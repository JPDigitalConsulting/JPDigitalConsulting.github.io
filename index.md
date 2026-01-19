
---
layout: default
title: Start
permalink: /
---

<section class="hero" id="home" aria-labelledby="hero-title">
  <div class="hero-media"><!-- Optional: assets/img/hero.jpg --></div>
  <div class="hero-content container">
    <h1 id="hero-title">Senior ERP Consultant & Project Manager</h1>
    <p class="subline">Fokus: <strong>Dynamics 365 Business Central</strong> – schnelle Orientierung, klare Struktur, messbare Projektergebnisse.</p>
    <div class="hero-ctas">
      <a class="btn btn-primary" href="#contact">Projekt anfragen</a>
      <a class="btn btn-secondary" href="https://www.linkedin.com/in/jan-hirt" target="_blank" rel="noopener">LinkedIn</a>
    </div>
  </div>
</section>

<section class="value container" aria-labelledby="value-title">
  <h2 id="value-title">Was ich für Sie löse</h2>
  <div class="value-grid">
    <article class="value-card"><h3>Komplexität reduzieren</h3><p>Klare Projektstruktur, saubere Kommunikation, pragmatische Entscheidungen – ohne Overhead.</p></article>
    <article class="value-card"><h3>BC schneller nutzbar machen</h3><p>Fit/Gap, priorisierte Roadmap und fokussiertes Delivery für <em>Dynamics 365 Business Central</em>.</p></article>
    <article class="value-card"><h3>Risiken senken</h3><p>Transparente Planung, realistische Timelines, kontinuierliches Risikomanagement.</p></article>
  </div>
</section>

<section id="about" class="about container" aria-labelledby="about-title">
  <div class="about-media"><!-- Optional: assets/img/portrait.jpg --></div>
  <div class="about-text">
    <h2 id="about-title">Über mich</h2>
    <p>Ich unterstütze Unternehmen als <strong>Senior ERP Consultant & Projektleiter</strong> bei Planung, Einführung und Optimierung von <strong>Dynamics 365 Business Central</strong>. Praxisnah, transparent und zielorientiert – damit Teams schnell ins Doing kommen und Ergebnisse sichtbar werden.</p>
    <ul class="bullets">
      <li>Branchenübergreifende ERP‑Projekte (KMU bis Konzernumfeld)</li>
      <li>End‑to‑End: Analyse, Implementierung, Rollout, Training</li>
      <li>Remote‑first, international einsatzfähig</li>
    </ul>
  </div>
</section>

<section id="services" class="services container" aria-labelledby="services-title">
  <h2 id="services-title">Leistungen</h2>
  <div class="service-grid">
    {%- for s in site.data.services -%}
    <article class="service-card">
      <div class="icon" aria-hidden="true">{{ s.icon }}</div>
      <h3>{{ s.title }}</h3>
      <p>{{ s.text }}</p>
    </article>
    {%- endfor -%}
  </div>
</section>

<section id="proof" class="proof container" aria-labelledby="proof-title">
  <h2 id="proof-title">Highlights</h2>
  <ul class="proof-list">
    <li>Erfahrung mit ERP‑Einführungen & Rollouts in unterschiedlichen Branchen</li>
    <li>Fokus auf Dynamics 365 Business Central & Schnittstellen</li>
    <li>Hands‑on Delivery: pragmatisch, transparent, verlässlich</li>
  </ul>
  <div class="logo-row" aria-label="Kundenlogos (optional)"></div>
</section>

<section id="cases" class="cases container" aria-labelledby="cases-title">
  <h2 id="cases-title">Ausgewählte Projekte</h2>
  <div class="case-grid">
    {%- for p in site.projects -%}
    <article class="case-card">
      <h3>{{ p.title }}</h3>
      <p class="case-meta">Rolle: {{ p.role }} • Dauer: {{ p.duration }}</p>
      <p>{{ p.excerpt }}</p>
    </article>
    {%- endfor -%}
  </div>
  <p class="hint">Mehr Details oder Referenzen gern auf Anfrage.</p>
</section>

<section id="contact" class="contact container" aria-labelledby="contact-title">
  <h2 id="contact-title">Kontakt</h2>
  <p>Schneller Einstieg? Schreiben Sie mir kurz Ihr Anliegen – ich melde mich zeitnah.</p>
  <div class="contact-actions">
    <a class="btn btn-primary" href="mailto:hello@jpdigital.consulting">E‑Mail senden</a>
    <a class="btn btn-secondary" href="https://www.linkedin.com/in/jan-hirt" target="_blank" rel="noopener">LinkedIn</a>
  </div>
  <p class="contact-meta">Bevorzugt remote • Verfügbarkeit nach Absprache</p>
</section>
