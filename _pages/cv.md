---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 2
---

<style>
.post-header{display:none;}

.cv-page-header{display:flex;justify-content:space-between;align-items:baseline;flex-wrap:wrap;gap:1rem;margin-bottom:1.5rem;}
.cv-page-header h1{font-size:1.6rem;font-weight:700;margin:0;}
.cv-download{display:inline-flex;align-items:center;gap:.5rem;font-size:.9rem;font-weight:600;color:var(--global-theme-color);text-decoration:none;border:1px solid var(--global-theme-color);border-radius:6px;padding:.45rem .9rem;}
.cv-download:hover{background:var(--global-theme-color);color:var(--global-hover-text-color);}

.cv-embed{width:100%;height:85vh;border:1px solid var(--global-divider-color);border-radius:6px;}
.cv-fallback{display:none;font-size:.9rem;color:var(--global-text-color-light);margin-top:.75rem;}

@media(max-width:576px){
  .cv-embed{display:none;}
  .cv-fallback{display:block;}
}
</style>

<div class="cv-page-header">
  <h1>CV</h1>
  <a class="cv-download" href="/assets/pdf/Joshi_Smriti_CV.pdf" download><i class="fas fa-download"></i> Download PDF</a>
</div>

<embed class="cv-embed" src="/assets/pdf/Joshi_Smriti_CV.pdf" type="application/pdf">
<p class="cv-fallback">PDF preview isn't available on this device &mdash; use the download link above to view the CV.</p>
