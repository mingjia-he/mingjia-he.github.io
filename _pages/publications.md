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

<h2 class="pub-topic">Cooperation and Mechanism Design in Networked Infrastructure Planning</h2>
<p class="pub-topic-desc">Mechanisms that let self-interested regions and operators co-invest in shared infrastructure, and share the gains fairly.</p>
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=cooperation]* %}

<h2 class="pub-topic">Welfarist Control Design</h2>
<p class="pub-topic-desc">Controlling multi-agent systems means trading off the costs of different participants, yet these costs can rarely be compared on a common scale. Drawing on social choice theory, we build efficiency metrics and control objectives that remain meaningful under limited interpersonal comparability, and bring fairness and equity into traffic control.</p>
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=welfarist]* %}

<h2 class="pub-topic">Data-Driven Planning and Operation of Mobility Systems</h2>
<p class="pub-topic-desc">How should mobility infrastructure be designed and services be operated, given how users behave?</p>
<div class="topic-papers">
  <div class="path-skills"><span>Multi-objective optimization</span><span>Agent-based micro-simulation</span><span>Preference learning</span><span>Multi-criteria decision-making</span></div>
  <ul class="path-papers">
    <li class="first-author"><a href="https://doi.org/10.1177/03611981241310399">Integrated Synchromodal Transport Planning and Preference Learning</a> <span class="path-venue">Transp. Res. Record, 2025</span> <span class="path-tech">neural preference learning</span><br><span class="pub-award"><i class="fa-solid fa-trophy"></i> TRB 2024 Best Academic Paper Award</span></li>
    <li class="first-author"><a href="https://doi.org/10.1016/j.trd.2023.103835">A Data-Driven Large-Scale Micro-Simulation Approach to Deploying and Operating Wireless Charging Lanes</a> <span class="path-venue">Transp. Res. Part D, 2023</span> <span class="path-tech">agent-based simulation</span></li>
    <li class="first-author"><a href="https://arxiv.org/abs/2311.12700">A Data-Driven Integrated Framework for Fast-Charging Facility Planning using Multi-Period Bi-Objective Optimization</a> <span class="path-venue">IEEE ITSC, 2023</span> <span class="path-tech">bi-objective optimization</span></li>
    <li class="first-author"><a href="https://doi.org/10.1109/ACCESS.2021.3063881">Station Importance Evaluation in Dynamic Bike-Sharing Rebalancing Optimization Using an Entropy-Based TOPSIS Approach</a> <span class="path-venue">IEEE Access, 2021</span> <span class="path-tech">MCDM + optimization</span></li>
  </ul>
</div>

<h2 class="pub-topic">Travel Behavior and Demand Modeling</h2>
<p class="pub-topic-desc">How do travelers choose, and how does demand vary across space, time, and disruptions?</p>
<div class="topic-papers">
  <div class="path-skills"><span>Discrete choice &amp; latent class models</span><span>Spatial econometrics</span><span>Spatio-temporal deep learning</span><span>Large-scale mobility data</span></div>
  <ul class="path-papers">
    <li><a href="https://doi.org/10.1016/j.trd.2025.104885">Electric or Gasoline Vehicle? Determinants of Vehicle Ownership in 247 Chinese Cities</a> <span class="path-venue">Transp. Res. Part D, 2025</span></li>
    <li><a href="https://doi.org/10.1016/j.tbs.2024.100773">How Temporary Disruption of Metro Service Influences Commuters’ Mode Shifts during COVID-19</a> <span class="path-venue">Travel Behav. Soc., 2024</span></li>
    <li><a href="https://doi.org/10.1016/j.cities.2023.104341">Non-Commuting Intentions during COVID-19: A Hybrid Latent Class Modeling Approach</a> <span class="path-venue">Cities, 2023</span> <span class="path-tech">latent class model</span></li>
    <li class="first-author"><a href="https://doi.org/10.1016/j.scs.2022.103967">Geographically Weighted Multinomial Logit Models for Bike-Sharing Renting–Returning Imbalance</a> <span class="path-venue">Sustain. Cities Soc., 2022</span> <span class="path-tech">spatial discrete choice</span></li>
    <li><a href="https://doi.org/10.3390/app12031161">Short-Term Prediction of Bike-Sharing Demand: A Spatial-Temporal Graph Attentional LSTM Approach</a> <span class="path-venue">Appl. Sci., 2022</span> <span class="path-tech">graph neural networks</span></li>
    <li class="first-author">Understanding the Difference in Regularity of Bike-Sharing Usage between Docked and Dockless Systems <span class="path-venue">TRB Annual Meeting, 2020</span></li>
    <li><a href="https://doi.org/10.3390/su10113949">Modeling the Factors Influencing the Activity Spaces of Bikeshare around Metro Stations</a> <span class="path-venue">Sustainability, 2018</span> <span class="path-tech">spatial regression</span></li>
    <li><a href="https://doi.org/10.3390/info9110289">Measuring Bikeshare Access/Egress Distance and Catchment Area around Metro Stations from Smartcard Data</a> <span class="path-venue">Information, 2018</span></li>
  </ul>
</div>

</div>
