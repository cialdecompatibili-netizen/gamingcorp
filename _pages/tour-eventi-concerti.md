---
layout: single
title: "Eventi, concerti e feste"
permalink: /tour/eventi-concerti/
description: "Pullman per concerti, partite e grandi eventi a Roma, e feste su misura: compleanni, addii al celibato e al nubilato."
ref: "cat-eventi-concerti"
classes: wide
author_profile: false
---
<p class="nv-lead">Pullman per concerti e partite, feste di compleanno e addii al celibato e nubilato.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "eventi-concerti" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
