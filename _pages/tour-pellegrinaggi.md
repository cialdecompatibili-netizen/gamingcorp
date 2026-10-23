---
layout: single
title: "Pellegrinaggi e turismo religioso"
permalink: /tour/pellegrinaggi/
description: "Pellegrinaggi e turismo religioso da Mentana e Roma: Assisi, Cascia e Loreto, con pullman, guida e assistenza."
ref: "cat-pellegrinaggi"
classes: wide
author_profile: false
---
<p class="nv-lead">Assisi, Cascia, Loreto: giornate e weekend con guida e momenti di preghiera.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "pellegrinaggi" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
