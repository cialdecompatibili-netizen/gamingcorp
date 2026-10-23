---
layout: single
title: "Gruppi, scuole e aziende"
permalink: /tour/gruppi-scuole-aziende/
description: "Gite per scuole, aziende, circoli e gruppi di amici da Mentana: programma su misura e preventivo gratuito."
ref: "cat-gruppi-scuole-aziende"
classes: wide
author_profile: false
---
<p class="nv-lead">Gite scolastiche, team building e uscite per circoli e associazioni, su preventivo.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "gruppi-scuole-aziende" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
