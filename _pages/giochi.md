---
layout: single
classes: wide
author_profile: false
title: "Giochi"
permalink: /giochi/
description: "I giochi di GamingCorp: sviluppati da noi per browser, Android e PC."
ref: giochi
---
{%- comment -%} Elenco da _data/giochi.json (fonte unica). Stile in assets/css/gaming.css. {%- endcomment -%}
<div class="gc"><div class="gc-wrap gc-sec" style="padding-top:0">
<p class="gc-lead">I giochi di GamingCorp sono in sviluppo: ogni scheda dice a che punto siamo. Quelli con etichetta Demo sono prove di terzi, provvisorie.</p>
{%- assign cats = site.data.giochi.giochi | map: "categoria" | uniq -%}
{%- for c in cats -%}
<h2 class="gc-h2" style="margin-top:2.4rem">{{ c }}</h2>
<div class="gc-grid">
{%- for g in site.data.giochi.giochi -%}{%- if g.categoria == c -%}
<a class="gc-card" href="{{ '/giochi/' | append: g.id | append: '/' | relative_url }}">
{% if g.immagine %}<img class="gc-img" src="{{ g.immagine | relative_url }}" alt="{{ g.nome }}" loading="lazy">{% else %}<div class="gc-art" style="--c1:{{ g.colori[0] }};--c2:{{ g.colori[1] }}" aria-hidden="true">{{ g.simbolo }}</div>{% endif %}
<div class="gc-card-b"><div class="gc-badges">{% for x in g.piattaforme %}<span class="gc-badge">{{ x }}</span>{% endfor %}<span class="gc-badge gc-badge-n">{{ g.stato }}</span></div>
<span class="gc-card-t">{{ g.nome }}</span><span class="gc-card-d">{{ g.breve }}</span><span class="gc-card-m">{{ g.genere }} &middot; {{ g.prezzo }}</span></div></a>
{%- endif -%}{%- endfor -%}
</div>
{%- endfor -%}
</div></div>
