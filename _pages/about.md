---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
social_image: "https://senyoIsaac.github.io/images/headshot.jpg"
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&family=Space+Grotesk:wght@500;700&display=swap');

.page__content {
  background:
    radial-gradient(circle at top left, rgba(101, 214, 255, 0.18), transparent 30%),
    radial-gradient(circle at bottom right, rgba(255, 180, 84, 0.12), transparent 25%),
    linear-gradient(180deg, #07161c 0%, #0d1d27 32%, #0b1720 100%);
  color: #e9f5ff;
}

.page__content h1,
.page__content h2,
.page__content h3,
.page__content h4,
.page__content .eyebrow,
.page__content .stat-value,
.page__content .chip {
  font-family: 'Space Grotesk', sans-serif;
}

.page__content p,
.page__content li,
.page__content td,
.page__content th,
.page__content a,
.page__content .btn,
.page__content .label {
  font-family: 'Inter', sans-serif;
}

.engi-shell {
  max-width: 1200px;
  margin: 0 auto;
  padding: 24px 0 48px;
}

.hero-panel {
  display: grid;
  grid-template-columns: 1.35fr 0.85fr;
  gap: 28px;
  align-items: stretch;
  margin: 14px 0 36px;
}

.hero-copy,
.hero-visual,
.card,
.feature-card,
.edu-card,
.contact-card {
  background: rgba(15, 29, 39, 0.8);
  border: 1px solid rgba(168, 203, 224, 0.12);
  border-radius: 24px;
  box-shadow: 0 20px 50px rgba(4, 11, 18, 0.35);
  backdrop-filter: blur(8px);
}

.hero-copy {
  padding: 32px 30px 26px;
}

.eyebrow {
  display: inline-block;
  margin-bottom: 16px;
  padding: 8px 12px;
  border-radius: 999px;
  background: rgba(101, 214, 255, 0.12);
  border: 1px solid rgba(101, 214, 255, 0.28);
  color: #8fe2ff;
  font-size: 0.74rem;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.hero-copy h1 {
  margin: 0 0 16px;
  font-size: clamp(2.5rem, 4vw, 4.2rem);
  line-height: 1.02;
  letter-spacing: -0.05em;
  color: #f3f8ff;
}

.hero-copy .lead {
  margin: 0;
  max-width: 720px;
  color: #d2e8f2;
  font-size: 1.08rem;
  line-height: 1.8;
}

.cta-row {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-top: 24px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 12px 18px;
  border-radius: 12px;
  font-weight: 700;
  text-decoration: none;
  transition: all 0.2s ease;
}

.btn:hover {
  transform: translateY(-1px);
  text-decoration: none;
}

.btn-primary {
  background: linear-gradient(135deg, #65d6ff, #7af0c8);
  color: #07161c;
}

.btn-secondary {
  border: 1px solid rgba(255, 180, 84, 0.4);
  background: rgba(255, 180, 84, 0.08);
  color: #ffd69b;
}

.stat-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
  margin-top: 28px;
}

.stat-item {
  padding: 16px 14px;
  border-radius: 16px;
  background: rgba(10, 19, 26, 0.7);
  border: 1px solid rgba(168, 203, 224, 0.08);
}

.stat-value {
  display: block;
  font-size: 1.5rem;
  color: #ffffff;
  margin-bottom: 6px;
}

.stat-item span:last-child {
  color: #b7d2e3;
  font-size: 0.84rem;
}

.hero-visual {
  position: relative;
  overflow: hidden;
  min-height: 100%;
}

.hero-visual img {
  display: block;
  width: 100%;
  height: 100%;
  min-height: 440px;
  object-fit: cover;
  filter: saturate(1.08) contrast(1.05);
}

.hero-badge {
  position: absolute;
  right: 18px;
  bottom: 18px;
  max-width: 240px;
  padding: 14px 16px;
  border-radius: 16px;
  background: rgba(7, 22, 28, 0.82);
  border: 1px solid rgba(101, 214, 255, 0.22);
  color: #dff3ff;
  box-shadow: 0 12px 30px rgba(4, 11, 18, 0.45);
}

.hero-badge strong {
  display: block;
  margin-bottom: 4px;
  color: #7ef1c0;
  font-size: 0.9rem;
}

.section-head {
  margin: 30px 0 18px;
  padding-top: 18px;
}

.section-head h2 {
  margin: 0;
  font-size: clamp(1.8rem, 2vw, 2.5rem);
  letter-spacing: -0.04em;
  color: #ebf6ff;
}

.card-grid,
.media-grid,
.connect-grid {
  display: grid;
  gap: 22px;
}

.card-grid {
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.card {
  overflow: hidden;
  transition: transform 0.2s ease, border-color 0.2s ease;
}

.card:hover,
.feature-card:hover,
.contact-card:hover {
  transform: translateY(-4px);
  border-color: rgba(101, 214, 255, 0.32);
}

.card img {
  display: block;
  width: 100%;
  height: 220px;
  object-fit: cover;
}

.card-body {
  padding: 22px 20px 20px;
}

.card-tag {
  display: inline-block;
  margin-bottom: 10px;
  color: #7de4ff;
  font-size: 0.72rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.card h3 {
  margin: 0 0 10px;
  font-size: 1.28rem;
  color: #f2f8ff;
  line-height: 1.35;
}

.card p {
  margin: 0;
  color: #bfd7e8;
  line-height: 1.75;
}

.feature-card {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 0;
  overflow: hidden;
  margin-top: 8px;
}

.feature-media {
  background: rgba(0,0,0,0.15);
}

.feature-media img,
.feature-media video {
  display: block;
  width: 100%;
  height: 100%;
  min-height: 320px;
  object-fit: cover;
  border-right: 1px solid rgba(168, 203, 224, 0.12);
}

.feature-copy {
  padding: 28px 26px;
}

.feature-copy h3 {
  margin: 0 0 12px;
  font-size: clamp(1.5rem, 2vw, 2.1rem);
  line-height: 1.2;
}

.feature-copy p {
  margin: 0;
  color: #cfe3ee;
  line-height: 1.8;
}

.media-grid {
  grid-template-columns: repeat(2, minmax(0, 1fr));
  margin-top: 20px;
}

.edu-contact-grid {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 22px;
  margin-top: 20px;
}

.edu-card,
.contact-card {
  padding: 26px 24px;
}

.edu-card table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 12px;
}

.edu-card th,
.edu-card td {
  padding: 12px 8px;
  border-bottom: 1px solid rgba(168, 203, 224, 0.1);
  text-align: left;
  vertical-align: top;
}

.edu-card th {
  color: #a9d4ff;
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
}

.edu-card td {
  color: #e1edf6;
}

.cv-link {
  display: inline-flex;
  margin-top: 16px;
  padding: 12px 16px;
  border-radius: 12px;
  background: rgba(122, 240, 200, 0.08);
  border: 1px solid rgba(122, 240, 200, 0.2);
  color: #93f4d2;
  text-decoration: none;
  font-weight: 700;
}

.connect-grid {
  grid-template-columns: repeat(3, minmax(0, 1fr));
  margin-top: 18px;
}

.contact-card {
  display: block;
  color: inherit;
  text-decoration: none;
  transition: all 0.2s ease;
}

.contact-card strong {
  display: block;
  margin-bottom: 4px;
  color: #f6fbff;
  font-size: 0.78rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.contact-card span {
  color: #cfe3ee;
  font-size: 1rem;
}

@media (max-width: 900px) {
  .hero-panel,
  .feature-card,
  .edu-contact-grid {
    grid-template-columns: 1fr;
  }

  .card-grid,
  .media-grid,
  .connect-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 600px) {
  .engi-shell {
    padding-left: 14px;
    padding-right: 14px;
  }

  .hero-copy,
  .edu-card,
  .contact-card {
    padding-left: 18px;
    padding-right: 18px;
  }

  .stat-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="engi-shell">

  <section class="hero-panel">
    <div class="hero-copy">
      <div class="eyebrow">Civil Engineer • AI Researcher • Innovator</div>
      <h1>Building resilient infrastructure for a smarter future.</h1>
      <p class="lead">I am Isaac Senyoh, a graduate civil engineer working at the intersection of structural engineering, computational modeling, machine learning, and intelligent monitoring systems. My work focuses on creating safer, more adaptive, and more sustainable infrastructure through data-driven design and advanced sensing technologies.</p>

      <div class="cta-row">
        <a class="btn btn-primary" href="https://senyoIsaac.github.io/files/Isaac_Senyoh_CV.pdf" target="_blank" rel="noopener">View CV</a>
        <a class="btn btn-secondary" href="#research">Explore research</a>
      </div>

      <div class="stat-grid">
        <div class="stat-item">
          <span class="stat-value">4+</span>
          <span>Core research domains</span>
        </div>
        <div class="stat-item">
          <span class="stat-value">AI</span>
          <span>for infrastructure intelligence</span>
        </div>
        <div class="stat-item">
          <span class="stat-value">Sustainability</span>
          <span>in engineering practice</span>
        </div>
      </div>
    </div>

    <div class="hero-visual">
      <img src="https://senyoIsaac.github.io/images/headshot.jpg" alt="Isaac Senyoh" />
      <div class="hero-badge">
        <strong>Focus</strong>
        Structural health monitoring, digital twins, resilient systems, and AI-enabled infrastructure decision support.
      </div>
    </div>
  </section>

  <div class="section-head" id="research">
    <h2>Research interests</h2>
  </div>

  <div class="card-grid">
    <div class="card">
      <img src="https://senyoIsaac.github.io/images/about/resiliency.jpg" alt="Natural Hazards and Civil Infrastructure Resiliency" />
      <div class="card-body">
        <span class="card-tag">01</span>
        <h3>Natural Hazards &amp; Infrastructure Resiliency</h3>
        <p>My work explores how emerging AI methods can help civil infrastructure systems learn from failure, predict risk, and become more resilient under extreme environmental and operational stress.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://senyoIsaac.github.io/images/about/digital-twin.jpg" alt="Digital Twin Systems in Civil Engineering" />
      <div class="card-body">
        <span class="card-tag">02</span>
        <h3>Digital Twin Systems</h3>
        <p>I am interested in building data-rich digital replicas of physical assets that integrate real-time sensor data, degradation tracking, and predictive maintenance for smarter management of infrastructure.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://senyoIsaac.github.io/images/about/crack.jpg" alt="Computer Vision for Structural Health Monitoring" />
      <div class="card-body">
        <span class="card-tag">03</span>
        <h3>Computer Vision in SHM</h3>
        <p>Through video processing and image-based techniques, I investigate non-contact methods for measuring strain, displacement, and damage evolution in structures where conventional sensors are limited or impractical.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://senyoIsaac.github.io/images/about/carbon-reduction.jpg" alt="Carbon Reduction and Circular Construction" />
      <div class="card-body">
        <span class="card-tag">04</span>
        <h3>Carbon Reduction &amp; Circular Construction</h3>
        <p>I also explore circular economy principles that support the reuse and safe reintegration of structural components, reducing waste while improving resource efficiency in the built environment.</p>
      </div>
    </div>
  </div>

  <div class="section-head">
    <h2>Current academic work</h2>
  </div>

  <div class="feature-card">
    <div class="feature-media">
      <video src="https://senyoIsaac.github.io/videos/crack.mp4" controls alt="Surface morphology reconstruction of heavily corroded steel"></video>
    </div>
    <div class="feature-copy">
      <span class="card-tag">Research highlight</span>
      <h3>Deep-learning surface morphology reconstruction of heavily corroded steel</h3>
      <p>Surface morphology reconstruction of heavily corroded specimens to enable improved structural assessment, damage interpretation, and data-driven decision making in steel condition evaluation.</p>
    </div>
  </div>

  <div class="section-head">
    <h2>Applied engineering and monitoring</h2>
  </div>

  <div class="feature-card">
    <div class="feature-media">
      <video src="https://senyoIsaac.github.io/videos/sensor.mp4" controls alt="Arduino-based real-time telemetry"></video>
    </div>
    <div class="feature-copy">
      <span class="card-tag">Systems</span>
      <h3>Arduino-based real-time telemetry</h3>
      <p>Exploring the fundamentals of Arduino programming in C++ and signal processing with Python to build practical monitoring tools for data acquisition, sensor analysis, and structural diagnostics.</p>
    </div>
  </div>

  <div class="section-head">
    <h2>Undergraduate research</h2>
  </div>

  <div class="media-grid">
    <div class="card">
      <img src="https://senyoIsaac.github.io/images/about/Bayesian.png" alt="Concrete fck and Bayesian network" />
      <div class="card-body">
        <span class="card-tag">Structural engineering</span>
        <h3>Concrete fck &amp; Bayesian Network</h3>
        <p>Evaluation and performance modelling of concrete compressive strength using Bayesian networks, with a case study in Ghana.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://senyoIsaac.github.io/images/about/asphalt.jpg" alt="Predictive models and evaluation" />
      <div class="card-body">
        <span class="card-tag">Transportation engineering</span>
        <h3>Predictive models &amp; evaluation</h3>
        <p>Asphalt pavement temperature local model evaluation, a study relevant to bridge engineering and transportation infrastructure performance.</p>
      </div>
    </div>
  </div>

  <div class="section-head">
    <h2>Education &amp; connection</h2>
  </div>

  <div class="edu-contact-grid">
    <div class="edu-card">
      <h3>Education</h3>
      <table>
        <thead>
          <tr>
            <th>Degree</th>
            <th>Institution</th>
            <th>Location</th>
            <th>Year</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>B.Sc. in Civil Engineering</td>
            <td>Kwame Nkrumah University of Science and Technology (KNUST)</td>
            <td>Kumasi, Ghana</td>
            <td>2024</td>
          </tr>
        </tbody>
      </table>
      <a class="cv-link" href="https://senyoIsaac.github.io/files/Isaac_Senyoh_CV.pdf" target="_blank" rel="noopener">Download full CV</a>
    </div>

    <div class="contact-card">
      <h3>Connect</h3>
      <div class="connect-grid">
        <a class="contact-card" href="https://github.com/senyoIsaac" target="_blank" rel="noopener">
          <strong>GitHub</strong>
          <span>github.com/senyoIsaac</span>
        </a>
        <a class="contact-card" href="https://www.linkedin.com/in/isaac-senyoh-4247a9220/" target="_blank" rel="noopener">
          <strong>LinkedIn</strong>
          <span>linkedin.com/in/isaac-senyoh</span>
        </a>
        <a class="contact-card" href="mailto:isaacsenyoh9@gmail.com">
          <strong>Email</strong>
          <span>isaacsenyoh9@gmail.com</span>
        </a>
      </div>
    </div>
  </div>

</div>

---