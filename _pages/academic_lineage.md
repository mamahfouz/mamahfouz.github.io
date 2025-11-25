---
layout: page
permalink: /academic-lineage/
title: academic lineage
nav: true
nav_order: 3
description: academic lineage based on co-authorship network
---

<style>
  /* Override container styles for full-page visualization */
  .container {
    margin-top: 0 !important;
    margin-bottom: 0 !important;
    padding: 0 !important;
    max-width: 100% !important;
    width: 100% !important;
    height: calc(100vh - 56px); /* Full viewport minus navbar */
  }
  
  .lineage-wrapper {
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
    border: none;
    overflow: hidden;
  }
  
  .lineage-wrapper iframe {
    width: 100%;
    height: 100%;
    border: none;
    display: block;
  }
</style>

<div class="lineage-wrapper">
  <iframe
    src="{{ '/assets/html/academic_lineage.html' | relative_url }}"
    frameborder="0"
    scrolling="no"
    title="Academic Lineage Visualization">
  </iframe>
</div>
