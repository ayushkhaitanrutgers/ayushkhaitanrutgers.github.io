---
layout: default
title: Research
permalink: /research
---

<section id="research" class="res">

  <h1 class="res__title">Research</h1>

  <!-- ===== AI for Mathematics ===== -->
  <article class="card">
    <h2 class="card__title">AI for Mathematics</h2>
    <div class="card__body">
      <p>My work in this area involves constructing AI tools that can be useful in mathematics research. This involves training and fine-tuning LLMs, and integrating LLMs with computer algebra systems. Using an LLM+CAS framework, we were recently able to answer a question of Terence Tao by constructing an AI tool that can prove research-level inequalities from several mathematical domains.</p>
    </div>
  </article>

  <!-- ===== Geometric analysis & conformal geometry ===== -->
  <article class="card">
    <h2 class="card__title">Geometric analysis and conformal geometry</h2>
    <div class="card__body">
      <p>In my PhD, I have constructed an infinite family of fully non-linear analogues of Perelman's W-functional, that are monotone along the Ricci flow.</p>
      <p>During my postdoc, I have fully proved a conjecture of Bhargav Narayanan, and partially solved the problem of proving sharp lower bounds on the permanent of a matrix, using tools from geometric analysis. Proving sharp lower bounds on the permanent of a matrix is an old, central problem in statistical mechanics, theoretical computer science and combinatorics, and we were surprisingly able to make progress on this question using monotone flows and differential operators.</p>
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

  @media (max-width: 640px){
    .card__title{ font-size: 1.2rem; }
    .card__body{ font-size: 0.96rem; }
  }
</style>
