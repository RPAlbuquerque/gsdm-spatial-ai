## 💫 About GSDM:


The GeoSocial Downscaling Model (GSDM) is a Spatial AI research project that reconstructs fine-scale urban accessibility patterns from coarse-grained mobility data. The project develops physics-guided deep learning methods that enable high-resolution (~500 m) accessibility estimation while preserving macro-level consistency constraints.

GSDM is designed to support research and decision-making in urban resilience, environmental justice, and equitable service provision. The project emphasizes open science, FAIR data principles, and reproducible Spatial AI workflows, and is developed as part of the Spatial AI Challenge 2025–26, hosted on the I-GUIDE Platform.

All experiments are executed on GPU-enabled cloud infrastructure (Jetstream2), and the full modeling pipeline is openly documented and containerized.
_____________________________________________________


## 📈 Projects:


GeoSocial Downscaling of Urban Mobility

A Spatial AI Framework for High-Resolution Service Accessibility

This project introduces a physics-guided U-Net architecture that downscales aggregated mobility flows into fine-grained accessibility surfaces while enforcing macro–micro consistency. The framework integrates national mobility indicators with socioeconomic and built-environment covariates, without relying on social media or individual behavioral traces.


Key outputs include:

· High-resolution accessibility surfaces (~100 m)

· Validated downscaling pipelines

· Containerized and GPU-ready workflows

· Pre-trained models and configuration files

· A Spatial AI Model Card with ethical and methodological documentation


The initial case study focuses on São Paulo, Brazil, but the framework is designed for transferability across urban contexts.
__________________________________________________________


## 💻 Tech Stack:


Python · Jupyter · PyTorch · TensorFlow · NumPy · Pandas · SciPy · Plotly ·

GeoPandas · Rasterio · Xarray · NetCDF ·

Docker · Singularity · YAML · Shell Script ·

U-Net · Physics-Guided Neural Networks ·

Jetstream2 · I-GUIDE Platform · GPU Computing ·

Git · GitHub · GitHub Actions · FAIR Workflows
___________________________


## 📊 Core Pipelines:


The GSDM workflow is organized into four modular pipelines implemented as Jupyter notebooks:

· Pipeline A — Mobility Processing

Aggregation, normalization, and preparation of national-scale mobility data.


· Pipeline S — Spatial Integration

Integration of mobility data with socioeconomic and built-environment covariates.


· Pipeline V — Validation

Aggregate consistency checks, distributional fidelity analysis, and spatial error diagnostics.


· Pipeline D — Downscaling

Physics-guided U-Net implementation for high-resolution accessibility estimation.


These pipelines define the complete Spatial AI workflow from raw data to validated outputs.
_____________________________________


## 👩‍🚀 Team Members

| Picture | Name | Role | Institution |
|--------|------|------|-------------|
| <img src="assets/team/Wang.jpg" width="80"/> | **Siqin Wang** | Lead Researcher & PI | University of Southern California |
| <img src="assets/team/Miranda.jpg" width="80"/> | **Jessica Miranda** | Researcher | Federal University of Rio Grande do Sul |
| <img src="assets/team/Albuquerque.jpeg" width="80"/> | **Rafael Albuquerque** | Researcher | Federal University of Rio Grande do Sul |
| <img src="assets/team/Brei.jpg" width="80"/> | **Vinicius Brei** | Principal Investigator | Federal University of Rio Grande do Sul |

____________________________________________


## 🏢 Support & Infrastructure


This project is developed and executed using resources provided by:

I-GUIDE Platform

Jetstream2 Cloud Infrastructure

Federal University of Rio Grande do Sul (UFRGS)

University of Southern California
______________________________________

📄 License:

This project is released under the MIT License.
______________________________________


📚 Citation:

Citation information is available in the CITATION.cff file.

If you use this project, please cite accordingly.
