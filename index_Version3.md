---
layout: default
title: "Manuskrip Perubatan Melayu — Indeks"
---

# Indeks Manuskrip

Kompendium ringkas rawatan tradisi (Bahasa Melayu sahaja). Pilih manuskrip untuk membaca detail.

<ul>
{% for m in site.manuscripts %}
  <li><a href="{{ m.url | relative_url }}">{{ m.title }}</a></li>
{% endfor %}
</ul>