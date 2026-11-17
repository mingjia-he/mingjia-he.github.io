---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---
<!-- _pages/publications.md
     Topics are set per entry in _bibliography/papers.bib via `topic={...}`.
     Labels (keyword chips) via `labels={A, B}`, awards via `award={...}`. -->
<div class="publications">

<h2 class="pub-topic">Hierarchical Decision-Making and Feedback Control in Mobility Systems</h2>
<p class="pub-topic-desc">How public authorities, competing operators, and travelers interact across levels, and how to steer the resulting equilibria with model-free feedback.</p>
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=hierarchical]* %}

<h2 class="pub-topic">Cooperation and Mechanism Design in Network Design</h2>
<p class="pub-topic-desc">Mechanisms that let self-interested regions and operators co-invest in shared infrastructure, and share the gains fairly.</p>
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=cooperation]* %}

<h2 class="pub-topic">Earlier Work</h2>
<p class="pub-topic-desc">Before my PhD: electric-mobility infrastructure, shared mobility and travel behavior, and freight transport.</p>
<ul class="earlier-work">
  <li><b>EV charging infrastructure:</b>
    wireless charging lanes (<a href="https://doi.org/10.1016/j.trd.2023.103835"><em>Transp. Res. Part D</em>, 2023</a>);
    fast-charging facility planning (<a href="https://arxiv.org/abs/2311.12700"><em>IEEE ITSC</em>, 2023</a>);
    EV vs. gasoline vehicle ownership in 247 Chinese cities (<a href="https://doi.org/10.1016/j.trd.2025.104885"><em>Transp. Res. Part D</em>, 2025</a>).</li>
  <li><b>Freight transport:</b>
    synchromodal transport planning with preference learning (<a href="https://doi.org/10.1177/03611981241310399"><em>Transp. Res. Record</em>, 2025</a>), <span class="pub-award" style="display:inline"><i class="fa-solid fa-trophy"></i> TRB 2024 Best Academic Paper Award</span>.</li>
  <li><b>Bike-sharing:</b>
    renting–returning imbalance (<a href="https://doi.org/10.1016/j.scs.2022.103967"><em>Sustain. Cities Soc.</em>, 2022</a>);
    demand prediction with graph attention LSTM (<a href="https://doi.org/10.3390/app12031161"><em>Appl. Sci.</em>, 2022</a>);
    rebalancing optimization (<a href="https://doi.org/10.1109/ACCESS.2021.3063881"><em>IEEE Access</em>, 2021</a>);
    docked vs. dockless usage (<em>TRB Annual Meeting</em>, 2020);
    activity spaces around metro stations (<a href="https://doi.org/10.3390/su10113949"><em>Sustainability</em>, 2018</a>;
    <a href="https://doi.org/10.3390/info9110289"><em>Information</em>, 2018</a>).</li>
  <li><b>Travel behavior during COVID-19:</b>
    metro disruption and mode shifts (<a href="https://doi.org/10.1016/j.tbs.2024.100773"><em>Travel Behav. Soc.</em>, 2024</a>);
    non-commuting intentions (<a href="https://doi.org/10.1016/j.cities.2023.104341"><em>Cities</em>, 2023</a>).</li>
</ul>

</div>
