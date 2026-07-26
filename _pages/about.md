---
layout: page
permalink: /
title: about
nav: true
nav_order: 1
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

.about-bio{font-size:1rem;line-height:1.7;margin-bottom:2.75rem;}

.about-page section{margin-bottom:2.75rem;}
.about-page section:last-child{margin-bottom:0;}
.about-page h2{font-size:1.05rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;padding-bottom:.5rem;margin-bottom:1.4rem;border-bottom:1px solid var(--global-divider-color);}

.role{margin-bottom:1.6rem;}
.role:last-child{margin-bottom:0;}
.role-head{display:flex;justify-content:space-between;align-items:baseline;gap:1rem;flex-wrap:wrap;}
.role-title{font-weight:700;font-size:1rem;}
.role-date{font-weight:600;font-size:.85rem;color:var(--global-theme-color);white-space:nowrap;}
.role-org{font-style:italic;font-size:.9rem;color:var(--global-text-color-light);margin:.15rem 0 .6rem;}
.role ul{margin:0;padding-left:1.15rem;}
.role li{margin-bottom:.35rem;font-size:.95rem;line-height:1.55;}

.edu-item{margin-bottom:1.3rem;}
.edu-item:last-child{margin-bottom:0;}
.edu-head{display:flex;justify-content:space-between;align-items:baseline;gap:1rem;flex-wrap:wrap;}
.edu-title{font-weight:700;font-size:1rem;}
.edu-date{font-weight:600;font-size:.85rem;color:var(--global-theme-color);white-space:nowrap;}
.edu-org{font-style:italic;font-size:.9rem;color:var(--global-text-color-light);margin:.15rem 0 0;}
.edu-note{font-size:.88rem;color:var(--global-text-color-light);margin:.3rem 0 0;}

.skills p{font-size:.95rem;line-height:1.65;margin-bottom:.6rem;}
.skills p:last-child{margin-bottom:0;}

.about-page ul.plain{padding-left:1.15rem;margin:0;}
.about-page ul.plain li{font-size:.95rem;line-height:1.6;margin-bottom:.45rem;}

.see-all{margin-top:1.1rem;font-size:.9rem;}
.see-all a{color:var(--global-theme-color);font-weight:600;text-decoration:none;}
.see-all a:hover{text-decoration:underline;}

.languages-line{font-size:.95rem;}

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
      <a href="https://www.linkedin.com/in/smriti1610/" target="_blank" rel="noopener"><i class="fab fa-linkedin"></i> LinkedIn</a>
      <a href="https://github.com/smriti-joshi" target="_blank" rel="noopener"><i class="fab fa-github"></i> GitHub</a>
      <a href="mailto:smriti.joshi@ub.edu"><i class="fas fa-envelope"></i> Email</a>
    </div>
  </div>
</div>

<p class="about-bio">
I'm a PhD Researcher at <a href="https://www.bcn-aim.org/" target="_blank" rel="noopener">BCN-AIM</a>, Universitat de Barcelona, funded by the Horizon Europe project <a href="https://radioval.eu/" target="_blank" rel="noopener">RadioVal</a>. Over 4+ years I've built and validated deep learning systems for medical imaging &mdash; creating community benchmarks and collaborating closely with hospitals across multiple continents. My work centers on models that generalize across multi-center clinical data, with hands-on expertise in domain adaptation, uncertainty estimation, and generative imaging.
</p>

<section id="experience">
  <h2>Experience</h2>

  <div class="role">
    <div class="role-head">
      <span class="role-title">PhD Researcher</span>
      <span class="role-date">2021 &ndash; Present</span>
    </div>
    <p class="role-org">BCN-AIM Laboratory, Universitat de Barcelona &middot; Barcelona, Spain</p>
    <ul>
      <li>Research trustworthy and adaptive AI for medical imaging &mdash; understanding and improving model behavior under domain shift &mdash; within the EU Horizon Europe project <a href="https://radioval.eu/" target="_blank" rel="noopener">RadioVal</a>, validated across 8+ hospitals.</li>
      <li>Co-leading the <a href="https://www.ub.edu/mama-synth/mama-synth" target="_blank" rel="noopener">MAMA-SYNTH Challenge</a> (MICCAI 2026) for synthesis of virtual contrast-enhanced breast MRI.</li>
      <li>Co-organized the <a href="https://www.ub.edu/mama-mia/" target="_blank" rel="noopener">MAMA-MIA Challenge</a> (MICCAI 2025) for generalizable and fair tumor segmentation and treatment response prediction in breast MRI.</li>
      <li>Achieved a Top-2 solution in the <a href="https://odelia2025.grand-challenge.org/" target="_blank" rel="noopener">ODELIA Challenge</a> (MICCAI 2025) for breast cancer classification.</li>
      <li>Contributed to trustworthy AI research including the <a href="https://future-ai.eu/" target="_blank" rel="noopener">FUTURE-AI</a> framework.</li>
    </ul>
  </div>

  <div class="role">
    <div class="role-head">
      <span class="role-title">Research Fellow</span>
      <span class="role-date">Feb 2021 &ndash; Jul 2021</span>
    </div>
    <p class="role-org">VCG, SEAS, Harvard University &middot; U.S.A. (Remote)</p>
    <ul>
      <li>Developed a self-supervised domain adaptation method for a large-scale connectomics dataset.</li>
    </ul>
  </div>
</section>

<section id="education">
  <h2>Education</h2>

  <div class="edu-item">
    <div class="edu-head">
      <span class="edu-title">PhD, Mathematics and Computer Science</span>
      <span class="edu-date">2022 &ndash; Present</span>
    </div>
    <p class="edu-org">Artificial Intelligence in Medicine Lab (BCN-AIM), Universitat de Barcelona &middot; Spain</p>
    <p class="edu-note">Summer School: International Computer Vision Summer School, 2025</p>
  </div>

  <div class="edu-item">
    <div class="edu-head">
      <span class="edu-title">MSc, Image Processing and Computer Vision (Honors)</span>
      <span class="edu-date">2019 &ndash; 2021</span>
    </div>
    <p class="edu-org">Erasmus Mundus &middot; University of Bordeaux, Autonomous University of Madrid, P&aacute;zm&aacute;ny P&eacute;ter Catholic University &middot; France, Spain, Hungary</p>
    <p class="edu-note">MSc thesis at VCG, SEAS, Harvard University (remote)</p>
  </div>

  <div class="edu-item">
    <div class="edu-head">
      <span class="edu-title">Integrated MSc, Physics</span>
      <span class="edu-date">2014 &ndash; 2018</span>
    </div>
    <p class="edu-org">Birla Institute of Technology and Science, Pilani &middot; India</p>
    <p class="edu-note">Thesis exchange at XLIM Research Institute, France</p>
  </div>
</section>

<section id="skills">
  <h2>Skills</h2>
  <div class="skills">
    <p><strong>Modeling:</strong> Data curation &amp; harmonization, radiomics, diffusion models, GANs, flow matching, nnU-Net, transformers, domain adaptation, uncertainty estimation.</p>
    <p><strong>Validation:</strong> Benchmarking, clinical validation, statistical testing &amp; experimental design, fairness &amp; robustness analysis.</p>
    <p><strong>Tools:</strong> PyTorch, TensorFlow, Python, Docker, Git/GitHub.</p>
  </div>
</section>

<section id="publications">
  <h2>Selected Publications</h2>
  <div class="publications">
    {% assign selected_keys = "joshi2026dense,garrucho2025mamamia,joshi2025tta,joshi2024uncertainty,cabrita2025stakeholder,joshi2021nn" | split: "," | join: "|" %}
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[key^={{ selected_keys }}]* %}
  </div>
  <p class="see-all"><a href="/publications/">See the full list of publications &rarr;</a></p>
</section>

<section id="leadership">
  <h2>Leadership &amp; Impact</h2>

  <div class="role">
    <div class="role-head">
      <span class="role-title">Lead, AI Working Group</span>
      <span class="role-date">2022 &ndash; 2023</span>
    </div>
    <p class="role-org"><a href="https://radioval.eu/" target="_blank" rel="noopener">European Union Horizon Europe Project &mdash; RadioVal</a></p>
    <ul>
      <li>Coordinated all AI-related work within the international consortium of 16 partners.</li>
      <li>Facilitated interdisciplinary collaboration to ensure clinically-informed AI model development.</li>
    </ul>
  </div>

  <div class="role">
    <div class="role-head">
      <span class="role-title">Lead, Grant Selection &amp; Sponsorship Committee</span>
      <span class="role-date">2023 &ndash; 2024</span>
    </div>
    <p class="role-org"><a href="https://conferences.miccai.org/2024/en/" target="_blank" rel="noopener">MICCAI 2024 LMIC Initiative</a></p>
    <ul>
      <li>Led the selection process for 50+ early-career researchers from lower-to-middle income countries, supporting their attendance at MICCAI 2024.</li>
      <li>Secured sponsorships and coordinated finances to maximize the impact of the programme.</li>
    </ul>
  </div>

  <div class="role">
    <div class="role-head">
      <span class="role-title">Coordinator</span>
      <span class="role-date">2022 &ndash; 2024</span>
    </div>
    <p class="role-org"><a href="https://africai.org/summer-school-2023/" target="_blank" rel="noopener">AFRICAI Summer School</a> &amp; <a href="https://www.anais.naamii.org.np/home" target="_blank" rel="noopener">Annual Nepal AI School</a></p>
    <ul>
      <li>Organized international AI schools, fostering research collaboration across Africa and South Asia.</li>
      <li>Coordinated one-year mentorship programs for African researchers, supporting capacity-building and career development in medical AI.</li>
    </ul>
  </div>

  <div class="role">
    <div class="role-head">
      <span class="role-title">Mentorship</span>
    </div>
    <ul>
      <li>Master in Data Science 2025 @ Universitat de Barcelona &mdash; lecture on Domain Adaptation.</li>
      <li>ESMPE 2023, AI in Medical Physics &mdash; lecture on Data Acquisition, Curation and Storage.</li>
      <li>Mentor @ RISE-MICCAI Winter School 2022.</li>
    </ul>
  </div>
</section>

<section id="achievements">
  <h2>Achievements &amp; Honors</h2>
  <ul class="plain">
    <li>Top-2 solution in the <a href="https://odelia2025.grand-challenge.org/" target="_blank" rel="noopener">ODELIA Challenge</a> @ MICCAI 2025.</li>
    <li>Erasmus Mundus Master Scholarship (2019 &ndash; 2021).</li>
    <li>Honors MSc in <a href="https://ipcv.eu/" target="_blank" rel="noopener">Image Processing and Computer Vision (IPCV)</a>.</li>
    <li>Co-authored <em>medigan</em> (JMI 2023), an open-source framework for medical image synthesis adopted across multiple research groups.</li>
  </ul>
</section>

<section id="languages">
  <h2>Languages</h2>
  <p class="languages-line">English (Proficient) &middot; Hindi (Native) &middot; Spanish (B1) &middot; French (A2) &middot; Hungarian (A1)</p>
</section>

</div>
