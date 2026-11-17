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
<p class="pub-topic-desc">When authorities, competing operators, and travelers decide at different levels, how can policy steer the resulting equilibria without modeling and differentiating through each level’s response?</p>
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=hierarchical]* %}

<h2 class="pub-topic">Cooperation and Mechanism Design in Networked Infrastructure Planning</h2>
<p class="pub-topic-desc">How can self-interested regions and operators be brought to co-invest in shared infrastructure, and how should the gains be divided so that cooperation is efficient, stable, and fair?</p>
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=cooperation]* %}

<h2 class="pub-topic">Welfarist Control Design</h2>
<p class="pub-topic-desc">How should the efficiency and fairness of a multi-agent system be measured, and then optimized, when its participants’ costs cannot be compared on a common scale?</p>
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=welfarist]* %}

<h2 class="pub-topic">Data-Driven Planning and Operation of Mobility Systems</h2>
<p class="pub-topic-desc">How can user behavior models, derived from large-scale mobility data, be effectively integrated into strategic decisions regarding infrastructure placement and service operations?</p>
<div class="topic-papers">
  <ul class="path-papers">
    <li class="first-author"><div class="path-title"><a href="https://doi.org/10.1177/03611981241310399">Integrated Synchromodal Transport Planning and Preference Learning</a></div>
      <div class="path-venue">Transportation Research Record, 2025</div>
      <div class="pub-award"><i class="fa-solid fa-trophy"></i> TRB 2024 Best Academic Paper Award</div>
      <div class="pub-labels"><span class="pub-label">Freight transport</span><span class="pub-label">Preference learning</span><span class="pub-label">Neural networks</span></div></li>
    <li class="first-author"><div class="path-title"><a href="https://doi.org/10.1016/j.trd.2023.103835">A Data-Driven Large-Scale Micro-Simulation Approach to Deploying and Operating Wireless Charging Lanes</a></div>
      <div class="path-venue">Transportation Research Part D: Transport and Environment, 2023</div>
      <div class="pub-labels"><span class="pub-label">EV charging</span><span class="pub-label">Agent-based simulation</span><span class="pub-label">Multi-objective optimization</span></div></li>
    <li class="first-author"><div class="path-title"><a href="https://arxiv.org/abs/2311.12700">A Data-Driven Integrated Framework for Fast-Charging Facility Planning using Multi-Period Bi-Objective Optimization</a></div>
      <div class="path-venue">IEEE 26th International Conference on Intelligent Transportation Systems (ITSC), 2023</div>
      <div class="pub-labels"><span class="pub-label">EV charging</span><span class="pub-label">Facility planning</span><span class="pub-label">Bi-objective optimization</span></div></li>
    <li class="first-author"><div class="path-title"><a href="https://doi.org/10.1109/ACCESS.2021.3063881">Station Importance Evaluation in Dynamic Bike-Sharing Rebalancing Optimization Using an Entropy-Based TOPSIS Approach</a></div>
      <div class="path-venue">IEEE Access, 2021</div>
      <div class="pub-labels"><span class="pub-label">Bike-sharing</span><span class="pub-label">Rebalancing optimization</span><span class="pub-label">TOPSIS</span></div></li>
  </ul>
</div>

<h2 class="pub-topic">Travel Behavior and Demand Modeling</h2>
<p class="pub-topic-desc">What drives travelers’ choices regarding transport modes, vehicles, and services, and how do these preferences vary geographically, evolve over time, and adapt to system disruptions?</p>
<div class="topic-papers">
  <ul class="path-papers">
    <li><div class="path-title"><a href="https://doi.org/10.1016/j.trd.2025.104885">Electric or Gasoline Vehicle? Determinants of Vehicle Ownership in 247 Chinese Cities</a></div>
      <div class="path-venue">Transportation Research Part D: Transport and Environment, 2025</div>
      <div class="pub-labels"><span class="pub-label">Electric vehicles</span><span class="pub-label">Vehicle ownership</span></div></li>
    <li><div class="path-title"><a href="https://doi.org/10.1016/j.tbs.2024.100773">How Temporary Disruption of Metro Service Influences Metro Commuters’ Mode Shifts during the COVID-19 Pandemic: Evidence from Tianjin, China</a></div>
      <div class="path-venue">Travel Behaviour and Society, 2024</div>
      <div class="pub-labels"><span class="pub-label">COVID-19</span><span class="pub-label">Public transit</span><span class="pub-label">Mode shift</span></div></li>
    <li><div class="path-title"><a href="https://doi.org/10.1016/j.cities.2023.104341">Non-Commuting Intentions during COVID-19 in Nanjing, China: A Hybrid Latent Class Modeling Approach</a></div>
      <div class="path-venue">Cities, 2023</div>
      <div class="pub-labels"><span class="pub-label">COVID-19</span><span class="pub-label">Latent class model</span><span class="pub-label">Travel intentions</span></div></li>
    <li class="first-author"><div class="path-title"><a href="https://doi.org/10.1016/j.scs.2022.103967">Geographically Weighted Multinomial Logit Models for Modelling the Spatial Heterogeneity in the Bike-Sharing Renting-Returning Imbalance: A Case Study on Nanjing, China</a></div>
      <div class="path-venue">Sustainable Cities and Society, 2022</div>
      <div class="pub-labels"><span class="pub-label">Bike-sharing</span><span class="pub-label">Discrete choice</span><span class="pub-label">Spatial heterogeneity</span></div></li>
    <li><div class="path-title"><a href="https://doi.org/10.3390/app12031161">Short-Term Prediction of Bike-Sharing Demand Using Multi-Source Data: A Spatial-Temporal Graph Attentional LSTM Approach</a></div>
      <div class="path-venue">Applied Sciences, 2022</div>
      <div class="pub-labels"><span class="pub-label">Bike-sharing</span><span class="pub-label">Demand prediction</span><span class="pub-label">Graph neural networks</span></div></li>
    <li class="first-author"><div class="path-title">Understanding the Difference in Regularity of Bike-Sharing Usage between Docked and Dockless Systems</div>
      <div class="path-venue">Transportation Research Board (TRB) Annual Meeting, 2020</div>
      <div class="pub-labels"><span class="pub-label">Bike-sharing</span><span class="pub-label">Usage regularity</span></div></li>
    <li><div class="path-title"><a href="https://doi.org/10.3390/su10113949">Modeling the Factors Influencing the Activity Spaces of Bikeshare around Metro Stations: A Spatial Regression Model</a></div>
      <div class="path-venue">Sustainability, 2018</div>
      <div class="pub-labels"><span class="pub-label">Bike-sharing</span><span class="pub-label">Spatial regression</span><span class="pub-label">Metro integration</span></div></li>
    <li><div class="path-title"><a href="https://doi.org/10.3390/info9110289">Measuring Bikeshare Access/Egress Transferring Distance and Catchment Area around Metro Stations from Smartcard Data</a></div>
      <div class="path-venue">Information, 2018</div>
      <div class="pub-labels"><span class="pub-label">Bike-sharing</span><span class="pub-label">Smartcard data</span><span class="pub-label">Catchment area</span></div></li>
  </ul>
</div>

</div>
