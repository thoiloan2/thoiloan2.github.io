---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{% for link in site.links %}
  <h2><a href="{{ link.url }}">{{ link.title }}</a></h2>
  <p>{{ link.excerpt }}</p>
{% endfor %}
