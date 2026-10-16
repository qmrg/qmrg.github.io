---
layout: default
title: QMRG
---

<section class="hero">
  <p class="eyebrow">RGS-IBG Research Group</p>
  <h1>Quantitative Methods Research Group</h1>
  <p class="lede">The QMRG promotes the application of quantitative methods in geography, from statistics and spatial data science to modelling, across human and physical geography.</p>
  <p class="actions">
    <a class="button" href="/about">About the group</a>
    <a class="button button-secondary" href="https://uk.linkedin.com/company/quantitative-methods-research-group-rgs">Follow us on LinkedIn</a>
  </p>
</section>

<section class="home-section">
  <h2>Latest news</h2>
  <ul class="posts posts-home">
    {% for post in site.posts limit:4 %}
    <li>
      <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%-d %b %Y" }}</time>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
  </ul>
  <p><a href="/blog">All posts →</a></p>
</section>

<section class="home-section">
  <h2>Explore</h2>
  <div class="cards">
    <a class="card" href="/prizes">
      <h3>Prizes</h3>
      <p>Our undergraduate dissertation prize and the Robin Flowerdew Award for postgraduate papers.</p>
    </a>
    <a class="card" href="/committee">
      <h3>Committee</h3>
      <p>Who runs the group today, and everyone who has served on the committee before.</p>
    </a>
    <a class="card" href="/publications">
      <h3>Publications</h3>
      <p>Reports on quantitative geography, the CATMOG series and the SAD interviews.</p>
    </a>
    <a class="card" href="https://www.jiscmail.ac.uk/cgi-bin/webadmin?SUBED1=QUANT-GEOG&amp;A=1">
      <h3>Mailing list</h3>
      <p>Join QUANT-GEOG for news, calls and events in quantitative geography.</p>
    </a>
  </div>
</section>
