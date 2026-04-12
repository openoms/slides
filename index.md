---
layout: default
title: Presentations
---

# Presentations

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/openoms/slides)

## Elérhető prezentációk / Available presentations

Ezen az oldalon a Marp alapú diákat tudod böngészőből megtekinteni, illetve elérhető hozzájuk a nyers Markdown kód (Raw Markdown) is.
If you have exported your Marp Markdown to HTML, you can view the formatted slides directly in your browser here:

{% for file in site.static_files %}
{% if file.extname == '.html' %}
* **[{{ file.basename }} (Megtekintés HTML-ként)]({{ site.baseurl }}{{ file.url }})** | [Nyers Markdown (Raw MD)](https://raw.githubusercontent.com/openoms/slides/main{{ file.url | replace: '.html', '.md' }})
{% endif %}
{% endfor %}

## Minden Markdown forrásfájl (Raw Markdown Source)
{% for page in site.pages %}
  {% if page.name != 'index.md' and page.name != 'README.md' and page.ext == '.md' %}
* [{{ page.name }}]({{ page.url | relative_url }}) - ([GitHub forrás](https://github.com/openoms/slides/blob/main{{ page.url | replace: '.html', '.md' }}))
  {% endif %}
{% endfor %}
