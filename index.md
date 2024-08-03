## Welcome to my really awesome website!

This is a website for people in my home to browse the games on my shelves so that they can pick out what they want to play. If you're not in my home then **Hey! What Gives?**

Right now it's just an empty website but one day it will be _very pretty_.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
