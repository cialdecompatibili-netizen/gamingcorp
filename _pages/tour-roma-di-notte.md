---
layout: single
title: "Roma di notte"
permalink: /tour/roma-di-notte/
description: "Roma di notte: tour serali guidati a Trastevere e nel centro storico, con rientro organizzato verso Mentana."
ref: "cat-roma-di-notte"
classes: wide
author_profile: false
---
<p class="nv-lead">Tour serali guidati per maggiorenni, con rientro organizzato.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "roma-di-notte" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
