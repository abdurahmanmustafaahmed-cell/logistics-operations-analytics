# Logistics & Operations Excellence Analytics Portfolio

This repository contains data-driven optimization projects designed to improve throughput, ensure SLA compliance, and refine warehouse strategy within fast-paced fulfillment environments.

## Project 1: E-Commerce Last-Mile SLA & TAT Optimization

* **Objective:** Analyze order life cycle logs to identify bottlenecks preventing 2-hour on-demand fulfillment targets.
* **Tools Used:** Google Sheets, Tableau Public
* **Tableau Dashboard:** [View Live Interactive Dashboard](https://public.tableau.com/views/E-CommerceLast-MileSLABottleneckAnalysis/Sheet1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
* **Presentation Deck:** [View Google Slides Presentation](https://docs.google.com/presentation/d/1wwZTV_29Np1cm7MPTZhTTiGLmwPrLvagk6ZMfX3W4ZM/edit?usp=sharing)
* **Key Finding:** Identified that the processing bottleneck resided heavily within the Order Packing phase (averaging 55 mins) rather than the transit networks.
* **Outcome:** Formulated layout optimization strategies to drop packing times, returning SLA compliance to target baselines.

## Project 2: Warehouse Slotting Strategy via ABC Velocity Analysis

* **Objective:** Minimize picking travel distances by re-allocating SKUs based on order velocity metrics.
* **Tools Used:** Python (Data modeling, Cumulative distribution logic)
* **Key Finding:** Class A items represented 78% of warehouse movements but were scattered randomly across remote aisles.
* **Outcome:** Proposed a structured slotting configuration keeping high-velocity SKUs nearest to packing areas, cutting travel times significantly.
