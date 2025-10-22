---
layout: default
title: Teaching
permalink: /teaching
---

<section id="teaching" class="res">

  <h1 class="res__title">Teaching</h1>

  <!-- ===== AI for Mathematics ===== -->
  <article class="card">
    <h2 class="card__title">AI and Mathematics</h2>
    <div class="card__body">
      <p>In Fall 2025, I am teaching a Graduate course on AI methods in research mathematics. This course has two separate, relatively disjoint components. In the first component, we go over the basics of machine learning, heavily based on <a href = "https://ocw.mit.edu/courses/6-867-machine-learning-fall-2006/pages/lecture-notes/">these notes</a> from MIT OCW. </p>
      <p> In the second part of the course, we study how to modify existing AI technologies like Funsearch and Alphageometry to be able to solve problems in other fields of Mathematics. This is primarily done through student projects, with weekly meetings and guidance.</p>
    </div>
  </article>

  <!-- ===== Geometric analysis & conformal geometry ===== -->
  <article class="card">
    <h2 class="card__title">Intro to proofs using Lean</h2>
    <div class="card__body">
      <p>I am also teaching an Intro to Proofs course based on Lean. This is one of the first such courses offered in the country, and I had to design several components of the course myself, that may be useful to other instructors teaching this course in the future.</p>
      <p>We are using Heather Macbeth's <a href= "https://hrmacbeth.github.io/math2001/">textbook</a> in our course. The students are expected to write both rigorous "human" proofs, as well as Lean proofs for every question that we attempt. We are systematically working through the entire textbook, and uploading solutions to all questions on GitHub. This comprehensive approach to Lean has been very rewarding, and most of the students in my class can now write proofs for non-trivial lemmas all by themselves, using intricate sequences of tactics and lemmas from MathLib4.</p>
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
