---
layout: single
title: "Gite per la terza età"
permalink: /tour/terza-eta/
description: "Gite per la terza età da Mentana e Roma: borghi, laghi e terme con ritmo tranquillo e accompagnatore."
ref: "cat-terza-eta"
classes: wide
author_profile: false
---
<p class="nv-lead">Ritmo lento, soste frequenti e accompagnatore: borghi, laghi e terme.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "terza-eta" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
