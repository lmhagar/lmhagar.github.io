---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

A version of my teaching dossier is available [here](LukeHagarDossier_Sep25.pdf).

The courses I have taught are detailed below.

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
