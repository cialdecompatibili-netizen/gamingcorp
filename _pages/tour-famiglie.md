---
layout: single
title: "Famiglie e bambini"
permalink: /tour/famiglie/
description: "Tour per famiglie e bambini a Roma e nel Lazio: caccia al tesoro, Parco dei Mostri di Bomarzo e visite con giochi."
ref: "cat-famiglie"
classes: wide
author_profile: false
---
<p class="nv-lead">Tour a misura di bambino: giochi, caccia al tesoro e ritmi rilassati.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "famiglie" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
