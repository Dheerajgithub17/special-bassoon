---
layout: template
author: Dheeraj
---

# Home page

Who am I?

My name is {{ page.author }}

## _Docs as Code_

Documentation as Code (Docs as Code) refers to a philosophy that you should be writing documentation with the same tools as code.

{% for item in site.data.employment %}
{{ item.company }}, {{ item.years }}
{% endfor %}

- Issue Trackers
- Version Control (Git)
- Plain Text Markup (Markdown, reStructuredText, Asciidoc)
- Code Reviews
- Automated Tests


