---
title: Megan's Generically Named Wobsite
---

# uhhh wobsite

Hello I am Megan and I do things on the internet and I put them here and this is not really meant to be anything more than a dumping ground at this point, but it exists. I attempt to write code and write game reviews sometimes. Sometimes I contribute to [AmberELEC](https://amberelec.org) and pretend to be a useful team member.

# Projects

- [MAME Memory Card Inserter](https://github.com/Miss-Inputs/MAME-Memory-Card-Inserter): Inserts Neo Geo memory cards into emulated Neo Geo machines automatically in MAME, so one's progress can be saved the way things are intended.
- [Meow Launcher](https://miss-inputs.github.io/Meow-Launcher), a game launcher thing that is also under construction, and not useful to people who aren't me yet. I guess you can ignore it for now.
- [geoguessr-map-maker](https://github.com/Miss-Inputs/geoguessr-map-maker) Half-baked Python tool/library to help generate GeoGuessr maps, which I used for a lot of GeoJSON -> map conversions.

Many other projects that I have forgotten about or abandoned! Maybe some that are actually useful (unlikely, a lot of them probably don't work or never did) but I just didn't feel like putting in a description and a link here.

Lots of GeoGuessr maps: See [here](https://miss-inputs.github.io/GeoGuessr-maps/).


# Game reviews

I try to write them sometimes, but I neglected doing so for an entire year. Here's hoping I remember to this time.

{% for post in site.categories.game-reviews %}
- [{{ post.title | replace: "*", "\*" }} ({{ post.platform }}, {%unless post.release.size%}{{post.release | date_to_string | date: "%Y "}}{%else%}{{post.release}}{%endunless%}, {{ post.dev }}){%- if post.game-version %} ({{ post.game-version }}) {%- endif -%}{%- if post.play-notes %} ({{ post.play-notes }}) {%- endif -%}]({{ post.url }})
{% endfor %}

# Blog posts (just tests for now)

Maybe one day I'll be a blogger.

{% for post in site.categories.test-posts %}
## {{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}

# Other places
[Bluesky](https://bsky.app/profile/miss-inputs.bsky.social)
[The less cool site](https://twitter.com/miss_inputs)
[YouTube](https://www.youtube.com/channel/UC8-LZ9t9ojFCraMYuXuj1ZA)
