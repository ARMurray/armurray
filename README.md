### Andrew Murray

Geographer (PhD) working in applied geospatial machine learning. I build
national-scale geospatial data products — models that run across the entire
United States, are validated against ground truth, and ship as datasets people
rely on. My work combines aerial and satellite imagery, spatial data
engineering, and machine learning to map physical infrastructure and
environmental exposure that existing data misses.

**Core stack:** Python (PyTorch, Ultralytics/YOLO, GeoPandas, rasterio) ·
R (tidymodels, sf, terra) · H3 spatial indexing · GeoParquet / DuckDB ·
object detection on aerial & satellite imagery · Docker / CI.

#### Featured work

- **[wastewater-plant-location-correction](https://github.com/ARMurray/wastewater-plant-location-correction)**
  — Correcting wrong facility coordinates nationwide by pairing a **YOLOv8**
  object detector on NAIP aerial imagery with a two-stage geospatial ML pipeline
  (H3 candidate generation, tidymodels). *PyTorch · Ultralytics · H3 · sf/terra ·
  GeoParquet.*
- **[USEPA/sewersheds](https://github.com/USEPA/sewersheds)** — Led/architected
  (org-hosted). National map of U.S. sewersheds: **XGBoost on H3 hexagons** with a
  custom OpenStreetMap road-routing algorithm — a released EPA data product with a
  public web map (17,000+ sewersheds).
- **[USEPA/ORD_SAB_Model](https://github.com/USEPA/ORD_SAB_Model)** —
  Led/architected (org-hosted). National **random-forest** model delineating
  drinking-water service-area boundaries for every U.S. community water system — a
  released EPA data product. *tidymodels · sf · terra.*
- **[DomesticWells](https://github.com/ARMurray/DomesticWells)** — Reproducible
  national estimate of private domestic-well locations from three decades of
  Census data (Murray et al., 2020). *sf · raster · multi-vintage boundary
  harmonization.*
