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
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=planning]* %}

<h2 class="pub-topic">Travel Behavior and Demand Modeling</h2>
<p class="pub-topic-desc">What drives travelers’ choices regarding transport modes, vehicles, and services, and how do these preferences vary geographically, evolve over time, and adapt to system disruptions?</p>
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[topic=behavior]* %}

</div>
