---
layout: about
title: about
permalink: /
subtitle: >
  Undergraduate, Department of Nursing, Chung-Ang University

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>📧 pjs12101113@cau.ac.kr</p>
    <p>📱 (+82)-10-4094-5719</p>

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<style>
  .post .post-header .post-title {
    font-size: clamp(2rem, 5vw, 3.2rem);
    line-height: 1.15;
  }
  .post .post-header .desc {
    font-size: 1.1rem;
    line-height: 1.6;
    color: var(--global-text-color-light);
  }
  .post .profile img {
    display: block;
    width: 100%;
    max-width: 220px;
    height: auto;
    aspect-ratio: auto;
    object-fit: contain;
  }
  .folio-intro {
    line-height: 1.75;
  }
  .folio-interests {
    margin-top: 1.75rem;
    padding-top: 1rem;
    border-top: 1px solid var(--global-divider-color);
  }
  .folio-interests h2 {
    margin-bottom: 0.65rem;
    font-size: 1.1rem;
    font-weight: 500;
  }
  .folio-interests ul {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem 1.25rem;
    padding: 0;
    list-style: none;
    font-size: 0.95rem;
  }
  .folio-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem 1.5rem;
    margin-top: 1.25rem;
  }
  .folio-links a {
    text-decoration: underline;
    text-underline-offset: 0.2em;
    text-decoration-thickness: 1px;
  }
  .folio-links a:focus-visible {
    outline: 2px solid var(--global-theme-color);
    outline-offset: 4px;
  }
  @media (max-width: 575px) {
    .post .profile img {
      max-width: 200px;
      margin-inline: auto;
    }
    .folio-interests {
      margin-top: 1.5rem;
    }
  }
</style>

<div class="folio-intro" markdown="1">
I am an undergraduate student in the Department of Nursing at Chung-Ang University (expected graduation: Feb. 2028).

I am particularly interested in how data-driven and AI-based approaches can improve clinical workflow, promote patient health, and prevent medical errors.

<section class="folio-interests" aria-labelledby="research-interests-heading">
  <h2 id="research-interests-heading">Research interests</h2>
  <ul role="list">
    <li>Nursing informatics</li>
    <li>Healthcare AI</li>
    <li>Human–AI interaction</li>
    <li>Medical big data analytics</li>
  </ul>
</section>

<nav class="folio-links" aria-label="Explore my work">
  <a href="{{ '/projects/' | relative_url }}">View projects</a>
  <a href="{{ '/cv/' | relative_url }}">View CV</a>
</nav>
</div>
