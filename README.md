# GeoPulse-Hyper-Local-Retail-Mobility-Analytics

## 📋 Executive Summary
GeoPulse is an enterprise-grade geospatial data lakehouse and visualization engine designed to eliminate guesswork in multi-million dollar retail site selection. By transforming massive streams of raw, anonymized mobile GPS data into dynamic foot-traffic mobility insights, GeoPulse empowers real estate strategists to optimize expansion plans and mitigate revenue cannibalization between existing and proposed store locations.

# TASK I
## 🎯 Aim of the Project

- **Scale Spatial Ingestion & Storage**: Build a robust Geospatial Data Lakehouse in Snowflake capable of ingesting massive arrays of coordinate data using native GEOGRAPHY data types.

- **Execute Distributed Spatial Joins**: Leverage Apache Sedona and PySpark to process heavy spatial intersections between millions of mobile GPS points and multi-polygon store catchment boundaries without memory bottlenecks.

- **Automate Modular ELT Workflows**: Configure dbt to cleanse spatial joins, track unique DeviceID trajectories over time, and aggregate hourly footfall metrics and multi-store cross-visitation patterns.

- **Prevent Store Cannibalization**: Model device movement history to accurately calculate traffic diversion rates between existing locations and proposed sites (e.g., quantifying morning commuter overlap).

- **Deliver Immersive 3D Spatial BI**: Embed Kepler.gl into a React application to render dynamic 3D H3 hexagons, movement arcs, and time-scrubbed footfall heatmaps that drive executive real estate decisions.
