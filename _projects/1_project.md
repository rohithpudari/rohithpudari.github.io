---
layout: page
title: project 1
description: a project with a background image
img: assets/img/prof_pics.jpg
importance: 1
category: work
related_publications: einstein1956investigations, einstein1950meaning
---

This starter project now points at assets that exist in the repository, so the generated site and broken-link checks stay green.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prof_pics.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The layout still behaves like a normal project page, but it no longer depends on placeholder images that are missing from the repo.
