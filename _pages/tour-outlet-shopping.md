---
layout: single
title: "Outlet e shopping"
permalink: /tour/outlet-shopping/
description: "Gite shopping in pullman da Mentana: Castel Romano Designer Outlet, Valmontone Outlet e shopping di Natale a Roma."
ref: "cat-outlet-shopping"
classes: wide
author_profile: false
---
<p class="nv-lead">Pullman per gli outlet vicini a Roma, senza pensieri di parcheggio.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "outlet-shopping" | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{{ '/contatti/' | relative_url }}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{{ '/tour/' | relative_url }}">Tutte le categorie</a>.</p>
