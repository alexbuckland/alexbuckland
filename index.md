
Running in the family
<h2>{{ site.data.menu.docs_list_title }}</h2>
<ul>
   {% for item in site.data.menu.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
[Bio](about.md)

[Contact](contact.md)
