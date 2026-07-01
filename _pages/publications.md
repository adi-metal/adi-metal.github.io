---
layout: page
permalink: /publications/
title: Publications
description: Selected publications and preprints.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<style>
  .publications ol.bibliography li .abbr figure {
    align-items: center;
    display: flex;
    height: 6.5rem;
    justify-content: center;
    margin: 0 auto 0.75rem;
    overflow: hidden;
    width: 8.5rem;
  }

  .publications ol.bibliography li .abbr picture {
    display: block;
    height: 100%;
    width: 100%;
  }

  .publications ol.bibliography li .abbr picture img.preview {
    background: var(--global-bg-color);
    display: block;
    height: 100% !important;
    object-fit: contain;
    width: 100% !important;
  }

  @media (max-width: 575.98px) {
    .publications ol.bibliography li .abbr figure {
      height: 7rem;
      width: 10rem;
    }
  }
</style>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<p class="publication-note">* indicates equal contribution.</p>

<div class="publications">

{% bibliography %}

</div>
