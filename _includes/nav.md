<h2>{{ site.data.pagelist.page_list_title }}</h2>
<ul>
    {% for item in site.data.pagelist.pages %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
    {% endfor %}
</ul>
