---
layout: distill
title: How to Make Good Figures for Scientific Papers
description: A guide on tools, styles, and purposes of figures in research papers, with concrete examples and references.
tags: figures visualization research paper
giscus_comments: true
date: 2025-08-17
featured: false
zoomable: true
chart:
  chartjs: true
  echarts: true
  vega_lite: true
tikzjax: true
typograms: true
authors:
  - name: Chengshuai Zhao
    url: "https://chengshuaizhao0.github.io/"
    affiliations:
      name: Arizona State University
bibliography: posts.bib

toc:
  - name: Introduction
  - name: Choosing the Right Tool
    subsections:
      - name: MS PowerPoint & Excel
      - name: Draw.io
      - name: MS Visio
      - name: Python
  - name: Style and Design
    subsections:
      - name: Using Color Effectively
      - name: Learning from Conference Styles
  - name: Purpose-Driven Figures
    subsections:
      - name: Illustration / Teaser Figures
      - name: Framework Figures
      - name: Results Figures
  - name: Takeaways

---

## Introduction

Good figures are often described as *the icing on the cake* of a research paper. They do more than just decorate — they illustrate, persuade, and clarify. Well-designed visuals can transform a dense idea into an accessible insight, guiding readers through your contributions with clarity and impact:

This article provides practical guidance on **tools**, **styles**, and **purposes** for creating strong figures, enriched with lessons learned from top conferences and recent publications.

---

## Choosing the Right Tool

Different tools serve different figure-making needs. Here we compare four popular ones:

### MS PowerPoint & Excel

MS [PowerPoint](https://powerpoint.cloud.microsoft/) and [Excel](https://excel.cloud.microsoft/) are intuitive and widely accessible. Their **GUI-based design**, built-in templates, and auto-alignment features make them great for beginners. However, they suffer from **limited graphic styles** and possible quality loss when exporting to other formats.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/excel.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/ppt.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Example created using MS PowerPoint & Excel <d-cite key="ting2025beyond"></d-cite>
</div>
---

### Draw.io

[Draw.io](https://www.drawio.com/) shines in **online collaboration** and vector output (SVG, PDF) with auto-cropping. It is especially useful for collaborative diagramming. The trade-off is **manual styling** and limited shape libraries.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/drawio.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Illustration made with Draw.io <d-cite key="zhao2025chain"></d-cite>
</div>
---

### MS Visio

MS [Visio](https://visio.cloud.microsoft/) supports **pixel-level manipulation**, professional diagramming, and math notations with **vector output**. It is excellent for technical diagrams but requires manual styling and comes as paid software.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/visio.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Technical diagram in MS Visio <d-cite key="zhao2021csgnn"></d-cite>
</div>
---

### Python

Python libraries (e.g., [Matplotlib](https://matplotlib.org/stable/tutorials/pyplot.html), [Seaborn](https://seaborn.pydata.org/)) enable **automatic alignment** and high-quality vector outputs. However, editing details post-generation is more challenging.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/python1.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/python2.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Data visualization with Python libraries <d-cite key="zhao2021csgnn"></d-cite>
</div>
---

## Style and Design

### Using Color Effectively

Colors can amplify clarity — but only if used carefully.  

- Leverage **default palettes** from tools like Seaborn or Draw.io.  
- Avoid cluttering a single figure with too many colors.  
- Study effective visual styles from top venues like *Nature* and premier conferences.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/color1.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/color2.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Default colors used in seaborn and draw.io <d-cite key="zhao2025cyberbot"></d-cite>
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/learn1.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/learn2.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
	<div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/learn3.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Color choices inspired by top conferences <d-cite key="zhao2025cyberbot"></d-cite>
</div>

---

### Learning from Conference Styles

Different research communities emphasize distinct figure styles:

- **Data Mining Conferences** → detailed, modularized structures.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/dm.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Data mining style visualization <d-cite key='tan2022graph'></d-cite>
</div>
- **Machine Learning Conferences** → abstract and minimal visuals.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/ml.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Minimalist ML figure style <d-cite key='xia2023mole'></d-cite>
</div>
- **NLP Conferences** → concept-driven, flow-based designs.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/nlp.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Concept-driven NLP figure <d-cite key='li2025preference'></d-cite>
</div>
---

## Purpose-Driven Figures

Figures should align with their intended role in the paper.

### Illustration / Teaser Figures

A **teaser figure** should succinctly state the problem and present it simply. Avoid overloading details; its purpose is to catch attention and clarify motivation.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/illustration1.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/illustration2.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Example teaser figure <d-cite key="tan2024wolf"></d-cite>
</div>
---

### Framework Figures

Framework figures should be **self-explanatory** and highlight **novel contributions**. They serve as a visual “blueprint” of your approach.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/framework.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Framework illustration <d-cite key="tan2024glue"></d-cite>
</div>
---

### Results Figures

Result-oriented figures should directly support **analysis or conclusions**. Every curve, bar, or scatter point must reinforce your argument.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/result1.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/result2.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/blog/2025-08-17-figures-for-papers/result3.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Result comparison figure <d-cite key="zhao2025chain"></d-cite>
</div>
---

## Takeaways

1. **Good figures are the icing on the cake** — they elevate the quality of your paper. 
2. **Choose tools** that best fit your workflow and needs.  
3. **Learn from good examples**, especially from leading conferences.  
4. **Keep figures self-explanatory**, ensuring they clearly support your narrative.

---