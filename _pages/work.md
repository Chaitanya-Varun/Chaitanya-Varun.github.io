---
layout: modern-page
body_class: work-page
title: "Work"
eyebrow: "Engineering, research & community"
description: "From physical-layer hardware and radar signal processing to collaborative AI platforms and reliable cloud services."
permalink: /work/
---

<nav class="experience-index" aria-label="Jump to selected experience">
  <a href="#oracle">
    <span class="experience-index__logo experience-index__logo--oracle"><img src="{{ '/images/brands/oracle-o.png' | relative_url }}" alt=""></span>
    <span><strong>Oracle</strong><small>Distributed cloud systems</small></span>
  </a>
  <a href="#gpai">
    <span class="experience-index__logo experience-index__logo--gpai"><img src="{{ '/images/brands/gpai-compact.png' | relative_url }}" alt=""></span>
    <span><strong>GPAI</strong><small>Future of Work platform</small></span>
  </a>
  <a href="#wisig">
    <span class="experience-index__logo experience-index__logo--wisig"><img src="{{ '/images/brands/wisig-networks.png' | relative_url }}" alt=""></span>
    <span><strong>WiSig</strong><small>5G NR physical layer</small></span>
  </a>
  <a href="#drdo">
    <span class="experience-index__logo experience-index__logo--drdo"><img src="{{ '/images/brands/drdo.png' | relative_url }}" alt=""></span>
    <span><strong>DRDO ASL</strong><small>Radar signal processing</small></span>
  </a>
</nav>

<section class="experience-story experience-story--featured" id="oracle" aria-labelledby="oracle-title">
  <header class="experience-story__rail">
    <img class="experience-story__logo experience-story__logo--oracle" src="{{ '/images/brands/oracle-o.png' | relative_url }}" alt="Oracle">
    <p class="experience-story__period">July 2023–present</p>
    <p class="experience-story__role">Member of Technical Staff<br>Fusion Data Intelligence</p>
  </header>
  <div class="experience-story__body">
    <p class="experience-story__eyebrow">Oracle · Bengaluru</p>
    <h2 id="oracle-title">Building dependable control planes for cloud analytics.</h2>
    <p class="experience-story__lead">I work across database connectivity, subscription systems, security automation, monitoring, and production operations. The common thread is making distributed services safer to change and easier to operate.</p>

    <div class="impact-grid">
      <article>
        <i class="fas fa-link" aria-hidden="true"></i>
        <h3>Connectivity &amp; reliability</h3>
        <ul>
          <li>Implemented walletless production-database connectivity to reduce operational overhead.</li>
          <li>Decoupled database dependencies, migrated REST calls to secure SDKs, and introduced circuit breakers.</li>
        </ul>
      </article>
      <article>
        <i class="far fa-bell" aria-hidden="true"></i>
        <h3>Subscriptions &amp; notifications</h3>
        <ul>
          <li>Developed trial-subscription flows supporting new customer transactions.</li>
          <li>Added notification batching and established DKIM and DMARC policies.</li>
        </ul>
      </article>
      <article>
        <i class="fas fa-shield-alt" aria-hidden="true"></i>
        <h3>Cloud &amp; security automation</h3>
        <ul>
          <li>Managed integrations across IAM/IDCS, OAC, ADW, Object Storage, and Vaults.</li>
          <li>Automated dependency security updates and streamlined region rollouts, including government realms.</li>
        </ul>
      </article>
      <article>
        <i class="fas fa-chart-line" aria-hidden="true"></i>
        <h3>Operational excellence</h3>
        <ul>
          <li>Implemented zero-downtime backfills and improved fleet dashboards, activity logs, and proactive metrics.</li>
          <li>Resolved production issues on call and built low-latency database and hot-patching tools.</li>
        </ul>
      </article>
    </div>

    <div class="experience-meta">
      <span>Distributed systems</span><span>OCI</span><span>IAM / IDCS</span><span>ADW</span><span>Security automation</span><span>On-call</span>
    </div>
    <p class="experience-callout"><strong>Recognition:</strong> Above and Beyond Award, Oracle Analytics and AI organization.</p>
  </div>
</section>
<section class="work-section" aria-labelledby="earlier-work-title">
  <header class="work-section__heading">
    <p class="eyebrow">Earlier product work</p>
    <h2 id="earlier-work-title">Security analytics and international AI collaboration.</h2>
  </header>

  <div class="experience-card-grid">
    <article class="experience-card">
      <header>
        <span class="experience-card__logo experience-card__logo--oracle"><img src="{{ '/images/brands/oracle-o.png' | relative_url }}" alt="Oracle"></span>
        <span class="experience-card__period">May–July 2022</span>
      </header>
      <p class="experience-card__org">Oracle · Fusion Analytics Warehouse</p>
      <h3>Server Tech Intern</h3>
      <p>Developed a machine-learning detector for identifying susceptible actions in system activity logs, then built an end-to-end demonstration platform in Oracle APEX.</p>
      <div class="experience-meta"><span>ML for security</span><span>Log analytics</span><span>Oracle APEX</span></div>
    </article>

    <article class="experience-card" id="gpai">
      <header>
        <span class="experience-card__logo experience-card__logo--gpai"><img src="{{ '/images/brands/gpai.png' | relative_url }}" alt="Global Partnership on Artificial Intelligence"></span>
        <span class="experience-card__period">July 2022–June 2023</span>
      </header>
      <p class="experience-card__org">Global Partnership on Artificial Intelligence</p>
      <h3>Student Associate · Future of Work</h3>
      <p>Worked with Prof. Uday B. Desai to build a web platform where international AI research communities could collaborate and share their work. Presented the initiative on the Future of Work Student Community Panel at the 2022 GPAI Summit in Japan.</p>
      <div class="experience-meta"><span>Web platform</span><span>Research collaboration</span><span>Japan summit</span></div>
      <a class="text-link" href="https://www.gpai.ai/projects/future-of-work/">About Future of Work <span aria-hidden="true">↗</span></a>
    </article>
  </div>
</section>

<section class="work-section" aria-labelledby="foundations-work-title">
  <header class="work-section__heading work-section__heading--split">
    <div>
      <p class="eyebrow">Research &amp; systems foundations</p>
      <h2 id="foundations-work-title">Before cloud infrastructure, I worked closer to the signal.</h2>
    </div>
    <p>These internships shaped how I think about the full stack, from physical-layer hardware and sensing algorithms to the services that eventually operate them.</p>
  </header>

  <div class="foundation-experience-grid">
    <article class="foundation-experience" id="wisig">
      <header>
        <img class="foundation-experience__logo foundation-experience__logo--wisig" src="{{ '/images/brands/wisig-networks.png' | relative_url }}" alt="WiSig Networks">
        <div><span>June–August 2021</span><strong>Project Intern</strong></div>
      </header>
      <h3>5G NR physical-layer engineering</h3>
      <p>Worked with the WiSig Networks / IIT Hyderabad 5G Testbed physical-layer team. Developed modules and hardware IP cores for system-on-chip design using Vivado HLS, Vitis, and embedded programming.</p>
      <div class="experience-meta"><span>5G NR PHY</span><span>Vivado HLS</span><span>Vitis</span><span>SoC design</span></div>
      <a class="text-link" href="https://itic.iith.ac.in/StartUp/WiSig.html">About WiSig <span aria-hidden="true">↗</span></a>
    </article>

    <article class="foundation-experience" id="drdo">
      <header>
        <img class="foundation-experience__logo foundation-experience__logo--drdo" src="{{ '/images/brands/drdo.png' | relative_url }}" alt="DRDO">
        <div><span>December 2021–January 2022</span><strong>Winter Intern · Advanced Systems Laboratory</strong></div>
      </header>
      <h3>Machine learning for radar processing</h3>
      <p>Investigated machine-learning alternatives to traditional radar signal-processing algorithms, focusing on pulse repetition interval estimation at DRDO’s Advanced Systems Laboratory in Hyderabad.</p>
      <div class="experience-meta"><span>Radar</span><span>Signal processing</span><span>Machine learning</span><span>PRI estimation</span></div>
      <a class="text-link" href="https://drdo.gov.in/drdo/en/organisation/technology-cluster/missiles-and-strategic-systems">About ASL <span aria-hidden="true">↗</span></a>
    </article>
  </div>
</section>

<section class="work-section" aria-labelledby="community-work-title">
  <header class="work-section__heading">
    <p class="eyebrow">Building with communities</p>
    <h2 id="community-work-title">Early-stage engineering, teaching, and service.</h2>
  </header>

  <div class="community-work-grid">
    <article>
      <img src="{{ '/images/brands/cloudglance-symbol.png' | relative_url }}" alt="CloudGlance">
      <h3>CloudGlance</h3>
      <p class="experience-card__period">Founding engineer · Early stage</p>
      <p>Worked briefly on the earliest engineering foundations for AI-assisted document intelligence.</p>
      <a href="https://www.cloudglancelab.com/">Visit CloudGlance <span aria-hidden="true">↗</span></a>
    </article>
    <article>
      <img src="{{ '/images/brands/bitshala.png' | relative_url }}" alt="Bitshala">
      <h3>Bitshala</h3>
      <p class="experience-card__period">Volunteer</p>
      <p>Contribute to a community supporting Bitcoin FOSS developer education and open technical learning.</p>
      <a href="https://bitshala.org/">Visit Bitshala <span aria-hidden="true">↗</span></a>
    </article>
    <article>
      <img src="{{ '/images/brands/iit-hyderabad-symbol.png' | relative_url }}" alt="IIT Hyderabad">
      <h3>IIT Hyderabad</h3>
      <p class="experience-card__period">Teaching Assistant · 2022</p>
      <p>Tutored and evaluated students in Data Structures and Applications (ID2230).</p>
    </article>
    <article class="community-work-grid__text-card">
      <i class="fas fa-hands-helping" aria-hidden="true"></i>
      <h3>Oracle Volunteers</h3>
      <p class="experience-card__period">Member · 2023–present</p>
      <p>Active contributor to corporate social responsibility and volunteering initiatives.</p>
    </article>
  </div>
</section>

<section class="work-section" aria-labelledby="selected-work-title">
  <header class="work-section__heading work-section__heading--split">
    <div>
      <p class="eyebrow">Selected technical work</p>
      <h2 id="selected-work-title">Projects beyond the job description.</h2>
    </div>
    <p>Research prototypes and hands-on builds have been a recurring way for me to learn new systems.</p>
  </header>

  <article class="project-feature">
    <div class="project-feature__icon"><i class="far fa-images" aria-hidden="true"></i></div>
    <div>
      <p class="experience-card__period">Python · PyTorch · OpenCV</p>
      <h3>Project Album</h3>
      <p>Built an end-to-end photo-classification pipeline using OpenCV and deep learning, including face recognition and classification workflows.</p>
    </div>
  </article>
</section>

<section class="work-section" id="milestones" aria-labelledby="recognition-title">
  <header class="work-section__heading">
    <p class="eyebrow">Recognition</p>
    <h2 id="recognition-title">Selected outcomes along the way.</h2>
  </header>
  <div class="recognition-grid">
    <article><span>2023</span><h3>ICASSP challenges</h3><p>Winner of the LIMMITS Grand Challenge and first runner-up in the Five Minute Clip Contest.</p></article>
    <article><span>2023</span><h3>Google Research Week</h3><p>Selected as a student researcher.</p></article>
    <article><span>2022</span><h3>IEEE Signal Processing Cup</h3><p>First runner-up worldwide; the project poster also received a Purdue Graduate Showcase award.</p></article>
    <article><span>2022</span><h3>Academic excellence</h3><p>Received IIT Hyderabad’s Academic Excellence Award and graduated with Honors in Electrical Engineering.</p></article>
  </div>
</section>

<section class="work-section" aria-labelledby="ip-title">
  <div class="placeholder-note">
    <h2 id="ip-title">Patent disclosure in progress</h2>
    <p>Details will be added after the filing status is ready to share publicly.</p>
  </div>
</section>
