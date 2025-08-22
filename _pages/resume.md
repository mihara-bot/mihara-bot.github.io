---
layout: single
permalink: /resume/
title: "Resume"
excerpt: "Download and view my resume"
author_profile: false
classes: wide
---

<style>
  .page__content {
    margin: 0 !important;
    padding: 0 !important;
    max-width: 100% !important;
  }
  
  .page {
    margin: 0 !important;
    padding: 0 !important;
  }
  
  .masthead,
  .page__footer {
    display: none !important;
  }
  
  body {
    margin: 0;
    padding: 0;
  }
  
  .pdf-container {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    z-index: 9999;
  }
  
  .pdf-iframe {
    width: 100%;
    height: 100%;
    border: none;
  }
</style>
<div class="pdf-container">
  <iframe src="{{ site.url }}{{ site.baseurl }}/assets/files/resume.pdf" 
          class="pdf-iframe"
          title="Resume PDF">
    <p>Your browser does not support PDF viewing. Please <a href="{{ site.url }}{{ site.baseurl }}/assets/files/resume.pdf">download the PDF</a> to view it.</p>
  </iframe>
</div>
