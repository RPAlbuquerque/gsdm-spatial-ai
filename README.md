# From Mobility Intensity to Market Infrastructure

## A Spatial AI Framework for Recovering Hidden Spatial Regimes and Multiscale Variation

This repository contains the final analytical notebook and supporting materials for the project **From Mobility Intensity to Market Infrastructure**, developed for the **I-GUIDE Spatial AI Challenge 2025–26**.

The project addresses a central question: **can structured human mobility signals reveal a spatially organized form of market infrastructure that distinguishes transient movement from recurring local activation, and does this structure correspond to differences in local economic intensity?**

Using nationwide tract-level mobility indicators from Brazil, the project constructs a **Market Infrastructure Index (MII)**, tests its spatial organization with **formal K-nearest-neighbor Moran's I**, identifies **localized mobility infrastructure regimes** using covariance signatures and **geographically weighted PCA**, evaluates the regimes against **VIIRS nighttime light intensity** as an external proxy for local economic intensity, and reconstructs **fine-scale intra-tract variation** through mass-preserving downscaling in São Paulo.

_____________________________________________________

## 💫 Project Framing

Nearby locations often exhibit similar mobility intensity while sustaining markedly different local economic activity. This project argues that **mobility intensity alone does not capture the spatial conditions associated with repeated access, stable visitation, and sustained local activity**.

We use the term **market infrastructure** in a specific and cautious sense. It does **not** refer only to physical infrastructure such as roads, utilities, or buildings, and it does **not** directly measure market outcomes. Instead, it refers to the **underlying spatial conditions reflected in mobility patterns** that support repeated access, stable visitation, and sustained local interaction in ways consistent with stronger **local economic intensity**.

Under this framing, mobility does not merely indicate how many people move through a place. It also reflects whether visitation is organized in patterns consistent with **repeated exposure, local return, and temporal regularity**. The project therefore treats mobility not simply as traffic, but as a **structured spatial phenomenon**.

This repository was developed as part of the **Spatial AI Challenge 2025–26** hosted on the **I-GUIDE Platform** and emphasizes **open science**, **FAIR data principles**, and **reproducible Spatial AI workflows**.

_____________________________________________________

## 📈 What This Project Does

This project develops a reproducible Spatial AI framework that:

- constructs **tract-level behavioral mobility indicators**
- recovers a **Market Infrastructure Index (MII)** from the covariance structure of visitation behavior
- tests the spatial organization of the MII using **formal K-nearest-neighbor Moran's I**
- identifies **mobility infrastructure regimes** through localized covariance analysis and **geographically weighted PCA**
- evaluates robustness through **neighborhood-size sensitivity analysis**
- evaluates economic differentiation using **VIIRS nighttime light intensity** as an external proxy for local economic intensity
- tests whether the MII and regimes add information beyond a **visit-volume-only baseline**
- reconstructs **multiscale spatial variation** through **mass-preserving 100-meter downscaling**

The national analysis covers **Brazil** using official **IBGE census tracts** as the primary spatial unit. The multiscale reconstruction component focuses on the **São Paulo metropolitan region**, where tract-level aggregation can conceal substantial internal heterogeneity.

_____________________________________________________

## 🌟 Main Contributions

This project makes four primary contributions:

1. It introduces a **reproducible Spatial AI workflow** for recovering a latent mobility-based infrastructure field from large-scale human mobility data.
2. It shows that the normalized MII is **spatially organized**, using **formal K-nearest-neighbor Moran's I** as a national-scale spatial autocorrelation diagnostic.
3. It identifies **localized mobility infrastructure regimes** through spatially varying covariance signatures, **geographically weighted PCA** robustness checks, and **neighborhood-size sensitivity analysis**.
4. It demonstrates how tract-level infrastructure can be redistributed to a **100-meter grid** through **mass-preserving downscaling**, revealing intra-tract variation that administrative units conceal.

_____________________________________________________

## 📊 Repository Structure

### Notebook

- **From_Mobility_Intensity_to_Market_Infrastructure.ipynb**  
  Final integrated, platform-ready notebook for the **I-GUIDE Spatial AI Challenge**. It contains the complete evaluator-facing workflow, including input verification, latent structure recovery, spatial autocorrelation testing, localized regime discovery, robustness checks, external validation, and multiscale reconstruction.

### Supporting Files

- **National Mobility Infrastructure Regimes Map.png**  
  Pre-rendered publication-quality national regime map used in the final notebook.

- **cartographic_rendering_national_regime_map.ipynb**  
  Supporting notebook documenting the cartographic rendering workflow used to create the national regime map.

- **assets/**  
  Folder containing figures, visual materials, and team images used in the repository.

_____________________________________________________

## 🔄 Core Analytical Logic

The project follows the logic below:

**human mobility signals**  
→ **standardized behavioral indicators**  
→ **latent structure recovery**  
→ **Market Infrastructure Index (MII)**  
→ **spatial autocorrelation testing**  
→ **localized covariance signatures**  
→ **GW-PCA robustness and sensitivity checks**  
→ **mobility infrastructure regimes**  
→ **external validation with VIIRS**  
→ **incremental validation beyond visit volume**  
→ **mass-preserving 100 m reconstruction**

_____________________________________________________

## 🌍 Data Sources

The analysis combines three main data sources:

- **Human mobility indicators** aggregated to the census tract level
- **Official 2022 IBGE census tract geometries**
- **VIIRS nighttime light intensity**, used as an external, spatially consistent proxy for **local economic intensity**

VIIRS is not treated as a direct measure of firm performance, transactions, profitability, or market outcomes. It is used to evaluate whether the recovered mobility infrastructure regimes correspond to economically differentiated spatial environments.

_____________________________________________________

## 🔎 Scope and Interpretation

The **MII** should not be interpreted as a direct measure of sales, firm performance, or market outcomes. It is a mobility-based latent infrastructure measure that integrates visit volume, visitor composition, repeat visitation, dwell time, and temporal stability.

The validation analyses are structural and diagnostic rather than causal. They evaluate whether the recovered mobility infrastructure field and regimes correspond to economically differentiated spatial environments, not whether mobility infrastructure causes local economic performance.

_____________________________________________________

## 🚀 Recommended Entry Point

Start with the final I-GUIDE notebook:

1. **From_Mobility_Intensity_to_Market_Infrastructure.ipynb** — final integrated, platform-ready notebook for the **I-GUIDE Spatial AI Challenge**.

This notebook contains the complete evaluator-facing workflow, including input verification, latent structure recovery, spatial autocorrelation testing, localized regime discovery, robustness checks, external validation, and multiscale reconstruction.

_____________________________________________________

## 👩‍🚀 Team Members

| Picture | Name | Role | Institution |
|--------|------|------|-------------|
| <img src="assets/team/Wang.jpg" width="80"/> | **Siqin (Sisi) Wang** | Lead Researcher & PI | University of Southern California, USA |
| <img src="assets/team/Miranda.jpg" width="80"/> | **Jessica Miranda** | Researcher | Federal University of Rio Grande do Sul, Brazil |
| <img src="assets/team/Albuquerque.jpeg" width="80"/> | **Rafael Albuquerque** | Researcher | Federal University of Rio Grande do Sul, Brazil |
| <img src="assets/team/Brei.jpg" width="80"/> | **Vinicius Brei** | Principal Investigator | Federal University of Rio Grande do Sul, Brazil |

____________________________________________

## 🏢 Support & Infrastructure

This project is developed and executed using resources provided by:

- **I-GUIDE Platform**
- **Federal University of Rio Grande do Sul (UFRGS)**
- **University of Southern California**

______________________________________

## 📄 License

This project is released under the **MIT License**.

______________________________________

## 📚 Citation

If you use or reference this repository, please cite the project as:

**From Mobility Intensity to Market Infrastructure: A Spatial AI Framework for Recovering Hidden Spatial Regimes and Multiscale Variation**

Citation metadata can also be provided through a `CITATION.cff` file if needed.
