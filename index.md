# Heading!

I don't know what to name websites. So this is under construction.

# Projects
[Meow Launcher](https://zowayix.github.io/Meow-Launcher), a game launcher thing that is also under construction, and not useful to people who aren't me yet.
[MAME Memory Card Inserter](https://github.com/Zowayix/MAME-Memory-Card-Inserter): Inserts Neo Geo memory cards into emulated Neo Geo machines automatically in MAME, so one's progress can be saved the way things are intended.

Many other projects that I have forgotten about or abandoned! Maybe some that are actually useful but I just didn't feel like putting in a description and a link here.

# Game reviews

Oh yeah so I actually started playing video games this year. I've given myself a task of writing about them all. Not sure why, something to do I guess.

{% for post in site.categories.game-reviews %}
- [{{ post.title || replace: "*", "\*" }} ({{ post.platform }}, {{ post.release}}, {{ post.dev }})]({{ post.url }})
{% endfor %}

# Blog posts (just tests for now)

{% for post in site.categories.test-posts %}
## {{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}
