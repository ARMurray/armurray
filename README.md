### Andrew Murray

PhD geographer turned applied geospatial machine-learning engineer. I build
**national-scale, production geospatial data products** — the kind where a model
has to run over every place in the country, be validated, and hold up to
scrutiny. My work fuses **remote-sensing imagery, spatial data engineering, and
machine learning** to map physical infrastructure and environmental exposure
that isn't otherwise on any map. I care about methods that are reproducible,
cross-validated, and defensible — not just results that look good once.

**Core stack:** Python (PyTorch, Ultralytics/YOLO, GeoPandas, rasterio) · R
(tidymodels, sf, terra) · H3 spatial indexing · GeoParquet/DuckDB · object
detection on satellite & aerial imagery · Docker/CI.

#### Featured work

- **[wastewater-plant-location-correction](https://github.com/ARMurray/wastewater-plant-location-correction)**
  — Correcting wrong facility coordinates at national scale by combining a
  **YOLOv8 object detector** on NAIP aerial imagery with a two-stage geospatial
  ML pipeline (H3 candidate generation, tidymodels). PyTorch · Ultralytics · H3 ·
  sf/terra · GeoParquet.
- **[USEPA/sewersheds](https://github.com/USEPA/sewersheds)** — Led/architected,
  org-hosted. National map of U.S. sewersheds: **XGBoost on H3 hexagons** with a
  custom OSM road-routing algorithm; a released EPA data product with a public
  web map (17,000+ sewersheds).
- **[DomesticWells](https://github.com/ARMurray/DomesticWells)** — Reproducible
  national estimate of private domestic-well locations from three decades of
  Census data (published as Murray et al., 2020). sf · raster · multi-vintage
  boundary harmonization.
