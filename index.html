<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Khaled & Alaa — Wedding Invitation</title>
<meta name="description" content="You are cordially invited." />
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Cinzel:wght@400;500&family=Lato:wght@300;400&display=swap" rel="stylesheet" />
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --navy: #0d1f3c;
    --deep: #06122a;
    --blue: #1a3a6b;
    --mid-blue: #2a5298;
    --sky: #4a7fd4;
    --pale: #d6e4f7;
    --white: #f8faff;
    --gold: #c9a84c;
    --gold-light: #e6c97a;
    --cream: #f0e8d8;
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--deep);
    color: var(--white);
    font-family: 'Lato', sans-serif;
    font-weight: 300;
    overflow-x: hidden;
  }

  /* ── ENVELOPE SCREEN ── */
  #envelope-screen {
    position: fixed;
    inset: 0;
    background: var(--deep);
    z-index: 1000;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    transition: opacity 0.8s ease, transform 0.8s ease;
  }

  #envelope-screen.opened {
    opacity: 0;
    pointer-events: none;
  }

  .env-hint {
    font-family: 'Lato', sans-serif;
    font-weight: 300;
    font-size: 12px;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    color: var(--pale);
    opacity: 0.6;
    margin-bottom: 2.5rem;
    animation: pulse 2.5s ease-in-out infinite;
  }

  @keyframes pulse {
    0%, 100% { opacity: 0.4; }
    50% { opacity: 0.9; }
  }

  .envelope-wrap {
    position: relative;
    width: 320px;
    height: 220px;
    filter: drop-shadow(0 20px 60px rgba(74,127,212,0.25));
    transition: transform 0.3s ease;
  }

  #envelope-screen:hover .envelope-wrap { transform: scale(1.03); }

  .envelope-body {
    position: absolute;
    inset: 0;
    background: linear-gradient(160deg, #1a3a6b 0%, #0d1f3c 60%, #06122a 100%);
    border-radius: 4px;
    border: 1px solid rgba(201,168,76,0.35);
    overflow: hidden;
  }

  .envelope-flap {
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 0;
    border-left: 160px solid transparent;
    border-right: 160px solid transparent;
    border-top: 110px solid #0d1f3c;
    filter: drop-shadow(0 4px 8px rgba(0,0,0,0.3));
    transform-origin: top center;
    transition: transform 0.7s cubic-bezier(0.4,0,0.2,1);
  }

  #envelope-screen.flap-open .envelope-flap {
    transform: rotateX(180deg);
  }

  .envelope-bottom {
    position: absolute;
    bottom: 0; left: 0; right: 0;
    height: 0;
    border-left: 160px solid transparent;
    border-right: 160px solid transparent;
    border-bottom: 90px solid #0b1a35;
  }

  .envelope-left {
    position: absolute;
    left: 0; top: 0; bottom: 0;
    width: 0;
    border-top: 110px solid transparent;
    border-bottom: 110px solid transparent;
    border-left: 90px solid #0e2244;
  }

  .envelope-right {
    position: absolute;
    right: 0; top: 0; bottom: 0;
    width: 0;
    border-top: 110px solid transparent;
    border-bottom: 110px solid transparent;
    border-right: 90px solid #0e2244;
  }

  .envelope-seal {
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    width: 52px;
    height: 52px;
    background: var(--navy);
    border: 1.5px solid var(--gold);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 2;
  }

  .seal-monogram {
    font-family: 'Cinzel', serif;
    font-size: 15px;
    color: var(--gold);
    letter-spacing: 0.05em;
  }

  .env-names {
    margin-top: 2.5rem;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: 26px;
    font-weight: 300;
    color: var(--pale);
    letter-spacing: 0.05em;
    opacity: 0;
    animation: fadeUp 1.2s 0.5s forwards;
  }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(14px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  /* ── STAR FIELD ── */
  #stars {
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 0;
    overflow: hidden;
  }

  .star {
    position: absolute;
    border-radius: 50%;
    background: #fff;
    animation: twinkle var(--d) ease-in-out infinite;
  }

  @keyframes twinkle {
    0%, 100% { opacity: var(--lo); }
    50%       { opacity: var(--hi); }
  }

  /* ── MAIN CONTENT ── */
  #main {
    position: relative;
    z-index: 1;
    opacity: 0;
    transition: opacity 1s ease 0.3s;
  }

  #main.visible { opacity: 1; }

  /* ── HERO ── */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 4rem 2rem;
    position: relative;
    overflow: hidden;
  }

  .hero::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 80% 60% at 50% 40%, rgba(42,82,152,0.18) 0%, transparent 70%);
    pointer-events: none;
  }

  .hero-ornament {
    width: 160px;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
    margin: 0 auto 2rem;
  }

  .hero-pre {
    font-family: 'Lato', sans-serif;
    font-weight: 300;
    font-size: 11px;
    letter-spacing: 0.45em;
    text-transform: uppercase;
    color: var(--gold-light);
    margin-bottom: 1.8rem;
    opacity: 0;
    animation: fadeUp 1s 0.2s forwards;
  }

  .hero-names {
    font-family: 'Cormorant Garamond', serif;
    font-weight: 300;
    font-size: clamp(68px, 12vw, 120px);
    line-height: 1;
    letter-spacing: -0.01em;
    color: var(--white);
    opacity: 0;
    animation: fadeUp 1s 0.4s forwards;
  }

  .hero-names .amp {
    font-style: italic;
    color: var(--gold);
    font-size: 0.75em;
    margin: 0 0.15em;
  }

  .hero-names .name-2 {
    display: block;
    margin-top: -0.1em;
  }

  .hero-date-line {
    display: flex;
    align-items: center;
    gap: 1.5rem;
    margin: 2.5rem auto;
    opacity: 0;
    animation: fadeUp 1s 0.6s forwards;
  }

  .hero-date-line span.rule {
    width: 60px;
    height: 1px;
    background: linear-gradient(90deg, transparent, rgba(201,168,76,0.5));
  }

  .hero-date-line span.rule.rev {
    background: linear-gradient(90deg, rgba(201,168,76,0.5), transparent);
  }

  .hero-date {
    font-family: 'Cinzel', serif;
    font-size: 13px;
    letter-spacing: 0.3em;
    color: var(--pale);
  }

  .hero-sub {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: 20px;
    color: rgba(214,228,247,0.7);
    margin-bottom: 3rem;
    opacity: 0;
    animation: fadeUp 1s 0.8s forwards;
  }

  .scroll-hint {
    position: absolute;
    bottom: 2.5rem;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 8px;
    opacity: 0;
    animation: fadeUp 1s 1.5s forwards;
  }

  .scroll-hint span {
    font-size: 10px;
    letter-spacing: 0.35em;
    text-transform: uppercase;
    color: rgba(214,228,247,0.4);
  }

  .scroll-arrow {
    width: 1px;
    height: 40px;
    background: linear-gradient(to bottom, rgba(201,168,76,0.6), transparent);
    animation: scrollDown 2s ease-in-out infinite;
  }

  @keyframes scrollDown {
    0% { transform: scaleY(0); transform-origin: top; opacity: 0; }
    40% { transform: scaleY(1); opacity: 1; }
    80% { transform: scaleY(1); opacity: 0; }
    100% { transform: scaleY(0); opacity: 0; }
  }

  /* ── SECTION SHARED ── */
  section {
    max-width: 800px;
    margin: 0 auto;
    padding: 6rem 2rem;
    text-align: center;
    position: relative;
    z-index: 1;
  }

  .section-label {
    font-family: 'Lato', sans-serif;
    font-size: 10px;
    font-weight: 400;
    letter-spacing: 0.5em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1.5rem;
  }

  .section-title {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: clamp(38px, 6vw, 56px);
    font-weight: 300;
    color: var(--white);
    line-height: 1.15;
    margin-bottom: 1.5rem;
  }

  .divider {
    width: 80px;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
    margin: 0 auto 2rem;
  }

  /* ── DETAILS CARDS ── */
  .details-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1.5px;
    background: rgba(201,168,76,0.2);
    border: 1px solid rgba(201,168,76,0.2);
    border-radius: 8px;
    overflow: hidden;
    margin-top: 3rem;
  }

  .detail-card {
    background: rgba(13,31,60,0.85);
    padding: 2.5rem 1.5rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.75rem;
    backdrop-filter: blur(8px);
    transition: background 0.3s ease;
  }

  .detail-card:hover {
    background: rgba(26,58,107,0.8);
  }

  .detail-icon {
    width: 40px;
    height: 40px;
    border: 1px solid rgba(201,168,76,0.35);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 0.5rem;
  }

  .detail-icon svg {
    width: 18px;
    height: 18px;
    stroke: var(--gold);
    fill: none;
    stroke-width: 1.5;
    stroke-linecap: round;
    stroke-linejoin: round;
  }

  .detail-label {
    font-size: 10px;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--gold-light);
    opacity: 0.7;
  }

  .detail-value {
    font-family: 'Cormorant Garamond', serif;
    font-size: 22px;
    font-weight: 400;
    color: var(--white);
    line-height: 1.3;
  }

  .detail-sub {
    font-family: 'Lato', sans-serif;
    font-size: 13px;
    font-weight: 300;
    color: var(--pale);
    opacity: 0.65;
  }

  /* ── COUNTDOWN ── */
  #countdown-section {
    background: rgba(6,18,42,0.5);
    border-top: 1px solid rgba(201,168,76,0.12);
    border-bottom: 1px solid rgba(201,168,76,0.12);
  }

  .countdown-grid {
    display: flex;
    justify-content: center;
    gap: 1px;
    background: rgba(201,168,76,0.15);
    border: 1px solid rgba(201,168,76,0.15);
    border-radius: 8px;
    overflow: hidden;
    margin-top: 3rem;
    max-width: 520px;
    margin-left: auto;
    margin-right: auto;
  }

  .cd-box {
    flex: 1;
    background: rgba(10,25,55,0.9);
    padding: 2rem 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 6px;
  }

  .cd-number {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(40px, 8vw, 64px);
    font-weight: 300;
    color: var(--white);
    line-height: 1;
    min-width: 2ch;
    text-align: center;
  }

  .cd-label {
    font-size: 9px;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--gold);
    opacity: 0.75;
  }

  /* ── MAP SECTION ── */
  .map-frame {
    margin-top: 2.5rem;
    border: 1px solid rgba(201,168,76,0.25);
    border-radius: 8px;
    overflow: hidden;
    height: 340px;
  }

  .map-frame iframe {
    width: 100%;
    height: 100%;
    border: 0;
    filter: invert(90%) hue-rotate(180deg) saturate(0.7) brightness(0.85);
  }

  /* ── CLOSING ── */
  .closing {
    min-height: 60vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 6rem 2rem;
    text-align: center;
    position: relative;
    z-index: 1;
  }

  .closing-quote {
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: clamp(22px, 4vw, 34px);
    font-weight: 300;
    color: var(--pale);
    line-height: 1.7;
    max-width: 560px;
    margin: 2rem auto 3rem;
    opacity: 0.85;
  }

  .closing-names {
    font-family: 'Cinzel', serif;
    font-size: 13px;
    letter-spacing: 0.35em;
    color: var(--gold);
  }

  footer {
    text-align: center;
    padding: 2rem;
    font-size: 11px;
    letter-spacing: 0.2em;
    color: rgba(214,228,247,0.2);
    position: relative;
    z-index: 1;
  }

  /* ── SCROLL REVEAL ── */
  .reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.9s ease, transform 0.9s ease;
  }

  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* ── ORNAMENTAL CORNERS ── */
  .corner-ornament {
    position: absolute;
    width: 60px;
    height: 60px;
    opacity: 0.3;
  }

  .corner-ornament svg {
    width: 100%;
    height: 100%;
    stroke: var(--gold);
    fill: none;
    stroke-width: 1;
  }

  .corner-tl { top: 2rem; left: 2rem; }
  .corner-tr { top: 2rem; right: 2rem; transform: scaleX(-1); }
  .corner-bl { bottom: 2rem; left: 2rem; transform: scaleY(-1); }
  .corner-br { bottom: 2rem; right: 2rem; transform: scale(-1,-1); }
</style>
</head>
<body>

<!-- Stars Background -->
<div id="stars"></div>

<!-- Envelope Screen -->
<div id="envelope-screen">
  <p class="env-hint">Tap to open your invitation</p>
  <div class="envelope-wrap">
    <div class="envelope-body"></div>
    <div class="envelope-left"></div>
    <div class="envelope-right"></div>
    <div class="envelope-bottom"></div>
    <div class="envelope-flap"></div>
    <div class="envelope-seal">
      <span class="seal-monogram">K&A</span>
    </div>
  </div>
  <p class="env-names">Khaled &amp; Alaa</p>
</div>

<!-- Main Invitation -->
<div id="main">

  <!-- Hero -->
  <div class="hero">
    <div class="corner-ornament corner-tl">
      <svg viewBox="0 0 60 60"><path d="M2 2 h24 M2 2 v24 M2 2 l18 18"/><path d="M10 2 h4 M2 10 v4" stroke-width="0.5"/></svg>
    </div>
    <div class="corner-ornament corner-tr">
      <svg viewBox="0 0 60 60"><path d="M2 2 h24 M2 2 v24 M2 2 l18 18"/><path d="M10 2 h4 M2 10 v4" stroke-width="0.5"/></svg>
    </div>
    <div class="corner-ornament corner-bl">
      <svg viewBox="0 0 60 60"><path d="M2 2 h24 M2 2 v24 M2 2 l18 18"/><path d="M10 2 h4 M2 10 v4" stroke-width="0.5"/></svg>
    </div>
    <div class="corner-ornament corner-br">
      <svg viewBox="0 0 60 60"><path d="M2 2 h24 M2 2 v24 M2 2 l18 18"/><path d="M10 2 h4 M2 10 v4" stroke-width="0.5"/></svg>
    </div>

    <p class="hero-pre">Together with their families</p>
    <div class="hero-ornament"></div>
    <div class="hero-names">
      Khaled<span class="amp">&amp;</span><span class="name-2">Alaa</span>
    </div>
    <div class="hero-date-line">
      <span class="rule"></span>
      <span class="hero-date">June 26, 2026</span>
      <span class="rule rev"></span>
    </div>
    <p class="hero-sub">cordially invite you to celebrate their wedding</p>
    <div class="scroll-hint">
      <span>Scroll</span>
      <div class="scroll-arrow"></div>
    </div>
  </div>

  <!-- Details -->
  <section class="reveal">
    <p class="section-label">The Celebration</p>
    <h2 class="section-title">Wedding Details</h2>
    <div class="divider"></div>
    <div class="details-grid">
      <div class="detail-card">
        <div class="detail-icon">
          <svg viewBox="0 0 24 24"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
        </div>
        <span class="detail-label">Date</span>
        <span class="detail-value">Friday</span>
        <span class="detail-sub">June 26, 2026</span>
      </div>
      <div class="detail-card">
        <div class="detail-icon">
          <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
        </div>
        <span class="detail-label">Time</span>
        <span class="detail-value">Evening</span>
        <span class="detail-sub">Doors open at 8:00 PM</span>
      </div>
      <div class="detail-card">
        <div class="detail-icon">
          <svg viewBox="0 0 24 24"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
        </div>
        <span class="detail-label">Venue</span>
        <span class="detail-value">TAG</span>
        <span class="detail-sub">Cairo, Egypt</span>
      </div>
    </div>
  </section>

  <!-- Countdown -->
  <section id="countdown-section" style="max-width:100%; padding: 5rem 2rem;">
    <div style="max-width:800px; margin:0 auto;">
      <p class="section-label reveal">Counting down to forever</p>
      <h2 class="section-title reveal">The Big Day</h2>
      <div class="divider reveal"></div>
      <div class="countdown-grid reveal" id="countdown">
        <div class="cd-box"><span class="cd-number" id="cd-days">--</span><span class="cd-label">Days</span></div>
        <div class="cd-box"><span class="cd-number" id="cd-hours">--</span><span class="cd-label">Hours</span></div>
        <div class="cd-box"><span class="cd-number" id="cd-mins">--</span><span class="cd-label">Minutes</span></div>
        <div class="cd-box"><span class="cd-number" id="cd-secs">--</span><span class="cd-label">Seconds</span></div>
      </div>
    </div>
  </section>

  <!-- Location -->
  <section class="reveal">
    <p class="section-label">Find Us</p>
    <h2 class="section-title">The Venue</h2>
    <div class="divider"></div>
    <p style="font-family:'Cormorant Garamond',serif; font-size:20px; font-style:italic; color:var(--pale); opacity:0.8; margin-bottom:0.5rem;">TAG</p>
    <p style="font-size:14px; letter-spacing:0.2em; color:rgba(214,228,247,0.5); text-transform:uppercase; margin-bottom:0.25rem;">Cairo, Egypt</p>
    <div class="map-frame">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d110502!2d31.2357!3d30.0444!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x14583fa60b21beeb%3A0x79f1ee2a02755f35!2sCairo%2C%20Egypt!5e0!3m2!1sen!2seg!4v1700000000000!5m2!1sen!2seg"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
        title="Wedding venue location in Cairo">
      </iframe>
    </div>
  </section>

  <!-- Closing -->
  <div class="closing reveal">
    <div class="divider"></div>
    <p class="section-label">With all our love</p>
    <p class="closing-quote">
      "And of His signs is that He created for you from yourselves mates, that you may find tranquility in them; and He placed between you affection and mercy."
    </p>
    <div class="divider"></div>
    <p class="closing-names">Khaled &amp; Alaa</p>
    <p style="margin-top:0.75rem; font-size:13px; letter-spacing:0.25em; color:rgba(214,228,247,0.3); font-family:'Lato',sans-serif;">June 26, 2026 · Cairo</p>
  </div>

  <footer>© 2026 Khaled & Alaa Wedding</footer>
</div>

<script>
  // Stars
  const starsEl = document.getElementById('stars');
  for (let i = 0; i < 180; i++) {
    const s = document.createElement('div');
    s.className = 'star';
    const size = Math.random() * 2 + 0.5;
    const lo = (Math.random() * 0.15 + 0.05).toFixed(2);
    const hi = (Math.random() * 0.5 + 0.2).toFixed(2);
    const dur = (Math.random() * 4 + 2).toFixed(1) + 's';
    s.style.cssText = `
      width:${size}px; height:${size}px;
      top:${Math.random()*100}%;
      left:${Math.random()*100}%;
      --lo:${lo}; --hi:${hi}; --d:${dur};
      animation-delay:${(Math.random()*5).toFixed(1)}s;
    `;
    starsEl.appendChild(s);
  }

  // Envelope open
  const envScreen = document.getElementById('envelope-screen');
  const mainEl = document.getElementById('main');

  envScreen.addEventListener('click', () => {
    envScreen.classList.add('flap-open');
    setTimeout(() => {
      envScreen.classList.add('opened');
      mainEl.classList.add('visible');
    }, 700);
  });

  // Countdown
  function updateCountdown() {
    const wedding = new Date('2026-06-26T20:00:00');
    const now = new Date();
    const diff = wedding - now;
    if (diff <= 0) {
      document.getElementById('cd-days').textContent = '00';
      document.getElementById('cd-hours').textContent = '00';
      document.getElementById('cd-mins').textContent = '00';
      document.getElementById('cd-secs').textContent = '00';
      return;
    }
    const days  = Math.floor(diff / 86400000);
    const hours = Math.floor((diff % 86400000) / 3600000);
    const mins  = Math.floor((diff % 3600000) / 60000);
    const secs  = Math.floor((diff % 60000) / 1000);
    document.getElementById('cd-days').textContent  = String(days).padStart(2,'0');
    document.getElementById('cd-hours').textContent = String(hours).padStart(2,'0');
    document.getElementById('cd-mins').textContent  = String(mins).padStart(2,'0');
    document.getElementById('cd-secs').textContent  = String(secs).padStart(2,'0');
  }
  updateCountdown();
  setInterval(updateCountdown, 1000);

  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.classList.add('visible');
        observer.unobserve(e.target);
      }
    });
  }, { threshold: 0.12 });
  reveals.forEach(el => observer.observe(el));
</script>
</body>
</html>
