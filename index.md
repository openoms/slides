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
* **[{{ file.basename }} (Megtekintés HTML-ként)]({{ file.path | relative_url }})** | [Nyers Markdown (Raw MD)](https://raw.githubusercontent.com/openoms/slides/main/{{ file.path | replace: '.html', '.md' | remove_first: '/' }})
{% endif %}
{% endfor %}
