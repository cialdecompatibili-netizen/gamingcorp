---
layout: single
title: "Bici, natura e trekking"
permalink: /tour/bici-natura/
description: "Tour in e-bike, laghi e passeggiate nella natura vicino a Roma: Appia Antica, Castelli Romani, lago di Bracciano."
ref: "cat-bici-natura"
classes: wide
author_profile: false
---
<p class="nv-lead">E-bike sull'Appia Antica, laghi e passeggiate vicino a Roma.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "bici-natura" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
