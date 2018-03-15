---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
{% assign sorted_pages = site.pages | sort:"order" %}
{% for node in sorted_pages %}
{% if node.order > 0 %}
<li><a href="{{node.url}}">{{node.title}}</a></li>
{% endif %}
{% endfor %}