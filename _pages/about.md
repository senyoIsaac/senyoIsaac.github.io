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
    radial-gradient(circle at top left, rgba(143, 227, 255, 0.22), transparent 22%),
    linear-gradient(180deg, #f5f7f8 0%, #eef2f5 100%);
  color: #1b2430;
}

.page__content h1,
.page__content h2,
.page__content h3,
.page__content h4,
.page__content .brand,
.page__content .stat-value,
.page__content .tag {
  font-family: 'Space Grotesk', sans-serif;
}

.page__content p,
.page__content li,
.page__content td,
.page__content th,
.page__content a,
.page__content .btn,
.page__content .nav-link {
  font-family: 'Inter', sans-serif;
}

.engi-shell {
  max-width: 1560px;
  margin: 0 auto;
  padding: 0 28px 48px;
}

.topbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 84px;
  border-bottom: 1px solid rgba(15, 23, 42, 0.08);
  margin-bottom: 6px;
  padding-top: 4px;
}

.brand {
  font-size: 1.2rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  color: #141d27;
}

.nav {
  display: flex;
  align-items: center;
  gap: 30px;
  flex-wrap: wrap;
}

.nav-link {
  color: #374253;
  font-size: 0.96rem;
  text-decoration: none;
  opacity: 0.8;
}

.nav-link:hover {
  text-decoration: none;
  opacity: 1;
}

.layout {
  display: grid;
  grid-template-columns: 280px minmax(0, 1.2fr) 280px;
  gap: 0;
  min-height: calc(100vh - 90px);
}

.sidebar,
.main-panel,
.focus-panel {
  min-height: 100%;
}

.sidebar {
  padding: 28px 26px 24px 0;
  border-right: 1px solid rgba(15, 23, 42, 0.08);
}

.profile-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding-top: 10px;
}

.profile-avatar {
  width: 152px;
  height: 152px;
  border-radius: 50%;
  overflow: hidden;
  border: 3px solid rgba(15, 23, 42, 0.08);
  box-shadow: 0 10px 22px rgba(15, 23, 42, 0.08);
  margin-bottom: 18px;
}

.profile-avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.profile-name {
  margin: 0 0 8px;
  font-size: 1.05rem;
  color: #1d2b35;
}

.profile-role {
  margin: 0;
  color: #606f7d;
  line-height: 1.6;
  font-size: 0.9rem;
}

.profile-meta {
  list-style: none;
  padding: 0;
  margin: 18px 0 0;
  width: 100%;
  text-align: left;
}

.profile-meta li {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 10px 0;
  color: #32404d;
  font-size: 0.92rem;
}

.profile-meta li::before {
  content: "•";
  color: #2f495d;
  font-size: 1.1rem;
  line-height: 1;
}

.main-panel {
  padding: 24px 42px 0 42px;
  border-right: 1px solid rgba(15, 23, 42, 0.08);
}

.micro-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 14px;
  margin-top: 30px;
}

.micro-card {
  background: #fff;
  border: 1px solid rgba(17, 24, 39, 0.06);
  border-radius: 16px;
  padding: 16px 14px;
}

.micro-card span {
  display: block;
  font-size: 0.72rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #5d6d7d;
}

.micro-card strong {
  display: block;
  margin-top: 8px;
  color: #151d29;
  font-size: 1.1rem;
}

.hero-copy {
  padding-top: 12px;
}

.hero-copy .eyebrow {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 42px;
  height: 12px;
  border-radius: 999px;
  background: linear-gradient(90deg, #111827, #4a5a6b);
  margin-bottom: 22px;
  position: relative;
  vertical-align: middle;
}

.hero-copy h1 {
  margin: 0;
  font-size: clamp(3.3rem, 5vw, 7rem);
  line-height: 0.9;
  letter-spacing: -0.065em;
  color: #111827;
}

.hero-copy .lead {
  margin-top: 22px;
  max-width: 660px;
  color: #333d49;
  font-size: 1.05rem;
  line-height: 1.75;
}

.cta-row {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-top: 26px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 150px;
  padding: 14px 20px;
  border-radius: 12px;
  font-weight: 700;
  text-decoration: none;
  transition: all 0.18s ease;
}

.btn:hover {
  text-decoration: none;
  transform: translateY(-1px);
}

.btn-primary {
  background: linear-gradient(135deg, #8fe3ff, #8de7c0);
  color: #11222d;
}

.btn-secondary {
  border: 1px solid rgba(15, 23, 42, 0.08);
  background: rgba(255, 255, 255, 0.4);
  color: #1b2430;
}

.stat-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
  margin-top: 28px;
}

.stat-item {
  background: rgba(17, 24, 39, 0.9);
  color: #ffffff;
  border-radius: 18px;
  padding: 18px 18px 22px;
  min-height: 116px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.stat-value {
  font-size: 2.3rem;
  line-height: 1;
  color: #ffffff;
  margin-bottom: 8px;
}

.stat-item span:last-child {
  color: rgba(255,255,255,0.8);
  font-size: 0.82rem;
}

.focus-panel {
  padding: 24px 0 0 28px;
}

.focus-card {
  margin-top: 120px;
  background: linear-gradient(180deg, rgba(17,24,39,0.95), rgba(27,39,52,0.94));
  border-radius: 26px;
  padding: 26px 22px 22px;
  color: #eaf5ff;
  box-shadow: 0 18px 36px rgba(17, 24, 39, 0.12);
  border: 1px solid rgba(143, 227, 255, 0.18);
}

.focus-card strong {
  display: block;
  margin-bottom: 18px;
  color: #cfeaff;
  font-size: 0.92rem;
  letter-spacing: 0.02em;
}

.focus-card h3 {
  margin: 0;
  font-size: clamp(1.4rem, 1.6vw, 2.2rem);
  line-height: 1.2;
  color: #ebf7ff;
}

.focus-card ul {
  list-style: none;
  padding: 0;
  margin: 18px 0 0;
}

.focus-card li {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 10px 0;
  color: #d7ebf9;
  font-size: 0.92rem;
}

.focus-card li::before {
  content: "";
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: linear-gradient(135deg, #8fe3ff, #8de7c0);
  box-shadow: 0 0 0 4px rgba(143, 227, 255, 0.12);
}

@media (max-width: 1024px) {
  .layout {
    grid-template-columns: 1fr;
  }

  .sidebar,
  .main-panel,
  .focus-panel {
    border: none;
    padding-left: 0;
    padding-right: 0;
  }

  .focus-card {
    margin-top: 20px;
  }
}

@media (max-width: 680px) {
  .engi-shell {
    padding-left: 16px;
    padding-right: 16px;
  }

  .topbar {
    flex-direction: column;
    justify-content: center;
    height: auto;
    align-items: flex-start;
    padding: 20px 0;
    gap: 12px;
  }

  .nav {
    gap: 14px 20px;
  }

  .stat-grid {
    grid-template-columns: 1fr;
  }

  .layout {
    display: block;
  }

  .main-panel {
    padding: 18px 0 0;
  }
}
</style>

<div class="engi-shell">
  <header class="topbar">
    <div class="brand">SENYOH</div>
    <nav class="nav" aria-label="Main navigation">
      <a class="nav-link" href="#">Publications</a>
      <a class="nav-link" href="#">CV</a>
      <a class="nav-link" href="#">GitHub</a>
      <a class="nav-link" href="#">Engineering Works</a>
      <a class="nav-link" href="#">Blog Posts</a>
    </nav>
  </header>

  <div class="layout">
    <aside class="sidebar">
      <div class="profile-card">
        <div class="profile-avatar">
          <img src="https://senyoIsaac.github.io/images/headshot.jpg" alt="Isaac Senyoh" />
        </div>

        <h2 class="profile-name">Isaac Senyoh</h2>
        <p class="profile-role">Assistant Bridge Engineer, CPLEX<br />Engineering Division, GH</p>

        <ul class="profile-meta">
          <li>Asuofia, Kumasi, Ghana</li>
          <li>CPLEX Company Limited</li>
          <li>Email</li>
          <li>GitHub</li>
          <li>LinkedIn</li>
        </ul>
      </div>
    </aside>

    <main class="main-panel">
      <section class="hero-copy">
        <div class="eyebrow" aria-hidden="true"></div>
        <h1>infrastructure<br />for a smarter<br />future.</h1>

        <p class="lead">
          I am Isaac Senyoh, a graduate civil engineer working at the intersection of structural engineering,
          computational modeling, machine learning, and intelligent monitoring systems. My work focuses on
          creating safer, more adaptive, and more sustainable infrastructure through data-driven design and
          advanced sensing technologies.
        </p>

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

        <div class="micro-grid">
          <div class="micro-card">
            <span>Current</span>
            <strong>Bridge engineering</strong>
          </div>
          <div class="micro-card">
            <span>Method</span>
            <strong>AI + sensing</strong>
          </div>
          <div class="micro-card">
            <span>Goal</span>
            <strong>Resilient systems</strong>
          </div>
        </div>
      </section>
    </main>

    <aside class="focus-panel">
      <div class="focus-card">
        <strong>Focus</strong>
        <h3>Structural health monitoring, digital twins, and AI-driven resilience.</h3>
        <ul>
          <li>Damage identification</li>
          <li>Predictive maintenance</li>
          <li>Decision-support systems</li>
        </ul>
      </div>
    </aside>
  </div>
</div>

---