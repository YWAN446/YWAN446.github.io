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
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/WWS_Figure1.jpg' | relative_url }}" alt="" title="Adaptive Sampling Allocation"/>
    </div>
</div>
<div class="caption">
    Heatmaps of sampling site distributions along with the update process given lambda=40 new shedders per day. The heatmap has two layers: the base layer has the hypothetical sewerage network and toilets. The red dots represent the shared toilets, and the size of a red dot represents the probability of a *S.* Typhi shedder defecating at this toilet. The second layer shows the contours of sampling sites distribution in blue. The contours of sampling sites will change with update process and over time will move to the geographic locations with the most shedders.
</div>

The results are summarized as a decision tree to guide the sampling strategy based on disease incidence, geographic distribution of risk, pathogen loss, and the sensitivity of the detection assay. The adaptive sampling site allocation method consistently outperformed alternatives with fixed site locations in most scenarios. In some cases, the optimum allocation method increased the median sensitivity from 45% to 90% within 20 updates.

## Part 2
### *Designing a Multilevel COVID-19 Wastewater Surveillance Study in Atlanta*

Monitoring SARS-CoV-2 in wastewater is a valuable approach to track COVID-19 transmission. Designing wastewater surveillance (WWS) with representative sampling sites and quantifiable results requires knowledge of the sewerage system and virus fate and transport. We developed a multi-level WWS system to track COVID-19 in Atlanta using an adaptive nested sampling strategy. From March 2021 to April 2022, 868 wastewater samples were collected from influent lines to wastewater treatment facilities and upstream community manholes. Variations in SARS-CoV-2 concentrations in influent line samples preceded similar variations in numbers of reported COVID-19 cases in the corresponding catchment areas. Community sites under nested sampling represented mutually-exclusive catchment areas. Community sites with high SARS-CoV-2 detection rates in wastewater covered high COVID-19 incidence areas, and adaptive sampling enabled identification and tracing of COVID-19 hotspots. This study demonstrates how a well-designed WWS provides actionable information including early warning of surges in cases and identification of disease hotspots.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/WWS_Atl_Fig1.jpg' | relative_url }}" alt="" title="Illustration of Adaptive Sampling Allocation"/>
    </div>
</div>
<div class="caption">
    The top plot shows the catchment areas of each community site nested within the overall catchment of the influent line site (in gray). The black lines represent the sewer network lines. The bottom plots shows the heatmap of reported COVID-19 cases between September 1st 2021–May 8th 2022 within the influent catchment area.
</div>
