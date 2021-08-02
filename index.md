# Heading!

I don't know what to name websites. So this is under construction.

# Projects
[Meow Launcher](https://zowayix.github.io/Meow-Launcher), a game launcher thing that is also under construction, and not useful to people who aren't me yet.  
[MAME Memory Card Inserter](https://github.com/Zowayix/MAME-Memory-Card-Inserter): Inserts Neo Geo memory cards into emulated Neo Geo machines automatically in MAME, so one's progress can be saved the way things are intended.


# Blog posts

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.date }}
{{ post.excerpt }}  
{{ post.categories }}
{% endfor %}
