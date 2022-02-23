---
title: Stuff and things
---

# uhhh wobsite

Hello I am Megan and I do things on the internet and I put them here and this is not really meant to be anything more than a dumping ground at this point, but it exists. I attempt to write code and write game reviews sometimes. Sometimes I contribute to [351ELEC](https://351elec.de) and pretend to be a useful team member.

# Projects

- [Meow Launcher](https://zowayix.github.io/Meow-Launcher), a game launcher thing that is also under construction, and not useful to people who aren't me yet.
- [MAME Memory Card Inserter](https://github.com/Zowayix/MAME-Memory-Card-Inserter): Inserts Neo Geo memory cards into emulated Neo Geo machines automatically in MAME, so one's progress can be saved the way things are intended.

Many other projects that I have forgotten about or abandoned! Maybe some that are actually useful but I just didn't feel like putting in a description and a link here.

# Game reviews

{% for post in site.categories.game-reviews %}
- [{{ post.title | replace: "*", "\*" }} ({{ post.platform }}, {{ post.release}}, {{ post.dev }}){%- if post.game-version %} ({{ post.game-version }}) {%- endif -%}{%- if post.play-notes %} ({{ post.play-notes }}) {%- endif -%}]({{ post.url }})
{% endfor %}

# Blog posts (just tests for now)

{% for post in site.categories.test-posts %}
## {{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}
