---
layout: page
permalink: /publications/
title: Publications
description: My academic publications and presentations.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

<h2>Journal Articles</h2>
{% bibliography -f papers -q @article %}

<h2>Conference Proceedings</h2>
{% bibliography -f papers -q @inproceedings %}

<h2>Talks</h2>
{% bibliography -f papers -q @conference %}

</div>
