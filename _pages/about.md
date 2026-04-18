---
layout: page
permalink: /
title: about
nav: true
nav_order: 1
---

<style>
body,html{background:linear-gradient(135deg,#ffd3ac 0%,#ffb5ab 25%,#e39a7b 50%,#b298e7 75%,#b8e3e9 100%) fixed !important;background-attachment:fixed !important;}
.container{max-width:1200px !important;}
.post{background:transparent;}
.post-header{display:none;}
nav#navbar{background:rgba(255,255,255,0.62) !important;backdrop-filter:blur(14px) !important;-webkit-backdrop-filter:blur(14px) !important;border-bottom:1px solid rgba(255,255,255,0.35) !important;box-shadow:0 1px 14px rgba(0,0,0,0.07) !important;}
nav#navbar .nav-link,nav#navbar .navbar-brand{color:#2d2d2d !important;}
.abv-nav{position:sticky;top:62px;z-index:900;display:flex;justify-content:center;flex-wrap:wrap;gap:0.2rem;padding:0.45rem 0.9rem;background:rgba(255,255,255,0.55);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);border-radius:999px;margin:0 auto 2.8rem;width:fit-content;box-shadow:0 2px 16px rgba(0,0,0,0.08);border:1px solid rgba(255,255,255,0.72);}
.abv-nav-link{padding:0.28rem 0.88rem;border-radius:999px;font-size:0.78rem;font-weight:600;color:rgba(30,20,10,0.58) !important;text-decoration:none !important;transition:background 0.18s,color 0.18s;}
.abv-nav-link:hover,.abv-nav-link.active{background:rgba(139,92,246,0.15);color:#7c3aed !important;text-decoration:none !important;}
.abt-hero{display:flex;align-items:flex-start;gap:2rem;margin-bottom:1.6rem;}
.abt-photo{width:200px;height:200px;border-radius:50%;object-fit:cover;flex-shrink:0;border:3px solid rgba(255,255,255,0.82);box-shadow:0 4px 22px rgba(0,0,0,0.1);}
.abt-intro-block h1.abt-name{font-size:1.85rem;font-weight:800;color:#1c1c1e;margin-bottom:0.18rem;margin-top:0;}
.abt-intro-block .abt-subtitle{font-size:0.88rem;color:rgba(40,30,15,0.58);margin-bottom:0.8rem;}
.about-intro{font-size:1.05rem;font-weight:600;color:#5b2d00;margin-bottom:0.8rem;}
.abt-bio{font-size:0.91rem;line-height:1.72;color:rgba(30,20,10,0.8);margin-bottom:0.55rem;}
.abt-bio a{color:#7c3aed !important;}.abt-bio strong,.abt-bio b{color:#1c1c1e;}
.research-tags{display:flex;flex-wrap:wrap;gap:0.4rem;margin:0.7rem 0 1.2rem;}
.rtag{display:inline-block;padding:0.22rem 0.8rem;border-radius:999px;font-size:0.76rem;font-weight:600;background:rgba(139,92,246,0.1);color:#7c3aed;border:1.5px solid rgba(139,92,246,0.28);transition:background 0.2s;}
.rtag:hover{background:rgba(139,92,246,0.2);}
.tl-social-row{display:flex;gap:0.85rem;margin-bottom:0.5rem;}
.tl-social-icon{display:inline-flex;align-items:center;justify-content:center;width:46px;height:46px;border-radius:50%;background:rgba(255,255,255,0.62);backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);border:1.5px solid rgba(255,255,255,0.82);font-size:1.2rem;text-decoration:none !important;transition:transform 0.2s,background 0.2s,box-shadow 0.2s;box-shadow:0 2px 10px rgba(0,0,0,0.07);color:#3d3d3d !important;}
.tl-social-icon:hover{transform:translateY(-4px) scale(1.1);background:rgba(255,255,255,0.92) !important;box-shadow:0 6px 22px rgba(0,0,0,0.12);text-decoration:none !important;}
.tl-social-icon.sch{color:#4285f4 !important;}.tl-social-icon.li{color:#0a66c2 !important;}.tl-social-icon.gh{color:#24292f !important;}.tl-social-icon.em{color:#e05b4b !important;}
.afp-section{scroll-margin-top:130px;padding-top:0.25rem;margin-bottom:3.5rem;}
.section-label{font-size:0.68rem;font-weight:800;text-transform:uppercase;letter-spacing:0.14em;color:rgba(50,30,15,0.48) !important;margin-bottom:1.5rem;}
.htl-track::after{background:rgba(255,255,255,0.4) !important;}
.htl-main-btn .htl-dot{background:#8b5cf6;box-shadow:0 0 0 3px rgba(255,255,255,0.7),0 0 0 5px #8b5cf6;}
.htl-main-btn:hover .htl-dot,.htl-main-btn.active .htl-dot{box-shadow:0 0 0 3px rgba(255,255,255,0.7),0 0 0 5px #8b5cf6,0 0 16px rgba(139,92,246,0.5);}
.htl-dot--current{background:#8b5cf6 !important;animation:htl-pulse 2.8s ease-in-out infinite;}
@keyframes htl-pulse{0%,100%{box-shadow:0 0 0 3px rgba(255,255,255,0.7),0 0 0 5px #8b5cf6;}50%{box-shadow:0 0 0 3px rgba(255,255,255,0.7),0 0 0 7px #8b5cf6,0 0 20px rgba(139,92,246,0.4);}}
.htl-meta .htl-years{color:#8b5cf6 !important;}.htl-meta .htl-name{color:#1c1c1e !important;}.htl-meta .htl-org{color:rgba(40,40,40,0.62) !important;}
.htl-sub-btn{background:rgba(255,255,255,0.48) !important;border:1px dashed rgba(255,255,255,0.72) !important;}
.htl-sub-btn:hover,.htl-sub-btn.active{background:rgba(255,255,255,0.82) !important;border-color:rgba(139,92,246,0.5) !important;}
.htl-sub-text{color:rgba(40,40,40,0.78) !important;}.htl-sub-text b{color:#7c3aed !important;}
.htl-panel{background:rgba(255,255,255,0.58) !important;backdrop-filter:blur(18px) !important;-webkit-backdrop-filter:blur(18px) !important;border:1px solid rgba(255,255,255,0.8) !important;border-top:2.5px solid #8b5cf6 !important;border-radius:14px !important;padding:1.5rem !important;box-shadow:0 6px 28px rgba(0,0,0,0.07) !important;}
.htl-panel.is-hidden{display:none;}.htl-panel.is-visible{display:block;animation:htl-fadein 0.28s ease both;}
@keyframes htl-fadein{from{opacity:0;transform:translateY(-6px);}to{opacity:1;transform:translateY(0);}}
.htl-panel-header h3{color:#1c1c1e !important;font-size:1rem;}.htl-panel-header p{color:rgba(40,40,40,0.7) !important;}
.htl-ph-meta{color:#8b5cf6 !important;}.htl-panel-close{color:rgba(50,50,50,0.45) !important;}.htl-panel-close:hover{color:#1c1c1e !important;}
.photo-slot{background:rgba(255,255,255,0.35) !important;border:1px dashed rgba(255,255,255,0.62) !important;}
.section-divider{display:flex;align-items:center;gap:0.75rem;margin:0 0 1.6rem;}
.section-divider-line{flex:1;height:1.5px;background:rgba(255,255,255,0.5);}
.section-divider-title{display:flex;align-items:center;gap:0.55rem;}
.section-divider-title h2{font-size:1.1rem !important;font-weight:700 !important;margin:0 !important;color:#1c1c1e !important;}
.sec-icon{width:28px;height:28px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:0.76rem;color:#fff;}
.cat-card{background:rgba(255,255,255,0.52) !important;backdrop-filter:blur(16px) !important;-webkit-backdrop-filter:blur(16px) !important;border:1px solid rgba(255,255,255,0.76) !important;box-shadow:0 4px 20px rgba(0,0,0,0.06) !important;border-radius:14px !important;}
.cat-card:hover{background:rgba(255,255,255,0.78) !important;box-shadow:0 8px 32px rgba(0,0,0,0.1) !important;transform:translateY(-3px) !important;}
.cat-card .cat-card-title{color:#1c1c1e !important;}.cat-card .cat-card-desc{color:rgba(40,40,40,0.74) !important;}.cat-card .cat-card-desc a{color:#7c3aed !important;}
@media(min-width:960px){.cat-cards{grid-template-columns:repeat(3,1fr) !important;}}
.pub-section-wrapper .publications ol.bibliography{padding-left:0 !important;}
.pub-section-wrapper .publications li{background:rgba(255,255,255,0.48) !important;backdrop-filter:blur(12px) !important;-webkit-backdrop-filter:blur(12px) !important;border:1px solid rgba(255,255,255,0.72) !important;border-radius:10px;padding:1rem 1.2rem !important;margin-bottom:0.75rem !important;}
.pub-section-wrapper .publications li:hover{background:rgba(255,255,255,0.72) !important;}
footer.fixed-bottom{background:rgba(255,255,255,0.56) !important;backdrop-filter:blur(10px) !important;-webkit-backdrop-filter:blur(10px) !important;border-top:1px solid rgba(255,255,255,0.45) !important;}
footer.fixed-bottom p,footer.fixed-bottom a,footer.fixed-bottom span{color:#3d3d3d !important;}
@media(max-width:600px){.abt-hero{flex-direction:column;align-items:center;}.tl-social-row{justify-content:center;}.abv-nav{top:56px;}}
</style>

<div class="about-full-page">

<!-- In-page section navigation -->
<nav class="abv-nav" id="abv-nav" role="navigation" aria-label="Page sections">
  <a class="abv-nav-link active" href="#sec-about">About</a>
  <a class="abv-nav-link" href="#sec-affiliations">Affiliations</a>
  <a class="abv-nav-link" href="#sec-challenges">Challenges</a>
  <a class="abv-nav-link" href="#sec-leadership">Leadership</a>
  <a class="abv-nav-link" href="#sec-impact">Impact</a>
  <a class="abv-nav-link" href="#sec-publications">Publications</a>
</nav>

<!-- ============================================================
     ABOUT
     ============================================================ -->
<section class="afp-section" id="sec-about" aria-label="About">
  <div class="abt-hero">
    <img class="abt-photo" src="/assets/img/prof_pic.jpg" alt="Smriti Joshi">
    <div class="abt-intro-block">
      <h1 class="abt-name">Smriti Joshi</h1>
      <div class="about-intro">PhD Researcher &middot; Trustworthy AI in HealthCare</div>
  <p class="abt-bio">I am a PhD Researcher at <a href="https://www.bcn-aim.org/"><strong>BCN-AIM</strong></a>, Universitat de Barcelona, funded by the Horizon Europe Project <strong><a href="https://radioval.eu/">RadioVal</a></strong>. My work focuses on building models and engaging community for advancing Health AI.</p>

  <!-- <div class="research-tags">
    <span class="rtag">Uncertainty Estimation</span>
    <span class="rtag">Domain Adaptation</span>
    <span class="rtag">Breast MRI</span>
    <span class="rtag">Robust AI</span>
    <span class="rtag">EU Horizon</span>
  </div> -->
  <div class="tl-social-row">
    <a class="tl-social-icon sch" href="https://scholar.google.com/citations?user=17124487720810434582" target="_blank" rel="noopener" aria-label="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="tl-social-icon li" href="https://www.linkedin.com/in/joshi-smriti/" target="_blank" rel="noopener" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
    <a class="tl-social-icon gh" href="https://github.com/smriti-joshi" target="_blank" rel="noopener" aria-label="GitHub"><i class="fab fa-github"></i></a>
    <a class="tl-social-icon em" href="mailto:smriti.joshi@ub.edu" aria-label="Email"><i class="fas fa-envelope"></i></a>
  </div>
</section>

<!-- ============================================================
     AFFILIATIONS
     ============================================================ -->
<section class="afp-section" id="sec-affiliations" aria-label="Affiliations and Education">
  <p class="section-label">Affiliations &amp; Education</p>
  <div class="htl-scroll-wrapper">
    <div class="htl-track">

      <div class="htl-node-group">
        <button class="htl-main-btn" data-gallery="bits" aria-label="BITS Pilani"><span class="htl-dot"></span></button>
        <div class="htl-meta">
          <span class="htl-years">2014 &ndash; 2018</span>
          <span class="htl-name">MSc Physics</span>
          <span class="htl-org">BITS Pilani, India</span>
        </div>
        <button class="htl-sub-btn" data-gallery="xlim" aria-label="XLIM Lab thesis">
          <span class="htl-sub-dot"></span>
          <span class="htl-sub-text">XLIM Lab, France<br><b>Thesis Exchange</b></span>
        </button>
      </div>

      <div class="htl-node-group">
        <button class="htl-main-btn" data-gallery="erasmus" aria-label="Erasmus Mundus MSc"><span class="htl-dot"></span></button>
        <div class="htl-meta">
          <span class="htl-years">2019 &ndash; 2021</span>
          <span class="htl-name">MSc IPCV (Honors)</span>
          <span class="htl-org">Erasmus Mundus</span>
        </div>
        <button class="htl-sub-btn" data-gallery="harvard" aria-label="Harvard VCG thesis">
          <span class="htl-sub-dot"></span>
          <span class="htl-sub-text">Harvard VCG, USA<br><b>MSc Thesis</b></span>
        </button>
      </div>

      <div class="htl-node-group">
        <button class="htl-main-btn" data-gallery="bcn" aria-label="BCN-AIM PhD"><span class="htl-dot htl-dot--current"></span></button>
        <div class="htl-meta">
          <span class="htl-years">2021 &ndash; Present</span>
          <span class="htl-name">PhD Candidate</span>
          <span class="htl-org">BCN-AIM &middot; Universitat de Barcelona</span>
        </div>
      </div>

    </div>
  </div>
  <div class="htl-panel is-hidden" id="htl-panel">
    <div class="htl-panel-inner">
      <button class="htl-panel-close" id="htl-panel-close" aria-label="Close panel">&times;</button>
      <div class="htl-panel-header" id="htl-panel-header"></div>
      <div class="htl-photo-grid" id="htl-photo-grid"></div>
    </div>
  </div>
</section>

<!-- ============================================================
     CHALLENGES
     ============================================================ -->
<section class="afp-section" id="sec-challenges" aria-label="Challenges">
  <div class="section-divider">
    <div class="section-divider-line"></div>
    <div class="section-divider-title">
      <span class="sec-icon" style="background:#c0392b"><i class="fas fa-bolt"></i></span>
      <h2>Challenges</h2>
    </div>
    <div class="section-divider-line"></div>
  </div>
  <div class="cat-cards">
    <div class="cat-card">
      <div class="cat-card-title">MAMA-MIA Challenge &mdash; Co-organizer</div>
      <div class="cat-card-when" style="color:#c0392b">MICCAI 2025</div>
      <p class="cat-card-desc">Designed and ran an open challenge on generalizable and fair tumor segmentation and pCR prediction using breast MRI. <a href="https://mama-mia.grand-challenge.org/" target="_blank" rel="noopener">Challenge page &rarr;</a></p>
    </div>
    <div class="cat-card">
      <div class="cat-card-title">ODELIA Challenge &mdash; Top-2 Solution</div>
      <div class="cat-card-when" style="color:#c0392b">MICCAI 2025</div>
      <p class="cat-card-desc">Placed Top-2 in the <a href="https://odelia-ai.eu/" target="_blank" rel="noopener">ODELIA</a> multi-center breast MRI challenge, demonstrating strong cross-site generalizability of our domain-adaptive approach.</p>
    </div>
  </div>
</section>

<!-- ============================================================
     LEADERSHIP
     ============================================================ -->
<section class="afp-section" id="sec-leadership" aria-label="Leadership">
  <div class="section-divider">
    <div class="section-divider-line"></div>
    <div class="section-divider-title">
      <span class="sec-icon" style="background:#0f766e"><i class="fas fa-users"></i></span>
      <h2>Leadership</h2>
    </div>
    <div class="section-divider-line"></div>
  </div>
  <div class="cat-cards">
    <div class="cat-card">
      <div class="cat-card-title">AI Working Group Lead &mdash; RadioVal</div>
      <div class="cat-card-when" style="color:#0f766e">2021 &ndash; Present</div>
      <p class="cat-card-desc">Leading the AI research workstream in <a href="https://radioval.eu/" target="_blank" rel="noopener">RadioVal</a>, an EU Horizon Europe project on clinical validation of AI for breast cancer treatment response.</p>
    </div>
    <div class="cat-card">
      <div class="cat-card-title">MICCAI 2024 LMIC Initiative &mdash; Committee Member</div>
      <div class="cat-card-when" style="color:#0f766e">2024</div>
      <p class="cat-card-desc">Served on the Grant Selection &amp; Sponsorship Committee for the <a href="https://conferences.miccai.org/2024/en/" target="_blank" rel="noopener">MICCAI 2024 LMIC Initiative</a>, leading selection of 50+ early-career researchers from lower-income countries.</p>
    </div>
    <div class="cat-card">
      <div class="cat-card-title">International AI Schools &mdash; AFRICAI</div>
      <div class="cat-card-when" style="color:#0f766e">2021 &ndash; Present</div>
      <p class="cat-card-desc">Active member of <a href="https://africai.org/" target="_blank" rel="noopener">AFRICAI</a>. Coordinated international AI schools across Africa and South Asia, connecting researchers to global medical AI communities.</p>
    </div>
  </div>
</section>

<!-- ============================================================
     IMPACT
     ============================================================ -->
<section class="afp-section" id="sec-impact" aria-label="Impact">
  <div class="section-divider">
    <div class="section-divider-line"></div>
    <div class="section-divider-title">
      <span class="sec-icon" style="background:#7c3aed"><i class="fas fa-star"></i></span>
      <h2>Impact</h2>
    </div>
    <div class="section-divider-line"></div>
  </div>
  <div class="cat-cards">
    <div class="cat-card">
      <div class="cat-card-title">Test-Time Adaptation for Breast MRI</div>
      <div class="cat-card-when" style="color:#7c3aed">MICCAI 2025 &mdash; First Author</div>
      <p class="cat-card-desc">Robust tumor segmentation under domain shift without retraining &mdash; addressing a core bottleneck for real-world deployment of clinical AI across diverse acquisition conditions.</p>
    </div>
    <div class="cat-card">
      <div class="cat-card-title">Uncertainty Estimation for Robust AI</div>
      <div class="cat-card-when" style="color:#7c3aed">SPIE 2024 &mdash; First Author</div>
      <p class="cat-card-desc">Investigated well-calibrated uncertainty signals for flagging unreliable predictions in breast MRI segmentation &mdash; a key ingredient for building clinician trust in AI.</p>
    </div>
    <div class="cat-card">
      <div class="cat-card-title">3 Co-authored Journal &amp; Book Publications</div>
      <div class="cat-card-when" style="color:#7c3aed">2025</div>
      <p class="cat-card-desc">JMI review on generative AI for imaging simulations, a Scientific Data paper on large-scale breast MRI datasets, and a book chapter on stakeholder perspectives in AI for healthcare.</p>
    </div>
    <div class="cat-card">
      <div class="cat-card-title">medigan &mdash; Clinical AI Framework</div>
      <div class="cat-card-when" style="color:#7c3aed">JMI 2023</div>
      <p class="cat-card-desc">Co-authored <em>medigan</em>, an open-source framework for medical image synthesis adopted across multiple research groups for synthetic data generation and augmentation.</p>
    </div>
  </div>
</section>

<!-- ============================================================
     PUBLICATIONS
     ============================================================ -->
<section class="afp-section pub-section-wrapper" id="sec-publications" aria-label="Publications">
  <div class="section-divider">
    <div class="section-divider-line"></div>
    <div class="section-divider-title">
      <span class="sec-icon" style="background:#1d4ed8"><i class="fas fa-book-open"></i></span>
      <h2>Publications</h2>
    </div>
    <div class="section-divider-line"></div>
  </div>
  <div class="publications">
    {% bibliography -f {{ site.scholar.bibliography }} %}
  </div>
</section>

</div>

<script>
(function(){
  'use strict';
  var GALLERY_DATA={
    bits:{title:'MSc Physics &middot; BITS Pilani',meta:'2014 &ndash; 2018 &middot; Pilani, Rajasthan, India',desc:'Four years studying Physics at BITS Pilani, one of India\'s premier institutions. Built a strong foundation in classical mechanics, electrodynamics, statistical mechanics, and computational methods.',photos:[]},
    xlim:{title:'Thesis Exchange &middot; XLIM Research Institute',meta:'During MSc &middot; Limoges, France',desc:'Conducted thesis research at the XLIM Research Institute (CNRS UMR 7252) in France &mdash; the first international research experience, at the intersection of applied physics and signal processing.',photos:[]},
    erasmus:{title:'MSc Image Processing &amp; Computer Vision (Honors)',meta:'2019 &ndash; 2021 &middot; Erasmus Mundus Joint Master\'s',desc:'Prestigious Erasmus Mundus Joint Master\'s across three European universities: Autonomous University of Madrid (Spain), University of Bordeaux (France), and P\u00e1zm\u00e1ny P\u00e9ter Catholic University (Hungary). Graduated with Honors.',photos:[]},
    harvard:{title:'MSc Thesis &middot; VCG SEAS, Harvard University',meta:'2021 &middot; Cambridge, Massachusetts, USA',desc:'Conducted MSc thesis research at the Visual Computing Group, SEAS, Harvard University. Focused on unsupervised domain adaptation for large-scale electron microscopy connectomics data.',photos:[]},
    bcn:{title:'Research Associate &rarr; PhD Candidate &middot; BCN-AIM, UB',meta:'2021 &ndash; Present &middot; Barcelona, Spain',desc:'Joined BCN-AIM as a Research Associate in 2021 and became a PhD Candidate from May 2022. Research focuses on trustworthy and robust AI for medical imaging within the EU Horizon RadioVal project.',photos:[]}
  };
  var PLACEHOLDER_COUNT=3;
  var panel=document.getElementById('htl-panel');
  var panelHdr=document.getElementById('htl-panel-header');
  var photoGrid=document.getElementById('htl-photo-grid');
  var closeBtn=document.getElementById('htl-panel-close');
  var mainBtns=document.querySelectorAll('.htl-main-btn');
  var subBtns=document.querySelectorAll('.htl-sub-btn');
  var currentId=null;
  function buildGrid(photos){var h='';if(photos&&photos.length){photos.forEach(function(s){h+='<div class="photo-slot"><img src="/'+s+'" alt="" loading="lazy"></div>';});}else{for(var i=0;i<PLACEHOLDER_COUNT;i++){h+='<div class="photo-slot"><div class="photo-placeholder"><i class="fas fa-image"></i><span>Add a photo</span></div></div>';}}return h;}
  function showPanel(id){var d=GALLERY_DATA[id];if(!d)return;currentId=id;panelHdr.innerHTML='<h3>'+d.title+'</h3><div class="htl-ph-meta">'+d.meta+'</div><p>'+d.desc+'</p>';photoGrid.innerHTML=buildGrid(d.photos);panel.classList.remove('is-visible');panel.classList.add('is-hidden');requestAnimationFrame(function(){requestAnimationFrame(function(){panel.classList.remove('is-hidden');panel.classList.add('is-visible');panel.scrollIntoView({behavior:'smooth',block:'nearest'});});});}
  function hidePanel(){panel.classList.remove('is-visible');panel.classList.add('is-hidden');clearActive();currentId=null;}
  function clearActive(){mainBtns.forEach(function(b){b.classList.remove('active');});subBtns.forEach(function(b){b.classList.remove('active');});}
  function handleClick(btn){var id=btn.getAttribute('data-gallery');if(currentId===id){hidePanel();return;}clearActive();btn.classList.add('active');showPanel(id);}
  mainBtns.forEach(function(btn){btn.addEventListener('click',function(){handleClick(btn);});});
  subBtns.forEach(function(btn){btn.addEventListener('click',function(){handleClick(btn);});});
  closeBtn.addEventListener('click',hidePanel);

  /* Scroll spy for in-page nav */
  var navLinks=document.querySelectorAll('.abv-nav-link');
  var sections=document.querySelectorAll('.afp-section');
  function onScroll(){
    var scrollY=window.pageYOffset;
    var activeId='sec-about';
    sections.forEach(function(sec){
      if(scrollY>=(sec.offsetTop-140)){activeId=sec.id;}
    });
    navLinks.forEach(function(link){
      link.classList.toggle('active',link.getAttribute('href')==='#'+activeId);
    });
  }
  window.addEventListener('scroll',onScroll,{passive:true});
  onScroll();
}());
</script>
