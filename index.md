## Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Systems

<ul>
  {% for game in site.systems %}
    <li>
      <a href="{{ game.url }}">{{ game.title }}</a>
    </li>
  {% endfor %}
</ul>

## Modules (Under Construction)

<ul>
  {% for module in site.modules %}
    <li>
      <a href="{{ module.url }}">{{ module.title }}</a>
    </li>
  {% endfor %}
</ul>

## Find Me Elsewhere

[itch.io](https://latest-gator.itch.io/)
