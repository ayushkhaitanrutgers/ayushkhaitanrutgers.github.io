---
layout: default
title: Publications
permalink: /publications
---

# Publications

Below is a list of my publications with always-visible summaries. I’ve tuned the typography and colors for a calmer, cleaner look.

<!-- ======= LIGHT, CRISP STYLES JUST FOR THIS PAGE ======= -->
<style>
  :root {
    --ink: #0f172a;            /* deep slate */
    --muted: #475569;          /* slate-600 */
    --soft: #64748b;           /* slate-500 */
    --line: #e2e8f0;           /* slate-200 */
    --paper: #ffffff;
    --petal: #f6f7fb;          /* soft blue-lavender */
    --accent: #5b6bc6;         /* relaxed lavender-blue */
    --accent-ink: #3944a3;
  }
  @media (prefers-color-scheme: dark) {
    :root{
      --ink:#e5e7eb; --muted:#cbd5e1; --soft:#94a3b8; --line:#1f2937;
      --paper:#0b1020; --petal:#0f162c; --accent:#93a2ff; --accent-ink:#c7ceff;
    }
  }

  .pub-list{max-width: 980px;}
  .pub{border-left: 3px solid var(--accent); padding: 1.1rem 1.2rem; margin: 1.2rem 0;
       background: var(--paper);}
  .pub + .pub{border-top: 1px solid var(--line);}
  .pub-title{font-size: 1.45rem; line-height: 1.25; margin: 0 0 .25rem 0; color: var(--ink)}
  .pub-title em{font-style: italic;}
  .pub-authors,
  .pub-meta{margin: .15rem 0; color: var(--muted); font-size: .98rem}
  .pub-meta a{color: var(--accent); text-decoration: none; border-bottom: 1px dotted var(--accent);}
  .pub-meta a:hover{color: var(--accent-ink); border-bottom-color: transparent;}

  /* Summary: smaller, crisp, calm */
  .pub-summary{
    margin-top: .55rem;
    padding: .75rem .85rem;
    background: var(--petal);
    border: 1px solid var(--line);
    border-radius: .6rem;
    color: var(--soft);
    font-size: .92rem;         /* smaller text */
    line-height: 1.45;         /* airy */
  }
</style>

<div class="pub-list">

  <section class="pub">
    <h2 class="pub-title">Paper 1: <em>An LLM–CAS framework for proving asymptotic inequalities</em></h2>
    <div class="pub-authors"><strong>Authors:</strong> Ayush Khaitan, <a href="https://www.cc.gatech.edu/people/vijay-ganesh">Vijay Ganesh</a></div>
    <div class="pub-meta">ICLR 2026 (submitted), 2025 — <a href="https://arxiv.org/abs/2510.12350">arXiv:2510.12350</a></div>
    <div class="pub-summary">
      We build an LLM+CAS framework that proves research-level asymptotic inequalities. Using it, we resolve multiple questions from MathOverflow and other research forums. This answers a question posed by Terence Tao about whether such a tool can be built in the first place.
    </div>
  </section>

  <section class="pub">
    <h2 class="pub-title">Paper 2: <em>Elementary symmetric polynomials under the fixed point measure</em></h2>
    <div class="pub-authors"><strong>Authors:</strong> Ayush Khaitan, <a href="https://sites.math.rutgers.edu/~narayanan/">Bhargav Narayanan</a>, <a href="https://sites.google.com/site/ishanmata">Ishan Mata</a></div>
    <div class="pub-meta">Submitted, 2025 — <a href="https://arxiv.org/abs/2505.12178">arXiv:2505.12178</a></div>
    <div class="pub-summary">
      We prove a surprising inhomogeneous inequality for symmetric polynomials, fully confirming a conjecture of Bhargav Narayanan. The result advances the program of obtaining sharp unconditional lower bounds on the permanent of a matrix.
    </div>
  </section>

  <section class="pub">
    <h2 class="pub-title">Paper 3: <em>Computing renormalized curvature integrals on Poincaré–Einstein manifolds</em></h2>
    <div class="pub-authors"><strong>Authors:</strong> <a href="https://sites.google.com/view/jeffreyscase">Jeffrey Case</a>, <a href="https://sites.google.com/view/yuehjulin">Yueh-Ju Lin</a>, <a href="https://aaron-tyrrell.com">Aaron Tyrrell</a>, <a href="https://www.genealogy.math.ndsu.nodak.edu/id.php?id=241215">Wei Yuan</a>, Ayush Khaitan</div>
    <div class="pub-meta">Submitted, 2024 — <a href="https://arxiv.org/abs/2404.11319">arXiv:2404.11319</a></div>
    <div class="pub-summary">
      We describe a general procedure for constructing renormalized curvature integrals on Poincaré–Einstein manifolds, yielding a systematic path to explicit curvature formulas and their analytic properties.
    </div>
  </section>

  <section class="pub">
    <h2 class="pub-title">Paper 4: <em>Ambient metric for manifolds with density and the Ricci flow</em></h2>
    <div class="pub-authors"><strong>Authors:</strong> Ayush Khaitan</div>
    <div class="pub-meta"><em>Advances in Mathematics</em> (accepted), 2023 — <a href="https://arxiv.org/abs/2308.02061">arXiv:2308.02061</a></div>
    <div class="pub-summary">
      We construct fully non-linear analogues of Perelman’s \(\mathcal W\)-functional that are monotone along the Ricci flow and stationary only for shrinking Ricci solitons, via a Fefferman–Graham ambient metric adapted to manifolds with density.
    </div>
  </section>

  <section class="pub">
    <h2 class="pub-title">Paper 5: <em>The weighted ambient metric</em></h2>
    <div class="pub-authors"><strong>Authors:</strong> <a href="http://www.personal.psu.edu/jqc5026/">Jeffrey S. Case</a>, Ayush Khaitan</div>
    <div class="pub-meta"><em>SIGMA</em> <strong>18</strong> (2022), 086, 21 pages — <a href="https://www.emis.de/journals/SIGMA/2022/086/">Journal link</a></div>
    <div class="pub-summary">
      We construct the Fefferman–Graham ambient metric for smooth metric measure spaces, providing the base geometry for weighted curvature invariants and their applications.
    </div>
  </section>

  <section class="pub">
    <h2 class="pub-title">Paper 6: <em>GJMS operators of smooth metric measure spaces</em></h2>
    <div class="pub-authors"><strong>Authors:</strong> Ayush Khaitan</div>
    <div class="pub-meta">Submitted, 2022 — <a href="https://arxiv.org/abs/2203.04719">arXiv:2203.04719</a></div>
    <div class="pub-summary">
      We construct GJMS operators in the weighted setting, extending the conformally covariant family to smooth metric measure spaces and linking ambient methods with analysis on manifolds with density.
    </div>
  </section>

  <section class="pub">
    <h2 class="pub-title">Paper 7: <em>Weighted renormalized volume coefficients</em></h2>
    <div class="pub-authors"><strong>Authors:</strong> Ayush Khaitan</div>
    <div class="pub-meta">Submitted, 2022 — <a href="https://arxiv.org/abs/2205.06018">arXiv:2205.06018</a></div>
    <div class="pub-summary">
      We construct renormalized volume coefficients for smooth metric measure spaces and prove several key properties, extending conformal/renormalization techniques to weighted geometries.
    </div>
  </section>

</div>
