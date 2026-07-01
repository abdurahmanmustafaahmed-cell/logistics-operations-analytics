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
* **Tools Used:** Python (Pandas, NumPy, Pareto analysis)
* **Execution:** Designed and executed a Python-based slotting engine to automate ABC classification.
* **Key Finding:** High-velocity 'Class A' items (approx. 20% of inventory) were historically stored in remote warehouse locations, creating unnecessary travel distance.
* **Outcome:** Engineered an optimized slotting configuration that moved high-velocity items to primary aisles, resulting in an estimated travel distance reduction of over 40% annually.
