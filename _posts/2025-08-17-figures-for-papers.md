---
layout: distill
title: How to Make Good Figures for Scientific Papers
description: A guide on tools, styles, and purposes of figures in research papers, with concrete examples and references.
tags: distill figures visualization research
giscus_comments: true
date: 2025-08-17
featured: true
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

Good figures are often described as *the icing on the cake* of a research paper. They do more than just decorate — they illustrate, persuade, and clarify. Well-designed visuals can transform a dense idea into an accessible insight, guiding readers through your contributions with clarity and impact:contentReference[oaicite:0]{index=0}.

This article provides practical guidance on **tools**, **styles**, and **purposes** for creating strong figures, enriched with lessons learned from top conferences and recent publications.

---

## Choosing the Right Tool

Different tools serve different figure-making needs. Here we compare four popular ones:

### MS PowerPoint & Excel
PowerPoint and Excel are intuitive and widely accessible. Their **GUI-based design**, built-in templates, and auto-alignment features make them great for beginners. However, they suffer from **limited graphic styles** and possible quality loss when exporting to other formats:contentReference[oaicite:1]{index=1}.  
<d-cite key="ting2025beyond"></d-cite>

---

### Draw.io
Draw.io shines in **online collaboration** and vector output (SVG, PDF) with auto-cropping. It is especially useful for collaborative diagramming. The trade-off is **manual styling** and limited shape libraries:contentReference[oaicite:2]{index=2}.  
<d-cite key="zhao2025chain"></d-cite>

---

### MS Visio
Visio supports **pixel-level manipulation**, professional diagramming, and math notations with **vector output**. It is excellent for technical diagrams but requires manual styling and comes as paid software:contentReference[oaicite:3]{index=3}.  
<d-cite key="zhao2021csgnn"></d-cite>

---

### Python
Python libraries (e.g., Matplotlib, Seaborn) enable **automatic alignment** and high-quality vector outputs. However, editing details post-generation is more challenging:contentReference[oaicite:4]{index=4}.  
<d-cite key="zhao2021csgnn"></d-cite>

---

## Style and Design

### Using Color Effectively
Colors can amplify clarity — but only if used carefully.  
- Leverage **default palettes** from tools like Seaborn or Draw.io.  
- Avoid cluttering a single figure with too many colors.  
- Study effective visual styles from top venues like *Nature* and premier conferences:contentReference[oaicite:5]{index=5}.  
<d-cite key="zhao2025cyberbot"></d-cite>

---

### Learning from Conference Styles
Different research communities emphasize distinct figure styles:

- **Data Mining Conferences** → detailed, modularized structures:contentReference[oaicite:6]{index=6}.  
  <d-cite key="tan2022graph"></d-cite>  

- **Machine Learning Conferences** → abstract and minimal visuals:contentReference[oaicite:7]{index=7}.  
  <d-cite key="xia2023mole"></d-cite>  

- **NLP Conferences** → concept-driven, flow-based designs:contentReference[oaicite:8]{index=8}.  
  <d-cite key="li2025preference"></d-cite>  

---

## Purpose-Driven Figures

Figures should align with their intended role in the paper.

### Illustration / Teaser Figures
A **teaser figure** should succinctly state the problem and present it simply. Avoid overloading details; its purpose is to catch attention and clarify motivation:contentReference[oaicite:9]{index=9}.  
<d-cite key="tan2024wolf"></d-cite>

---

### Framework Figures
Framework figures should be **self-explanatory** and highlight **novel contributions**. They serve as a visual “blueprint” of your approach:contentReference[oaicite:10]{index=10}.  
<d-cite key="tan2024glue"></d-cite>

---

### Results Figures
Result-oriented figures should directly support **analysis or conclusions**. Every curve, bar, or scatter point must reinforce your argument:contentReference[oaicite:11]{index=11}.  
<d-cite key="*zhao2025chain*"></d-cite>

---

## Takeaways

1. **Good figures are the icing on the cake** — they elevate the quality of your paper.  
2. **Choose tools** that best fit your workflow and needs.  
3. **Learn from good examples**, especially from leading conferences.  
4. **Keep figures self-explanatory**, ensuring they clearly support your narrative:contentReference[oaicite:12]{index=12}.

---