---
---

<div class="home-hero">
  <div class="home-hero-copy">
    <p class="home-eyebrow">Computational neuroscience · TU Dresden</p>
    <h1>How do minds adapt?</h1>
    <p class="home-hero-lead">
      We study the computations that support adaptive cognition—and the
      multi-scale biological machinery that brings those computations to life.
    </p>
    <div class="home-actions">
      <a class="button" href="{{ '/research/' | relative_url }}">Explore our research</a>
      <a class="button button-secondary" href="{{ '/team/' | relative_url }}">Meet the team</a>
    </div>
    <ul class="home-signals" aria-label="Research scales">
      <li>Brain</li>
      <li>Body</li>
      <li>Environment</li>
    </ul>
  </div>
  <div class="home-hero-visual">
    <img
      src="{{ '/images/research.png' | relative_url }}"
      alt="Illustrated map connecting biological intelligence, neural systems, and adaptive behavior"
    >
    <span class="home-hero-caption">
      From neural machinery to adaptive behavior across species
    </span>
  </div>
</div>

{% include section.html %}

<div class="home-section-heading">
  <div>
    <p class="section-eyebrow">Our research</p>
    <h2>Adaptive intelligence in the living world</h2>
  </div>
  <p>
    We combine computational models with neural and behavioral data to uncover
    shared principles of decision-making across brains, bodies, and environments.
  </p>
</div>

<div class="research-pillars">
  <a class="research-pillar" href="{{ '/research/#ed' | relative_url }}">
    <span class="research-pillar-inner">
      <span class="research-pillar-number">01</span>
      <h3>Environmental dynamics</h3>
      <p>How organisms track change, balance risk, and adapt decisions as their surroundings evolve.</p>
      <span class="research-pillar-arrow" aria-hidden="true">Explore →</span>
    </span>
  </a>
  <a class="research-pillar" href="{{ '/research/#wm' | relative_url }}">
    <span class="research-pillar-inner">
      <span class="research-pillar-number">02</span>
      <h3>Internal world models</h3>
      <p>How minds build, test, and update representations to predict outcomes and guide action.</p>
      <span class="research-pillar-arrow" aria-hidden="true">Explore →</span>
    </span>
  </a>
  <a class="research-pillar" href="{{ '/research/#ec' | relative_url }}">
    <span class="research-pillar-inner">
      <span class="research-pillar-number">03</span>
      <h3>Embodied constraints</h3>
      <p>How physiology, sensory limits, and biomechanics shape the strategies available to an organism.</p>
      <span class="research-pillar-arrow" aria-hidden="true">Explore →</span>
    </span>
  </a>
</div>

{% include section.html %}

<div class="home-section-heading">
  <div>
    <p class="section-eyebrow">From the lab</p>
    <h2>Latest updates</h2>
  </div>
  <a href="{{ '/blog/' | relative_url }}">View all news →</a>
</div>

<div class="home-news">
  {% include list.html data="posts" component="post-excerpt" %}
</div>
