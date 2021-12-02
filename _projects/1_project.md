---
layout: page
title: SaniPath
description: a project to access the risk of exposure to fecal contamination through multiple environmental pathways in urban communities
img: /assets/img/SP_img_001.jpg
importance: 1
category: work
---

## Phase 1
### Development of SaniPath Exposure Accessment Approach in Accra, Ghana

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/SP_Figure1.png' | relative_url }}" alt="" title="SaniPath Conceptual Diagram"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/SP_Figure2.png' | relative_url }}" alt="" title="Fecal Microbes Transfer Network"/>
    </div>
</div>
<div class="caption">
    SaniPath exposure assessment conceptual diagram (left) and illustration of a fecal microbes transfer network (right).
</div>

Unsafe fecal sludge management results in widely distributed fecal contamination in the urban environment and poses a risk of disease transmission via multiple exposure pathways. To better understand how different environmental sources contribute to overall exposure to fecal contamination, we quantified exposure through multiple pathways for children under 5 years old in four high-density, low-income, urban neighborhoods in Accra, Ghana. We collected more than 500 hours of structured observation of behaviors of 156 children, 800 household surveys, and 1,855 environmental samples. Data were analyzed using Bayesian models, estimating the environmental and behavioral factors associated with exposure to fecal contamination. These estimates were applied in exposure models simulating sequences of behaviors and transfers of fecal indicators. This approach allows us to identify the contribution of any sources of fecal contamination in the environment to child exposure and use dynamic fecal microbe transfer networks to track fecal indicators from the environment to oral ingestion. The contributions of different sources to exposure were categorized into four types (high/low by dose and frequency), as a basis for ranking pathways by the potential to reduce exposure. Although we observed variation in estimated exposure ($10^8–10^{16}$ CFU/day for *Escherichia* coli) between different age groups and neighborhoods, the greatest contribution was consistently from food (contributing > 99.9\% to total exposure). Hands played a pivotal role in fecal microbe transfer, linking environmental sources to oral ingestion. The fecal microbe transfer network constructed here provides a systematic approach to study the complex interaction between contaminated environment and human behavior on exposure to fecal contamination.

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/1.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/3.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
```
