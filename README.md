# Hi, I'm Aisun 👋

**Scientific Python | Geospatial Engineering | Reproducible AI Evaluation**

I build Python-based workflows for scientific and geospatial data processing, with a focus on numerical correctness, reproducibility, data quality, and automated testing.

My current interests include **Earth-science coding benchmarks, scientific AI evaluation, spatial analysis, and reliable research software**.

## 🌍 Featured Project — GeoClimateBench

**[Explore GeoClimateBench's validated benchmark suite](https://github.com/AisunZa/GeoClimateBench/tree/feature/harbor-agent-evaluation)** | **[Verified GitHub Actions run](https://github.com/AisunZa/GeoClimateBench/actions/runs/39966344276)**

GeoClimateBench is an open-source scientific Python portfolio project for developing and evaluating terminal-based Earth-science coding tasks.

It includes three reproducible Harbor benchmarks:

| Scientific task | Core challenge |
|---|---|
| Daily Temperature QC | Physical units, missing data, UTC timestamps, and sampled daily maxima |
| Heatwave P90 | Historical climatology, percentile thresholds, and consecutive extreme-temperature events |
| Station–Grid Validation | Haversine matching, observation exclusions, and numerical error statistics |

**Verification highlights:**
- All three Harbor benchmarks passed Oracle (`1.0`) and Nop (`0.0`) controls.
- Independent numerical verifiers and Docker-separated execution environments.
- 17 successful fault-injection controls across the first two benchmarks.
- 30 additional scientific regression controls for station–grid validation.
- 32 passing tests in the original scientific regression suite.
- Successful GitHub Actions scientific verification workflow.

**Tools:** Python, NumPy, pandas, SciPy, xarray, NetCDF, pytest, Docker, Harbor, Git, and GitHub Actions.

**Scientific scope:** The offline benchmarks use synthetic data. A separate exploratory case study compares ERA5-Land temperatures with DWD station observations for Berlin-Tempelhof in July 2022. Synthetic benchmark results are not presented as proof of real-world forecast accuracy.

## 🗺️ Other Selected Projects

### [GeoAsset Intelligence Platform](https://github.com/AisunZa/geoasset-intelligence-platform)

Geospatial infrastructure-risk and maintenance analysis using Python, QGIS/PyQGIS, GeoPandas, PostGIS, FastAPI, Docker, and automated testing.

### [GeoDiff CI](https://github.com/AisunZa/geodiff-ci)

A geospatial regression-testing tool for detecting changes in geometry validity, coordinate reference systems, schemas, feature counts, and spatial coverage.

My broader work also includes computer vision, image analysis, and Python backend development.

## 🔬 Engineering Interests

- Scientific programming and numerical verification
- Earth-science and environmental data processing
- AI coding-task development and evaluation
- Geospatial analysis and data quality control
- Reproducible computational workflows
- Automated testing and continuous integration

I aim to make computational results **explainable, testable, and reproducible**, with explicit assumptions and honest reporting of limitations.

## 🤝 Collaboration

I'm interested in opportunities involving scientific Python, Earth-science AI evaluation, geospatial engineering, and research software.

Explore my [repositories](https://github.com/AisunZa?tab=repositories) to see the source code, documentation, tests, and project examples.
