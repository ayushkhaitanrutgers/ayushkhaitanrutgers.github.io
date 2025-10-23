---
layout: default
title: Research Group
permalink: /research-group
---

<section id="research" class="res">

  <h1 class="res__title">Research group</h1>

  <!-- ===== AI for Mathematics ===== -->
  <article class="card">
    <h2 class="card__title">AI for Mathematics</h2>
    <div class="card__body">
      <p>I run a research group with some undergraduate Math adn CS students. We develop AI tools that can help mathematicians in their research. We also fine-tune open source models on various Mathematica packages.
      </p>
      </div>
  </article>

</section>

<style>
  :root{
    --bg: #ffffff;
    --ink: #0f172a;
    --mute: #475569;
    --soft: #55627a;
    --line: #e6e8ee;
    --chip: #f7f8fc;
    --r: 14px;
  }

  .res{ background: var(--bg); max-width: 900px; }
  .res__title{ margin: 0 0 6px 0; font-size: 2rem; line-height: 1.2; color: var(--ink); }

  .card{ padding: 16px 0 18px 0; border-top: 1px solid var(--line); }
  .card:first-of-type{ border-top: 0; }

  .card__title{ margin: 0 0 8px 0; font-size: 1.35rem; font-weight: 650; color: var(--ink); }

  .card__body{
    background: var(--chip);
    border: 1px solid var(--line);
    border-radius: var(--r);
    padding: 14px 16px;
    color: var(--soft);
    font-size: 0.98rem;
    line-height: 1.55;
  }

  .card__body a{
    color: #3347c2;
    text-decoration: none;
    border-bottom: 1px dotted rgba(51,71,194,.35);
  }
  .card__body a:hover{ border-bottom-color: transparent; }

  @media (max-width: 640px){
    .card__title{ font-size: 1.2rem; }
    .card__body{ font-size: 0.96rem; }
  }
</style>
