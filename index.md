---
title: Insurance Knowledge Repo
layout: default
---

# 🏠 Insurance Knowledge Repo

Welcome to the **HULA / Insurance Knowledge Repository** — a public collection of PDFs and learning resources covering Home, Umbrella, Life, and Auto insurance.

## Available Documents

Below are the PDFs currently hosted in this repository:

{% for pdf in site.static_files %}
  {% if pdf.extname == ".pdf" %}
- [{{ pdf.name }}]({{ pdf.path }})
  {% endif %}
{% endfor %}

- [Auto Insurance Guide](Auto_Insurance_Guide.pdf)
- [Homeowners Insurance Guide](Homeowners_Insurance_Guide.pdf)
- [MCL ACT 218 of 1956](MCL-ACT-218-OF-1956.pdf)

---
Maintained by [HULA Insurance Services](https://github.com/GG38040)
