
Running in the family
<ul>
   {% for item in site.data.menu.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
