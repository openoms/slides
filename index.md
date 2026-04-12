---
layout: default
title: Presentations
---

# Presentations

Here are the available slide decks and materials:

## Slide Presentations (Embeds)
{% assign base_url = "https://openoms.github.io/slides" %}

{% for file in site.static_files %}
{% if file.extname == '.pptx' %}
### {{ file.basename }}

<iframe src="https://view.officeapps.live.com/op/embed.aspx?src={{ base_url }}{{ file.path }}" width="100%" height="600px" frameborder="0" title="{{ file.basename }}">This is an embedded Microsoft Office presentation, powered by Office.</iframe>

[Download PPTX]({{ file.path | relative_url }})
{% endif %}
{% endfor %}

## Formatted HTML Slides
If you have exported your Marp Markdown to HTML, you can view the formatted slides directly in your browser here:

{% for file in site.static_files %}
{% if file.extname == '.html' %}
* [{{ file.basename }} (View Slides)]({{ file.path | relative_url }})
{% endif %}
{% endfor %}

## Raw Markdown Source
{% for page in site.pages %}
  {% if page.name != 'index.md' and page.name != 'README.md' and page.ext == '.md' %}
* [{{ page.name }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}
