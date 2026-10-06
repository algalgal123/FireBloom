# Spatiotemporal Dynamics of Wildfire on Cyanobacterial Harmful Algal Blooms Proliferation

## Project Overview
This repository contains the data science pipelines, computational workflows, and open-source data artifacts developed to assess the impacts of wildfire inputs on cyanobacterial harmful algal bloom (cyanoHAB) dynamics across California lakes. 

By integrating remote sensing, cloud computing, and big data architectures, this project introduces the concept of **FireBlooms**—wildfire-fueled cyanobacterial events driven by pyroallochthonous watershed inputs. We identify critical spatiotemporal thresholds, finding that lakes within 10 km of wildfire perimeters experience elevated bloom occurrence within a 3-month post-fire lag, while lakes within 6 km exhibit significant increases in turbidity.

## Core Technical Stack
* **Languages:** Python, R
* **Cloud Computing & Remote Sensing:** Google Earth Engine (GEE), PlanetScope High-Resolution Satellite Imagery
* **Big Data & HPC Orchestration:** `xarray`, `dask` (benchmarked and profiled on Stanford's Sherlock HPC Cluster)
* **Geospatial & Statistical Analysis:** ArcGIS, Spatiotemporal Correlative Inference

## Data Product & Artifacts
This repository serves as an open-source framework for environmental data tracking. It includes:
* **Satellite Processing Pipelines:** Scripts to ingest and harmonize multi-source remote sensing imagery.
* **Spatiotemporal Core Dataset:** The engineered dataset linking California wildfire perimeters, lag metrics, lake proximity parameters, and corresponding cyanoHAB/turbidity tracking.

## Citation / Abstract
> **Abstract:** Cyanobacterial harmful algal blooms (cyanoHABs) are increasing worldwide in both frequency and duration, posing growing threats to water quality and ecosystem health. At the same time, wildfires are becoming more frequent and intense, yet their role in promoting cyanoHABs remains poorly understood. Here we combine data derived from remote sensing, geospatial analysis, and statistical modeling to assess whether wildfires influence cyanoHAB dynamics in lakes across California. We find that lakes within 10 km of wildfire perimeters exhibit elevated bloom occurrence within three months following fire, while lakes within 6 km show significant increases in turbidity. We define these wildfire-fueled cyanobacterial events as FireBlooms, where fire-driven watershed inputs promote bloom formation. The transport of fire-derived material from burned watersheds into lakes, for which we use the term pyroallochthonous inputs, leads to browning, nutrient enrichment, and reduced light penetration. Our results reveal that wildfire proximity and postfire lag are critical predictors of cyanoHAB risk, highlighting a previously underappreciated link between terrestrial disturbance and aquatic ecosystem response. These findings underscore the vulnerability of lakes to compounding climate-driven stressors and provide a framework for anticipating wildfire-related water quality degradation in fire-prone regions.
