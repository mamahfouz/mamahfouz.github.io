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
  body .container.mt-5 {
    margin-top: 0 !important;
    margin-bottom: 0 !important;
    padding: 0 !important;
    max-width: 100% !important;
    width: 100% !important;
    height: calc(100vh - 56px) !important;
    position: relative !important;
  }
  
  /* Hide the post header for this page */
  body .post header.post-header {
    display: none !important;
  }
  
  /* Make post wrapper full height */
  body .post {
    margin: 0 !important;
    padding: 0 !important;
    height: 100% !important;
  }
  
  /* Make article full height */
  body .post article {
    margin: 0 !important;
    padding: 0 !important;
    height: 100% !important;
  }
  
  .lineage-wrapper {
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
    border: none;
    overflow: hidden;
    display: block;
  }
  
  .lineage-wrapper iframe {
    width: 100%;
    height: 100%;
    min-height: 600px;
    border: none;
    display: block;
  }
</style>

<div class="lineage-wrapper">
  <iframe
    src="{{ '/assets/html/academic_lineage.html' | relative_url }}"
    frameborder="0"
    scrolling="no"
    allowfullscreen
    loading="eager"
    title="Academic Lineage Visualization">
  </iframe>
</div>
