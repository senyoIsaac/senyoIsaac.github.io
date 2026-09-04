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
  background: #f3f5f4;
  color: #1d2730;
}

.page__content h1,
.page__content h2,
.page__content h3,
.page__content h4,
.page__content .brand,
.page__content .stat-value,
.page__content .eyebrow {
  font-family: 'Space Grotesk', sans-serif;
}

.page__content p,
.page__content li,
.page__content a,
.page__content .btn,
.page__content .nav-link {
  font-family: 'Inter', sans-serif;
}

.engi-shell {
  max-width: 1680px;
  margin: 0 auto;
  padding: 0 28px 48px;
}

.topbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  min-height: 78px;
  border-bottom: 1px solid rgba(17, 24, 39, 0.08);
  padding: 10px 0 12px;
}

.brand {
  font-size: 1.15rem;
  font-weight: 700;
  letter-spacing: 0.18em;
  color: #111827;
}

.nav {
  display: flex;
  align-items: center;
  gap: 28px;
  flex-wrap: wrap;
}

.nav-link {
  color: #3d4a57;
  text-decoration: none;
  font-size: 0.92rem;
}

.nav-link:hover {
  text-decoration: none;
  color: #111827;
}

.layout {
  display: grid;
  grid-template-columns: 300px minmax(0, 1fr);
  gap: 0;
  min-height: calc(100vh - 100px);
}

.sidebar {
  border-right: 1px solid rgba(17, 24, 39, 0.08);
  padding: 28px 24px 0 0;
}

.profile-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding-top: 10px;
}

.profile-avatar {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  overflow: hidden;
  border: 1px solid rgba(17, 24, 39, 0.08);
  box-shadow: 0 10px 24px rgba(17, 24, 39, 0.08);
  margin-bottom: 18px;
}

.profile-avatar img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.profile-name {
  margin: 0 0 8px;
  font-size: 1.18rem;
  color: #111827;
}

.profile-role {
  margin: 0;
  font-size: 0.9rem;
  line-height: 1.7;
  color: #4d5c6d;
}

.profile-meta {
  width: 100%;
  margin: 22px 0 0;
  padding: 0;
  list-style: none;
  text-align: left;
}

.profile-meta li {
  position: relative;
  padding-left: 18px;
  margin: 12px 0;
  color: #344251;
  font-size: 0.92rem;
}

.profile-meta li::before {
  content: "•";
  position: absolute;
  left: 0;
  top: 0;
  color: #111827;
}

.main-panel {
  padding: 26px 28px 0 42px;
}

.hero-copy {
  max-width: 980px;
  padding-top: 18px;
}

.eyebrow {
  display: inline-block;
  width: 52px;
  height: 10px;
  border-radius: 999px;
  background: linear-gradient(90deg, #111827, #596b7d);
  margin-bottom: 20px;
}

.hero-copy h1 {
  margin: 0;
  font-size: clamp(3.1rem, 5vw, 7rem);
  line-height: 0.88;
  letter-spacing: -0.07em;
  color: #111827;
}

.hero-copy .lead {
  margin-top: 24px;
  max-width: 700px;
  color: #36455c;
  font-size: 1.08rem;
  line-height: 1.8;
}

.cta-row {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-top: 28px;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 160px;
  padding: 14px 18px;
  border-radius: 12px;
  font-weight: 700;
  text-decoration: none;
  transition: transform 0.18s ease;
}

.btn:hover {
  text-decoration: none;
  transform: translateY(-1px);
}

.btn-primary {
  background: linear-gradient(135deg, #8fe3ff, #8de7c0);
  color: #111827;
}

.btn-secondary {
  border: 1px solid rgba(17, 24, 39, 0.08);
  background: rgba(255, 255, 255, 0.5);
  color: #111827;
}

.stats {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
  margin-top: 34px;
  max-width: 880px;
}

.stat {
  background: #121a24;
  color: #fff;
  border-radius: 18px;
  padding: 18px 18px 20px;
}

.stat-value {
  display: block;
  font-size: 2.2rem;
  line-height: 1;
  color: #ffffff;
  margin-bottom: 8px;
}

.stat-label {
  color: rgba(255, 255, 255, 0.8);
  font-size: 0.82rem;
}

@media (max-width: 900px) {
  .layout {
    grid-template-columns: 1fr;
  }

  .sidebar {
    border-right: none;
    border-bottom: 1px solid rgba(17, 24, 39, 0.08);
    padding-right: 0;
    padding-bottom: 18px;
  }

  .main-panel {
    padding-left: 0;
  }

  .stats {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 600px) {
  .engi-shell {
    padding-left: 16px;
    padding-right: 16px;
  }

  .topbar {
    flex-direction: column;
    align-items: flex-start;
    gap: 12px;
    padding-top: 18px;
  }

  .nav {
    gap: 12px 18px;
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
        <p class="profile-role">Assistant Bridge Engineer<br />CPLEX Engineering Division, Ghana</p>

        <ul class="profile-meta">
          <li>Asuofia, Kumasi</li>
          <li>CPLEX Company Limited</li>
          <li>isaacsenyoh9@gmail.com</li>
          <li>github.com/senyoIsaac</li>
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
          resilient infrastructure, data-driven design, and technology-enabled decision-making for safer and
          more sustainable systems.
        </p>

        <div class="cta-row">
          <a class="btn btn-primary" href="https://senyoIsaac.github.io/files/Isaac_Senyoh_CV.pdf" target="_blank" rel="noopener">View CV</a>
          <a class="btn btn-secondary" href="#research">Explore research</a>
        </div>

        <div class="stats">
          <div class="stat">
            <span class="stat-value">4+</span>
            <span class="stat-label">Core research areas</span>
          </div>
          <div class="stat">
            <span class="stat-value">AI</span>
            <span class="stat-label">Infrastructure intelligence</span>
          </div>
          <div class="stat">
            <span class="stat-value">Sustainability</span>
            <span class="stat-label">Engineering practice</span>
          </div>
        </div>
      </section>
    </main>
  </div>
</div>

---