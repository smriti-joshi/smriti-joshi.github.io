---
layout: page
permalink: /
title: about
nav: false
---

<style>
.post-header{display:none;}

.about-header{display:flex;gap:1.75rem;align-items:center;margin-bottom:2rem;}
.about-photo{width:128px;height:128px;border-radius:12px;object-fit:cover;flex-shrink:0;}
.about-header-text h1{margin:0 0 .2rem;font-size:2rem;font-weight:700;}
.about-tagline{margin:0 0 .35rem;font-size:1.05rem;font-weight:600;color:var(--global-theme-color);}
.about-affil{margin:0 0 .8rem;font-size:.95rem;color:var(--global-text-color-light);}
.about-affil a{color:inherit;text-decoration:underline;}
.about-social{display:flex;flex-wrap:wrap;gap:1.1rem;}
.about-social a{display:inline-flex;align-items:center;gap:.4rem;font-size:.85rem;color:var(--global-text-color-light);text-decoration:none;}
.about-social a:hover{color:var(--global-theme-color);}

.about-bio{font-size:1rem;line-height:1.7;margin-bottom:0.9rem;}
.about-bio:last-of-type{margin-bottom:2.75rem;}

.about-page section{margin-bottom:2.75rem;}
.about-page section:last-child{margin-bottom:0;}
.about-page h2{font-size:1.05rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;padding-bottom:.5rem;margin-bottom:1.4rem;border-bottom:1px solid var(--global-divider-color);}

.see-all{margin-top:1.1rem;font-size:.9rem;}
.see-all a{color:var(--global-theme-color);font-weight:600;text-decoration:none;}
.see-all a:hover{text-decoration:underline;}

@media(max-width:576px){
  .about-header{flex-direction:column;align-items:flex-start;}
  .about-photo{width:100px;height:100px;}
}
</style>

<div class="about-page">

<div class="about-header">
  <img class="about-photo" src="/assets/img/smriti.png" alt="Smriti Joshi">
  <div class="about-header-text">
    <h1>Smriti Joshi</h1>
    <p class="about-tagline">ML Researcher &middot; Trustworthy AI in Healthcare</p>
    <p class="about-affil">PhD Researcher at <a href="https://www.bcn-aim.org/" target="_blank" rel="noopener">BCN-AIM</a>, Universitat de Barcelona</p>
    <div class="about-social">
      <a href="https://scholar.google.com/citations?user=17124487720810434582" target="_blank" rel="noopener"><i class="ai ai-google-scholar"></i> Google Scholar</a>
      <a href="https://orcid.org/0000-0001-8480-023X" target="_blank" rel="noopener"><i class="ai ai-orcid"></i> ORCID</a>
      <a href="https://www.linkedin.com/in/smriti1610/" target="_blank" rel="noopener"><i class="fab fa-linkedin"></i> LinkedIn</a>
      <a href="https://github.com/smriti-joshi" target="_blank" rel="noopener"><i class="fab fa-github"></i> GitHub</a>
      <a href="mailto:smriti.joshi@ub.edu"><i class="fas fa-envelope"></i> Email</a>
      <a href="/cv/"><i class="fas fa-file-alt"></i> CV</a>
    </div>
  </div>
</div>

<p class="about-bio">
I'm a PhD Researcher at <a href="https://www.bcn-aim.org/" target="_blank" rel="noopener">BCN-AIM</a>, Universitat de Barcelona, working on trustworthy AI for medical imaging &mdash; models that hold up under domain shift and multi-center clinical data, rather than just in-distribution benchmarks. My work sits at the intersection of domain adaptation, uncertainty estimation, and generative imaging, mostly applied to breast MRI within the Horizon Europe project <a href="https://radioval.eu/" target="_blank" rel="noopener">RadioVal</a>.
</p>
<p class="about-bio">
A good part of my time also goes into building shared infrastructure for the field: I co-organize community benchmarks like <a href="https://www.ub.edu/mama-mia/" target="_blank" rel="noopener">MAMA-MIA</a> and <a href="https://www.ub.edu/mama-synth/mama-synth" target="_blank" rel="noopener">MAMA-SYNTH</a>, and help coordinate AI schools and mentorship programs across Africa and South Asia through <a href="https://africai.org/" target="_blank" rel="noopener">AFRICAI</a>.
</p>

<section id="publications">
  <h2>Selected Publications</h2>
  <div class="publications">
    {% assign selected_keys = "joshi2026dense,garrucho2025mamamia,joshi2025tta,joshi2024uncertainty,cabrita2025stakeholder,joshi2021nn" | split: "," | join: "|" %}
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[key^={{ selected_keys }}]* %}
  </div>
  <p class="see-all"><a href="/publications/">See the full list of publications &rarr;</a></p>
</section>

</div>
