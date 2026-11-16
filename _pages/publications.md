---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2024, 2025, 2026]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">

<h3>Refereed conference proceedings</h3>

<ol reversed>

  <!-- CCS 2026 -->
  <li>
    <div class="text-justify">
      <strong>Fayolle, I.</strong>, Geimer, A., De Almeida Braga, D., &amp; Maurice, C. (2026).
      Practice Makes (Im)Perfect: A Look Back at Benchmarking Practices for Microarchitectural Side-Channel Attacks.
      <i>Proceedings of the 2026 ACM SIGSAC Conference on Computer and Communications Security</i>,
      1655–1669.
      <a href="https://doi.org/10.1145/3830454.3846555">https://doi.org/10.1145/3830454.3846555</a>
    </div>

    <a href="{{ '/papers/ccs26_fayolle.pdf' | relative_url }}" target="_blank">
      <button class="btn btn-success btn-sm">PDF</button>
    </a>

    <a href="https://doi.org/10.1145/3830454.3846555" target="_blank">
      <button class="btn btn-primary btn-sm">DOI</button>
    </a>

    <a href="https://github.com/Naeele/Practice_Makes_-Im-Perfect---Artifacts"
       target="_blank" rel="noopener">
      <button class="btn btn-info btn-sm">ARTIFACTS</button>
    </a>
  </li>

  <!-- CANS 2024 -->
  {% bibliography --query @*[key = "FayolleWKREM24"] %}

</ol>

</div>