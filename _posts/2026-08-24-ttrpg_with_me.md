---
layout: default
title: "TTRPG With Me"
---

# TTRPG With Me

This is a bit of an experiment. I'm going to list all the things I'd love to GM, and if you're interested in being at that table then you can gather a group of players, pick some time windows, and reach out to me. I'll probably be willing to run these things for you!

This page is incomplete, I'd be willing to run most RPGs, even/especially ones I haven't heard of before.
This page will automatically update as I add new games.

## I Can Run This Anytime

<ul>
{% assign systems = site.systems | where: "gm_prep", "None" %}
{% for system in systems %}
  <li><a href="{{ system.url }}">{{ system.title }}</a></li>
{% endfor %}
</ul>

## Need A Couple Days To Prep

<ul>
{% assign systems = site.systems | where: "gm_prep", "Days" %}
{% for system in systems %}
  <li><a href="{{ system.url }}">{{ system.title }}</a></li>
{% endfor %}
</ul>

## Greater Prep Required

<ul>
{% assign systems = site.systems | where: "gm_prep", "Weeks" %}
{% for system in systems %}
  <li><a href="{{ system.url }}">{{ system.title }}</a></li>
{% endfor %}
</ul>
