# From Mobility Intensity to Market Infrastructure

## A Spatial AI Framework for Recovering Hidden Regime Structure and Multiscale Variation

This repository contains the analytical workflow, notebooks, and supporting materials for the project **From Mobility Intensity to Market Infrastructure**.

The project addresses a central question: **can a latent spatial infrastructure of markets be recovered from the behavioral covariance structure of human mobility signals, and does this infrastructure explain spatial differences in local economic intensity?**

Using large-scale mobility data from Brazil, the project constructs a **Market Infrastructure Index (MII)** from the dominant covariance structure of visitation behavior, identifies **spatially differentiated infrastructure regimes**, evaluates their **economic differentiation** using VIIRS nighttime light intensity, and reconstructs **fine-scale intra-tract variation** through mass-preserving downscaling.

_____________________________________________________

## 💫 Project Framing

Nearby locations often exhibit similar levels of mobility intensity while sustaining markedly different levels of local economic activity. This project argues that **mobility intensity alone does not capture the spatial conditions associated with repeated access, stable visitation, and sustained local activity**.

We use the term **market infrastructure** in a specific and cautious sense. It does **not** refer only to physical infrastructure such as roads, utilities, or buildings, and it does **not** directly measure market outcomes. Instead, it refers to the **underlying spatial conditions reflected in mobility patterns** that support repeated access, stable visitation, and sustained local interaction in ways consistent with stronger **local economic intensity**.

Under this framing, mobility does not merely indicate how many people move through a place. It also reflects whether visitation is organized in patterns consistent with **repeated exposure, local return, and temporal regularity**. The project therefore treats mobility not simply as traffic, but as a **structured spatial phenomenon**.

This repository was developed as part of the **Spatial AI Challenge 2025–26** hosted on the **I-GUIDE Platform** and emphasizes **open science**, **FAIR data principles**, and **reproducible Spatial AI workflows**.

_____________________________________________________

## 📈 What This Project Does

This project develops a Spatial AI framework that:

- constructs **tract-level behavioral mobility indicators**
- recovers a **Market Infrastructure Index (MII)** from the covariance structure of visitation behavior
- identifies **mobility infrastructure regimes** through localized covariance analysis
- evaluates their economic differentiation using **VIIRS nighttime light intensity**
- reconstructs **multiscale spatial variation** through **mass-preserving downscaling**

The national analysis covers **Brazil** using official **IBGE census tracts** as the primary spatial unit. The multiscale reconstruction component focuses on the **São Paulo metropolitan region**, where tract-level aggregation can conceal substantial internal heterogeneity.

_____________________________________________________

## 🌟 Main Contributions

This project makes three primary contributions:

1. It introduces a **reproducible Spatial AI framework** for recovering a latent mobility-based infrastructural dimension from large-scale mobility traces.
2. It shows that mobility-based market infrastructure is **spatially heterogeneous** and organized into **distinct spatial regimes** rather than reducible to a single gradient of visitation.
3. It demonstrates that these structures can be reconstructed at finer spatial resolutions through **mass-preserving downscaling**, making otherwise hidden intra-tract variation empirically visible.

_____________________________________________________

## 📊 Repository Structure

### Notebooks

- **1 - Pipeline A (Mobility).ipynb**  
  Constructs tract-level behavioral mobility indicators from raw mobility traces, including visitation intensity, visitor diversity, repeat visitation, dwell time, and temporal stability.

- **2 - Pipeline S (Spatial Integration).ipynb**  
  Integrates the mobility indicators with official 2022 IBGE census tract geometries and produces the national tract-level spatial base.

- **3 - Pipeline V (Validation).ipynb**  
  Evaluates the internal consistency, robustness, and distinctiveness of the mobility construct through statistical diagnostics and validation procedures.

- **4 - Pipeline D (Downscaling).ipynb**  
  Implements the mass-preserving spatial downscaling procedure used to reconstruct fine-resolution infrastructure patterns within census tracts.

- **5 - Pipeline X (Spatial Structural Regime Modeling (GW-PCA)).ipynb**  
  Recovers localized covariance structure, estimates spatially varying mobility organization, and identifies mobility infrastructure regimes.


- **from_mobility_intensity_to_market_infrastructure_spatial_ai.ipynb**  
  Final integrated notebook presenting the analytical workflow, empirical results, figures, maps, and narrative structure of the project.

### Supporting Files

- **Data Dictionary - Human Mobility.xlsx**  
  Data dictionary describing the human mobility variables used in the project.

- **assets/**  
  Folder containing figures, visual materials, and team images used in the repository.

_____________________________________________________

## 🔄 Core Analytical Logic

The project follows the logic below:

**human mobility signals**  
→ **behavioral indicators**  
→ **covariance structure**  
→ **Market Infrastructure Index (MII)**  
→ **spatial regimes**  
→ **economic validation with VIIRS**  
→ **multiscale reconstruction through downscaling**

_____________________________________________________

## 🌍 Data Sources

The analysis combines three main data sources:

- **Human mobility data** aggregated to the census tract level
- **IBGE 2022 census tract geometries**
- **VIIRS nighttime light emissions** as an external proxy for **local economic intensity**

_____________________________________________________

## 🚀 Recommended Entry Points

If you are new to the repository, start here:

1. **from_mobility_intensity_to_market_infrastructure_spatial_ai.ipynb** — integrated analytical narrative
2. **1 - Pipeline A (Mobility).ipynb** — indicator construction
3. **5 - Pipeline X (Spatial Structural Regime Modeling (GW-PCA)).ipynb** — core spatial structural modeling
4. **4 - Pipeline D (Downscaling).ipynb** — multiscale reconstruction

_____________________________________________________

## 👩‍🚀 Team Members

| Picture | Name | Role | Institution |
|--------|------|------|-------------|
| <img src="assets/team/Wang.jpg" width="80"/> | **Siqin Wang** | Lead Researcher & PI | University of Southern California, USA |
| <img src="assets/team/Miranda.jpg" width="80"/> | **Jessica Miranda** | Researcher | Federal University of Rio Grande do Sul, Brazil |
| <img src="assets/team/Albuquerque.jpeg" width="80"/> | **Rafael Albuquerque** | Researcher | Federal University of Rio Grande do Sul, Brazil |
| <img src="assets/team/Brei.jpg" width="80"/> | **Vinicius Brei** | Principal Investigator | Federal University of Rio Grande do Sul, Brazil |

____________________________________________

## 🏢 Support & Infrastructure

This project is developed and executed using resources provided by:

- **I-GUIDE Platform**
- **Jetstream2 Cloud Infrastructure**
- **Federal University of Rio Grande do Sul (UFRGS)**
- **University of Southern California**

______________________________________

## 📄 License

This project is released under the **MIT License**.

______________________________________

## 📚 Citation

If you use or reference this repository, please cite the project as:

**From Mobility Intensity to Market Infrastructure: A Spatial AI Framework for Recovering Hidden Regime Structure and Multiscale Variation**

Citation metadata can also be provided through a `CITATION.cff` file if needed.
