---
layout: single
title: "Vino e sapori del Lazio"
permalink: /tour/vino-sapori/
description: "Tour del vino e dei sapori nel Lazio: degustazioni a Frascati, Castelli Romani e Tuscia, con guida e pullman."
ref: "cat-vino-sapori"
classes: wide
author_profile: false
---
<p class="nv-lead">Cantine, frantoi e pranzi tipici tra Frascati, Castelli Romani e Tuscia.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "vino-sapori" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
