You can find me on [instagram](https://instagram.com/alex.buckland) and [twitter](https://twitter.com/alexbuckland)

<ul>
   {% for item in site.data.menu.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
