<!doctype html>
<html lang="{{ site.lang | default: 'en-US' }}">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">
    <link rel="favicon" href="{{ '/assets/img/favicon.ico' }}">
    <link rel="stylesheet" href="{{ '/assets/css/style.css' }}">
    <!--[if lt IE 9]>
    <script src="https://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
    {% seo %}
</head>
<nav>
    {% include nav.html %}
</nav>
<body>
    {{ content }}
</body>
<footer>
    {% include footer.html %}
</footer>
</html>
