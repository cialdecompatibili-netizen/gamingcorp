---
layout: single
title: "Roma: tour guidati a piedi"
permalink: /tour/roma-tour-guidati/
description: "Tour guidati a piedi a Roma in piccolo gruppo: Colosseo, Foro Romano, Musei Vaticani, catacombe, Trastevere e Ghetto."
ref: "cat-roma-tour-guidati"
classes: wide
author_profile: false
---
<p class="nv-lead">Colosseo, Vaticano, catacombe e quartieri con una guida, in piccolo gruppo.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "roma-tour-guidati" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
