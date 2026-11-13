# flood-sense


1. Project overview and research framing
FloodSense Africa is a geospatial AI project designed to investigate flood susceptibility and map observed flood extent using open Earth-observation, terrain, rainfall and water-observation datasets. The initial case study is Greater Banjul, The Gambia.
Project aim
Build a reproducible geospatial data pipeline and evaluate machine-learning and deep-learning methods for (a) identifying locations with higher relative flood susceptibility and (b) delineating observed floodwater in selected satellite-observed events where suitable reference labels exist.
Why this is a strong flagship project
It combines applied machine learning with geospatial data engineering, remote sensing, climate-related risk and a real West African study area.
It demonstrates end-to-end engineering: data ingestion, geospatial processing, model training, evaluation, API design, dashboard delivery and reproducibility.
It creates a credible path to a technical report or research paper, provided the data and validation support defensible conclusions.
Research questions
Which terrain, hydrological, land-cover, rainfall and historical-water indicators are associated with mapped flood susceptibility in the Greater Banjul study area?
How do interpretable statistical baselines compare with tree-based machine-learning models under spatially separated validation?
Can Sentinel-1 SAR imagery support event-based flood extent segmentation for selected events with defensible reference masks?
How well do the models generalise to geographically distinct areas or separate flood events?
How can uncertainty, data limitations and model outputs be communicated through a usable geospatial application?
Intended outputs
A documented Greater Banjul geospatial dataset and reproducible processing pipeline.
A susceptibility model with spatial validation and interpretable feature analysis.
An event-based flood extent segmentation experiment, if adequate imagery and labels can be assembled.
A FastAPI backend, PostGIS-backed data service and Nuxt/Vue map dashboard.
A model card, data card, technical report and public GitHub repository.
