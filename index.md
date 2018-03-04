---
title: One-Shot Games
---

# Ready-to-Play

{% for item in site.games %}

* [{{ item.title }}]({{ item.url | relative_url }})

{% endfor %}

# Ideas

{% for item in site.ideas %}

* [{{ item.title }}]({{ item.url | relative_url }})

{% endfor %}
