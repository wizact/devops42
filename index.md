---
layout: home
---
{% assign sorted_pages = site.pages | sort:"order" %}
{% for node in sorted_pages %}
{% if node.order > 0 %}

{% assign indent = node.sub %}
<li style="margin-left: {{indent | times: 20}}px"><a href="{{site.baseurl}}/{{node.url}}">{{node.title}}</a></li>
{% endif %}
{% endfor %}
