---
layout: page
title: Wastewater Surveillance
description: a project of wastewater surveillance for pathogens (i.e., SARS-CoV-2, S. Typhi)
img: /assets/img/WWS_img_001.jpg
importance: 1
category: work
---

## Part 1
### *Designing a Typhoid Environmental Surveillance Study: A Simulation Model for Optimum Sampling Site Allocation*

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/WWS_Figure2.jpg' | relative_url }}" alt="" title="SaniPath Conceptual Diagram"/>
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/WWS_Figure3.jpg' | relative_url }}" alt="" title="Fecal Microbes Transfer Network"/>
    </div>
</div>
<div class="caption">
    Diagram of feces flow from toilets to pumping station through the underground sewerage network (left) and Life-cycle diagram of S. Typhi in the sewerage system including: the generation of shedders, the assignment of shedders to shared toilets that are connected to the hypothetical sewerage network, the amount of S. Typhi shed that enters and exits the sewerage system (right).
</div>

Environmental surveillance can be used for monitoring enteric disease in a population by detecting pathogens, shed by infected people, in sewage. Detection of pathogens depends on many factors: infection rates and shedding in the population, pathogen fate in the sewerage network, and also sampling sites, sample size, and assay sensitivity. This complexity makes the design of sampling strategies challenging, which creates a need for mathematical modeling to guide decision making.

In the present study, a model was developed to simulate pathogen shedding, pathogen transport and fate in the sewerage network, sewage sampling, and detection of the pathogen. The simulation study used Salmonella enterica serovar Typhi (S. Typhi) as the target pathogen and two wards in Kolkata, India as the study area. Five different sampling strategies were evaluated for their sensitivity of detecting S. Typhi, by sampling unit: sewage pumping station, shared toilet, adjacent multiple shared toilets (primary sampling unit), pumping station + shared toilets, pumping station + primary sampling units. Sampling strategies were studied in eight scenarios with different geographic clustering of risk, pathogen loss (decay, leakage), and sensitivity of detection assays. A novel adaptive sampling site allocation method was designed, that updates the locations of sampling sites based on their performance. We then demonstrated how the simulation model can be used to predict the performance of environmental surveillance and how it is improved by optimizing the allocation of sampling sites.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/WWS_Figure1.jpeg' | relative_url }}" alt="" title="Adaptive Sampling Allocation"/>
    </div>
</div>
<div class="caption">
    Heatmaps of sampling site distributions along with the update process given lambda=40 new shedders per day. The heatmap has two layers: the base layer has the hypothetical sewerage network and toilets. The red dots represent the shared toilets, and the size of a red dot represents the probability of a *S.* Typhi shedder defecating at this toilet. The second layer shows the contours of sampling sites distribution in blue. The contours of sampling sites will change with update process and over time will move to the geographic locations with the most shedders.
</div>

The results are summarized as a decision tree to guide the sampling strategy based on disease incidence, geographic distribution of risk, pathogen loss, and the sensitivity of the detection assay. The adaptive sampling site allocation method consistently outperformed alternatives with fixed site locations in most scenarios. In some cases, the optimum allocation method increased the median sensitivity from 45% to 90% within 20 updates.
