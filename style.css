:root {
  --bg: #09111f;
  --bg-soft: #111c2d;
  --panel: #12213a;
  --panel-2: #132944;
  --primary: #4cc9f0;
  --primary-2: #7b61ff;
  --accent: #7ef7d6;
  --text: #eaf2ff;
  --muted: #a9b9d1;
  --line: rgba(255, 255, 255, 0.08);
  --shadow: 0 20px 60px rgba(10, 17, 32, 0.45);
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: "Cairo", sans-serif;
  background: linear-gradient(180deg, #08111d 0%, #0d1830 100%);
  color: var(--text);
  line-height: 1.7;
}

a {
  color: inherit;
  text-decoration: none;
}

img {
  max-width: 100%;
  display: block;
}

.container {
  width: min(1120px, calc(100% - 32px));
  margin: 0 auto;
}

.section {
  padding: 100px 0;
}

.alt {
  background: rgba(255, 255, 255, 0.02);
}

.eyebrow {
  display: inline-block;
  font-size: 0.78rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 14px;
  font-weight: 700;
}

h1,
h2,
h3,
p {
  margin: 0;
}

h1 {
  font-size: clamp(2.5rem, 5vw, 4.5rem);
  line-height: 1.2;
  margin-bottom: 18px;
}

h2 {
  font-size: clamp(2rem, 3vw, 3rem);
  line-height: 1.3;
  margin-bottom: 18px;
}

p {
  color: var(--muted);
  font-size: 1.05rem;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 52px;
  padding: 0 24px;
  border-radius: 14px;
  font-weight: 700;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.btn:hover {
  transform: translateY(-2px);
}

.btn-primary {
  background: linear-gradient(135deg, var(--primary), var(--primary-2));
  box-shadow: 0 16px 30px rgba(92, 112, 255, 0.35);
  color: white;
}

.btn-secondary {
  border: 1px solid var(--line);
  background: rgba(255, 255, 255, 0.02);
  color: var(--text);
}

.header {
  position: sticky;
  top: 0;
  z-index: 50;
  backdrop-filter: blur(16px);
  background: rgba(9, 17, 31, 0.7);
  border-bottom: 1px solid var(--line);
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  min-height: 88px;
  gap: 20px;
}

.brand {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-size: 1.35rem;
  font-weight: 800;
}

.brand-mark {
  display: inline-grid;
  place-items: center;
  width: 38px;
  height: 38px;
  border-radius: 12px;
  background: linear-gradient(135deg, var(--primary), var(--primary-2));
  color: white;
  box-shadow: var(--shadow);
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 28px;
  color: var(--muted);
  font-weight: 600;
}

.nav-links a {
  transition: color 0.2s ease;
}

.nav-links a:hover {
  color: var(--text);
}

.menu-toggle {
  display: none;
  background: transparent;
  border: none;
  width: 42px;
  height: 42px;
  cursor: pointer;
  padding: 0;
}

.menu-toggle span {
  display: block;
  width: 100%;
  height: 3px;
  border-radius: 999px;
  background: white;
  margin: 7px 0;
}

.hero {
  padding: 84px 0 64px;
}

.hero-content {
  display: grid;
  grid-template-columns: 1.1fr 0.9fr;
  align-items: center;
  gap: 46px;
}

.hero-text {
  max-width: 620px;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 18px;
  margin: 32px 0 26px;
}

.hero-points {
  display: flex;
  flex-wrap: wrap;
  gap: 12px 24px;
  list-style: none;
  color: var(--muted);
  font-weight: 600;
}

.hero-points li::before {
  content: "✓";
  color: var(--accent);
  margin-left: 8px;
}

.hero-visual {
  position: relative;
  min-height: 470px;
  display: grid;
  place-items: center;
}

.dashboard-card {
  position: relative;
  width: min(100%, 480px);
  background: linear-gradient(180deg, rgba(18, 33, 58, 0.9), rgba(11, 22, 39, 0.85));
  border: 1px solid var(--line);
  border-radius: 28px;
  box-shadow: var(--shadow);
  overflow: hidden;
}

.main-card {
  padding: 18px 22px 28px;
  transform: rotate(-6deg);
}

.card-top {
  display: flex;
  gap: 8px;
  padding-bottom: 20px;
}

.dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  display: block;
}

.dot.red { background: #ff6b6b; }
.dot.yellow { background: #ffd166; }
.dot.green { background: #68d391; }

.chart-box {
  height: 220px;
  display: flex;
  align-items: end;
  justify-content: center;
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.02), rgba(255, 255, 255, 0.01));
  border: 1px solid rgba(255, 255, 255, 0.06);
  border-radius: 18px;
  padding: 20px;
}

.chart-bars {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: end;
  gap: 14px;
}

.chart-bars span {
  flex: 1;
  background: linear-gradient(180deg, var(--primary), var(--primary-2));
  border-radius: 14px 14px 0 0;
  display: block;
}

.floating-badge {
  position: absolute;
  background: rgba(8, 17, 29, 0.9);
  border: 1px solid var(--line);
  border-radius: 18px;
  box-shadow: var(--shadow);
  padding: 16px 18px;
  display: flex;
  flex-direction: column;
  min-width: 150px;
}

.badge-one {
  right: 10px;
  top: 40px;
}

.badge-two {
  left: 5px;
  bottom: 30px;
}

.floating-badge strong {
  font-size: 1.3rem;
  color: var(--text);
}

.floating-badge span {
  color: var(--muted);
  font-size: 0.9rem;
}

.stats {
  padding: 20px 0 0;
}

.stat-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 18px;
}

.stat-item {
  background: rgba(255, 255, 255, 0.02);
  border: 1px solid var(--line);
  border-radius: 18px;
  padding: 28px 20px;
  text-align: center;
}

.stat-item strong {
  display: block;
  font-size: clamp(1.9rem, 2vw, 2.8rem);
  margin-bottom: 8px;
}

.stat-item span {
  color: var(--muted);
}

.two-col {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 36px;
  align-items: center;
}

.about-panel {
  display: grid;
  gap: 18px;
}

.panel-box {
  display: flex;
  align-items: center;
  gap: 18px;
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid var(--line);
  border-radius: 20px;
  padding: 18px 20px;
}

.mini-icon {
  width: 58px;
  height: 58px;
  display: grid;
  place-items: center;
  border-radius: 16px;
  font-size: 1.6rem;
  background: linear-gradient(135deg, rgba(76, 201, 240, 0.12), rgba(123, 97, 255, 0.2));
}

.panel-box h3 {
  margin-bottom: 4px;
  font-size: 1.2rem;
}

.section-heading {
  margin-bottom: 36px;
  text-align: center;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 22px;
}

.service-card {
  background: rgba(255, 255, 255, 0.02);
  border: 1px solid var(--line);
  border-radius: 24px;
  padding: 30px 22px;
  box-shadow: var(--shadow);
}

.service-card .icon {
  font-size: 2rem;
  margin-bottom: 18px;
}

.service-card h3 {
  margin-bottom: 12px;
  font-size: 1.35rem;
}

.feature-list {
  display: grid;
  gap: 18px;
}

.feature-item {
  display: flex;
  gap: 22px;
  align-items: flex-start;
  padding: 22px 24px;
  background: rgba(255, 255, 255, 0.02);
  border: 1px solid var(--line);
  border-radius: 22px;
}

.feature-item span {
  display: inline-grid;
  place-items: center;
  width: 54px;
  height: 54px;
  border-radius: 14px;
  font-weight: 800;
  background: linear-gradient(135deg, rgba(76, 201, 240, 0.15), rgba(123, 97, 255, 0.22));
  color: var(--text);
}

.feature-item h3 {
  margin-bottom: 6px;
}

.testimonial-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 22px;
}

.testimonial {
  background: rgba(255, 255, 255, 0.02);
  border: 1px solid var(--line);
  border-radius: 20px;
  padding: 28px;
  color: var(--text);
  font-size: 1.05rem;
}

.testimonial footer {
  margin-top: 18px;
  color: var(--muted);
  font-weight: 700;
}

.cta {
  padding: 0 0 100px;
}

.cta-box {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
  background: linear-gradient(135deg, rgba(76, 201, 240, 0.12), rgba(123, 97, 255, 0.15));
  border: 1px solid var(--line);
  border-radius: 28px;
  padding: 30px 36px;
}

.footer {
  border-top: 1px solid var(--line);
  background: rgba(10, 18, 31, 0.9);
}

.footer-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 82px;
  gap: 18px;
  flex-wrap: wrap;
}

.socials {
  display: flex;
  gap: 18px;
  color: var(--muted);
}

@media (max-width: 980px) {
  .nav-links {
    position: absolute;
    top: 88px;
    left: 16px;
    right: 16px;
    display: none;
    flex-direction: column;
    background: rgba(9, 17, 31, 0.96);
    border: 1px solid var(--line);
    border-radius: 18px;
    padding: 18px 16px;
  }

  .nav-links.open {
    display: flex;
  }

  .menu-toggle {
    display: block;
  }

  .hero-content,
  .two-col,
  .card-grid,
  .stat-grid,
  .testimonial-grid {
    grid-template-columns: 1fr;
  }

  .card-grid {
    display: grid;
  }

  .cta-box {
    flex-direction: column;
    text-align: center;
  }
}

@media (max-width: 600px) {
  .btn {
    width: 100%;
  }

  .hero-actions {
    flex-direction: column;
  }

  .hero {
    padding-top: 56px;
  }

  .service-card,
  .testimonial,
  .feature-item,
  .panel-box {
    padding: 20px 18px;
  }

  .nav {
    min-height: 76px;
  }
}
