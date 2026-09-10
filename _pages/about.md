---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
<div class="about">
  <header class="about__intro">
    <p class="about__eyebrow">Computer Science · University of Maryland</p>
    <p class="about__lead">Hello! I’m Jiahao, a junior exploring how compilers, formal methods, and machine learning systems can make complex programs faster and more trustworthy.</p>
    <div class="about__links" aria-label="Profile links">
      <a class="about__button about__button--primary" href="mailto:{{ site.author.email }}"><i class="fas fa-envelope" aria-hidden="true"></i> Email me</a>
      <a class="about__button" href="{{ site.author.googlescholar }}"><i class="ai ai-google-scholar" aria-hidden="true"></i> Google Scholar</a>
      <a class="about__button" href="{{ site.author.github }}"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
    </div>
  </header>

  <section class="about__section" aria-labelledby="research-heading">
    <div class="about__section-heading">
      <div>
        <p class="about__kicker">What I’m working on</p>
        <h2 id="research-heading">Research Experience</h2>
      </div>
    </div>
    <article class="about__experience">
      <div class="about__experience-meta">
        <span class="about__status"><span aria-hidden="true"></span> Current</span>
        <time datetime="2025-05">May 2025 – Present</time>
      </div>
      <h3>Scaling Probabilistic Logic Reasoning</h3>
      <p>Working with Soufflé and ProbLog to explore scalable probabilistic logic inference.</p>
    </article>
  </section>

  <section class="about__section" aria-labelledby="publications-heading">
    <div class="about__section-heading">
      <div>
        <p class="about__kicker">Selected work</p>
        <h2 id="publications-heading">Publications</h2>
      </div>
    </div>
    <div class="about__publications">
      <article class="about__publication">
        <div class="about__publication-topline">
          <span class="about__venue">FMCAD 2026</span>
          <span class="about__paper-type">Conference paper</span>
        </div>
        <h3>PSOUFFLÉ: Scaling Exact Probabilistic Logic Inference for Program Analysis</h3>
        <p class="about__authors">Xuyang Li<sup>∗</sup>, <strong>Jiahao Xia<sup>∗</sup></strong>, Ahmed Adnan, and Jingbo Wang</p>
        <p class="about__publication-venue"><em>Formal Methods in Computer-Aided Design (FMCAD)</em>, 2026</p>
        <div class="about__paper-links">
          <a href="https://repositum.tuwien.at/handle/20.500.12708/230507"><i class="fas fa-file-pdf" aria-hidden="true"></i> Paper</a>
          <a href="https://zenodo.org/records/20091940"><i class="fas fa-cube" aria-hidden="true"></i> Artifact</a>
        </div>
      </article>
      <article class="about__publication">
        <div class="about__publication-topline">
          <span class="about__venue about__venue--review">Under review</span>
          <span class="about__paper-type">CPP 2027</span>
        </div>
        <h3>End-to-End Verified Polyhedral Compilation</h3>
        <p class="about__authors">Xuyang Li, Minghai Lu, Siyu Chen, <strong>Jiahao Xia</strong>, Weiyi Chen, and Jingbo Wang</p>
      </article>
    </div>
    <p class="about__note"><sup>∗</sup> Equal contribution.</p>
  </section>

  <section class="about__section" aria-labelledby="interests-heading">
    <div class="about__section-heading">
      <div>
        <p class="about__kicker">Topics I care about</p>
        <h2 id="interests-heading">Research Interests</h2>
      </div>
    </div>
    <ul class="about__interests">
      <li><i class="fas fa-microchip" aria-hidden="true"></i><span>ML Systems <small>and ML Compilers</small></span></li>
      <li><i class="fas fa-code-branch" aria-hidden="true"></i><span>Compiler Optimization <small>and Program Analysis</small></span></li>
      <li><i class="fas fa-shield-alt" aria-hidden="true"></i><span>Formal Methods <small>and Verification</small></span></li>
    </ul>
  </section>
</div>
