# DustSCAN
The DustSCAN repository contains the source code used in our recent paper for analyzing dust plumes. This code facilitates the identification and characterization of dust plumes using hourly images from SEVIRI on Meteosat satellites. 

<img src="https://github.com/faisalalnasser13/DustSCAN/assets/100229605/57ca6eb0-003f-4e50-906e-12cf90a4bde0" width="410" height="300"> <img src="https://github.com/faisalalnasser13/DustSCAN/assets/100229605/574e5b5d-d16a-4167-9db2-e13e9bd2f42e" width="300" height="300">

Key functionalities include:
- DBSCAN Clustering: Applies the DBSCAN algorithm for clustering dust-affected pixels into plumes.
- Plume Property Analysis: Extracts properties like source area, centroid, coverage, extent, duration, and contribution.
- Dataset Integration: Integrates additional datasets like soil moisture, vegetation index, and wind vectors for comprehensive analysis.
- Validation Tools: Features validation tools as detailed in the paper, ensuring accuracy in plume tracking.
