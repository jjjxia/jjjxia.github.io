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
    <p class="about__lead">Hello! I’m Jiahao, a computer science undergraduate at the University of Maryland working on probabilistic program analysis and compiler validation, with interests in formal methods and ML systems.</p>
    <div class="about__links" aria-label="Profile links">
      <a class="about__button about__button--primary" href="mailto:{{ site.author.email }}"><i class="fas fa-envelope" aria-hidden="true"></i> Email me</a>
      <a class="about__button" href="{{ site.author.googlescholar }}"><i class="ai ai-google-scholar" aria-hidden="true"></i> Google Scholar</a>
      <a class="about__button" href="https://github.com/{{ site.author.github }}"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
    </div>
  </header>

  <section class="about__section" aria-labelledby="research-heading">
    <div class="about__section-heading">
      <div>
        <p class="about__kicker">Research projects</p>
        <h2 id="research-heading">Research Experience</h2>
      </div>
    </div>
    <article class="about__experience">
      <div class="about__experience-meta">
        <span><time datetime="2025-05">May 2025</time> – <time datetime="2026-08">Aug 2026</time></span>
      </div>
      <h3>PSoufflé: Probabilistic Logic Inference for Program Analysis</h3>
      <p>Worked with Prof. Jingbo Wang at Purdue University on <a href="https://github.com/psouffle-lang/psouffle">PSoufflé</a>, a Soufflé-based system for scalable exact probabilistic inference in program analysis. The <a href="https://github.com/psouffle-lang">PSoufflé organization</a> hosts the project.</p>
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
          <a href="https://github.com/psouffle-lang/psouffle"><i class="fab fa-github" aria-hidden="true"></i> Code</a>
        </div>
    </div>
    <p class="about__note"><sup>∗</sup> Equal contribution.</p>
  </section>

  <section class="about__section" aria-labelledby="service-heading">
    <div class="about__section-heading">
      <div>
        <p class="about__kicker">Academic community</p>
        <h2 id="service-heading">Service</h2>
      </div>
    </div>
    <article class="about__experience">
      <h3>Artifact Evaluation Committee Member, TACAS 2027</h3>
      <p>Tools and Algorithms for the Construction and Analysis of Systems</p>
    </article>
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
