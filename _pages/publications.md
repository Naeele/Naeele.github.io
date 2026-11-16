---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2024, 2025, 2026]
---

<style>
.jumbotron {
    padding: 3%;
    padding-bottom: 10px;
    padding-top: 10px;
    margin-top: 10px;
    margin-bottom: 30px;
}
</style>

<div class="jumbotron">

<h3>Refereed conference proceedings</h3>

<!-- CCS 2026: manually added -->
<ol class="bibliography" reversed start="2">
<li>

<style>
.btn {
    margin-bottom: 5px;
    padding-top: 0px;
    padding-bottom: 0px;
    padding-left: 15px;
    padding-right: 15px;
    height: 20px;
}
</style>

<div class="text-justify">
<strong>Fayolle, I.</strong>, Geimer, A., De Almeida Braga, D., &amp; Maurice, C. (2026).
Practice Makes (Im)Perfect: A Look Back at Benchmarking Practices for Microarchitectural Side-Channel Attacks.
<i>Proceedings of the 2026 ACM SIGSAC Conference on Computer and Communications Security</i>,
<i>1655–1669.</i>
<a href="https://doi.org/10.1145/3830454.3846555">
https://doi.org/10.1145/3830454.3846555
</a>
</div>

<a href="{{ '/papers/ccs_26fayolle.pdf' | relative_url }}" target="_blank">
<button class="btn btn-success btn-sm">PDF</button>
</a>

<a href="https://doi.org/10.1145/3830454.3846555" target="_blank">
<button class="btn btn-primary btn-sm">DOI</button>
</a>

<button class="btn btn-danger btn-sm" onclick="toggleBibtexCCS26()">BIB</button>

<button class="btn btn-warning btn-sm" onclick="toggleAbstractCCS26()">ABSTRACT</button>

<a href="https://github.com/Naeele/Practice_Makes_-Im-Perfect---Artifacts"
   target="_blank" rel="noopener">
<button class="btn btn-info btn-sm">ARTIFACTS</button>
</a>

<div id="aCCS26" style="display:none; background-color:black; border-radius:5px; padding:10px; margin-bottom:20px;">
<pre>
@inproceedings{FayolleCCS26,
  author = {Fayolle, Iliana and Geimer, Antoine and De Almeida Braga, Daniel and Maurice, Cl{\'e}mentine},
  title = {Practice Makes (Im)Perfect: A Look Back at Benchmarking Practices for Microarchitectural Side-Channel Attacks},
  year = {2026},
  isbn = {9798400728716},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3830454.3846555},
  doi = {10.1145/3830454.3846555},
  booktitle = {Proceedings of the 2026 ACM SIGSAC Conference on Computer and Communications Security},
  pages = {1655--1669},
  numpages = {15},
  keywords = {microarchitectural, side-channel attacks, benchmarking},
  location = {The Hague, Netherlands},
  series = {CCS '26}
}
</pre>
</div>

<div id="bCCS26" style="display:none; background-color:black; border-radius:5px; padding:10px; margin-bottom:20px;">
<pre>
Microarchitectural side-channel research has grown at an exceptional pace in recent years, increasing the need for rigorous and meaningful benchmarking. Early attack papers typically relied on indirect proxies, such as covert-channel bandwidth or key-recovery on naive AES and RSA implementations, setting de facto standards that many subsequent works continued to replicate, sometimes by directly comparing against raw numbers from prior work. While these practices offer convenient points of comparison, current benchmarks may not be the most relevant to assess specific properties of new primitives. Even more problematic, microarchitectural attacks are notoriously sensitive to experimental conditions: minimal changes in the target system can significantly alter outcomes and performance. As a result, inadequate evaluation practices undermine reproducibility and cast doubt on the relevance of comparisons, even in top-tier venues where such issues should be identified.
This paper tackles the core problem of proper benchmarking for microarchitectural side-channel attacks and examines its broader impact on research quality in the field. We survey 83 attack papers published in top-ranked security and architecture conferences from 2014 to 2024. From this corpus, we identify and define 19 recurrent benchmarking flaws that affect evaluation completeness, relevance, soundness, and reproducibility. These flaws include unfair or absent comparisons, missing code or materials, and the failure to evaluate the key attack properties. On average, each paper exhibits 5.5 such flaws, highlighting how widespread the issue is, even in highly selective venues. Based on our findings, we identify and suggest key properties that are relevant to properly evaluate new attacks. We also highlight trends over time and different practices between security and architecture conferences.
</pre>
</div>

<script>
function toggleBibtexCCS26() {
    var x = document.getElementById('aCCS26');
    x.style.display = x.style.display === 'none' ? 'block' : 'none';
}

function toggleAbstractCCS26() {
    var x = document.getElementById('bCCS26');
    x.style.display = x.style.display === 'none' ? 'block' : 'none';
}
</script>

<!-- Semi-automated and Easily Interpretable Side-Channel Analysis for Modern JavaScript. -->


<div class="text-justify"><span id="FayolleWKREM24"><strong>Fayolle, I.</strong>, Wichelmann, J., Köhl, A., Rudametkin, W., Eisenbarth, T., &amp; Maurice, C. (2024). Semi-automated and Easily Interpretable Side-Channel Analysis for Modern JavaScript. <i>CANS (2)</i>, <i>14906</i>, 25–46. https://doi.org/10.1007/978-981-97-8016-7_2</span></div>


<a href="http://localhost:4000/papers/cans24_fayolle.pdf" target="_blank"><button class="btn btn-success btm-sm">PDF</button></a>

<a href="http://doi.org/10.1007/978-981-97-8016-7_2" target="_blank"><button class="btn btn-primary btm-sm">DOI</button></a>

<button class="btn btn-danger btm-sm" onclick="toggleBibtexFayolleWKREM24()">BIB</button>

<button class="btn btn-warning btm-sm" onclick="toggleAbstractFayolleWKREM24()">ABSTRACT</button>

<div id="aFayolleWKREM24" style="display: none; background-color:black; border-radius:5px; padding:10px; margin-bottom:20px;">
<pre>@inproceedings{FayolleWKREM24,
  author = {Fayolle, Iliana and Wichelmann, Jan and Köhl, Anja and Rudametkin, Walter and Eisenbarth, Thomas and Maurice, Clémentine},
  title = {Semi-automated and Easily Interpretable Side-Channel Analysis for Modern JavaScript},
  booktitle = {{CANS} {(2)}},
  series = {Lecture Notes in Computer Science},
  volume = {14906},
  pages = {25--46},
  publisher = {Springer},
  year = {2024},
  file = {cans24_fayolle.pdf},
  url = {https://doi.org/10.1007/978-981-97-8016-7\_2},
  doi = {10.1007/978-981-97-8016-7\_2},
  artifacts = {https://github.com/EasyWalk-CI-project/EasyWalk-Evaluation}
}
</pre>
</div>

<a href="https://github.com/EasyWalk-CI-project/EasyWalk-Evaluation" target="_blank" rel="noopener">
  <button class="btn btn-info btm-sm">ARTIFACTS</button>
</a>


<div id="bFayolleWKREM24" style="display: none; background-color:black; border-radius:5px; padding:10px; margin-bottom:20px;">
<pre>Over the years, developers have become increasingly reliant on web technologies to build their applications, raising concerns about side-channel attacks, especially on cryptographic libraries. Despite the efforts of researchers to ensure constant-time security by proposing tools and methods to find vulnerabilities, challenges remain due to inadequate tools and integration issues in development processes. We tackle the main limitations of state-of-the-art detection tools. While Microwalk is the first and, to the best of our knowledge, only tool to find side-channel vulnerabilities in JavaScript libraries, the instrumentation framework it relies on does not support modern JavaScript features. Moreover, and common to most state-of-the-art detection tools not aimed at JavaScript, writing tests is a tedious process due to the complexity of libraries, the lack of information about test coverage, and the rudimentary interpretability of the report. Furthermore, recent studies show that developers do not use these tools due to compatibility issues, poor usability, and a lack of integration into workflows. We extend Microwalk in several directions. First, we design a generic AST-level tracing technique that is tailored to source-based dynamic side-channel leakage analysis, providing support for the latest language features. Second, we bring semi-automation to Microwalk analysis templates, considerably reducing the manual effort necessary to integrate side-channel analyses into development workflows. Third, we are the first to combine leakage reporting with coverage visualization. We evaluate the new toolchain on a set of cryptographic libraries and show that it can quickly and comprehensively uncover more vulnerabilities while writing tests with half as many lines of code as the previous Microwalk version. By open sourcing our new tracer and analysis template, we hope to increase the adoption of automated side-channel leakage analyses in cryptographic library development.</pre>
</div>

<script>
function toggleBibtexFayolleWKREM24(parameter) {
    var x= document.getElementById('aFayolleWKREM24');
    if (x.style.display === 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }
}
function toggleAbstractFayolleWKREM24(parameter) {
    var x= document.getElementById('bFayolleWKREM24');
    if (x.style.display === 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }
}
</script>
</li></ol>
</div>