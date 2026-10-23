---
layout: single
title: "Crediti foto"
permalink: /crediti-foto/
description: "Autori e licenze delle fotografie usate sul sito, da Wikimedia Commons."
ref: crediti-foto
author_profile: false
sitemap: false
---

Le fotografie dei tour sono tratte da Wikimedia Commons e usate secondo le licenze indicate.

{% for c in site.data.crediti %}- **{{ c[1].titolo }}**, {{ c[1].autore }}, licenza {{ c[1].licenza }} ([fonte]({{ c[1].url }}))
{% endfor %}
