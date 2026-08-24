# The VPS35 p.A320V variant segregates with Parkinson’s disease in a pesticide-exposed family

`GP2 ❤️ Open Science 😍`

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22085586.svg)](https://doi.org/10.5281/zenodo.22085586)

**Last updated:** July 2026

## Summary

This is the online repository for the manuscript titled **"The VPS35 p.A320V variant segregates with Parkinson’s disease in a pesticide-exposed family"**.

## Data statement
Data used in the preparation of this article were obtained from the Global Parkinson’s Genetics Program (GP2; https://gp2.org).

All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson’s disease, and are available via application on the website (https://amp-pd.org/register-for-amp-pd). For up-to-date information on GP2 data acquisition, access, and policies, visit https://gp2.org/. Tier 1 data can be accessed by completing a form on the Accelerating Medicines Partnership in Parkinson’s Disease (AMP®-PD) website (https://amp-pd.org/register-for-amp-pd). Tier 2 data access requires approval and a Data Use Agreement signed by your institution.

In this analysis we used Tier 2 GP2 Release 11 data ([10.5281/zenodo.17753486](https://doi.org/10.5281/zenodo.17753486)).

### Helpful Links

- [GP2 Website](https://gp2.org/)
  - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
  - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)

## Repository Orientation
- The `analysis/` directory includes all analyses discussed in the manuscript.

<pre> THIS_REPO/ 
  ├── analyses/ 
  |     └── extract_VPS35_pA320V.ipynb
  ├── LICENSE
  └── README.md 
</pre>

## Analysis Notebooks
### Languages: Python, bash, and R
| Directory | Notebooks   | Description | 
|-----------|----------------|--------|
|`analyses/`| `extract_VPS35_pA320V.ipynb`         | Extract VPS35 p.A320V variant|


## Software
| **Software** | **Version(s)** | **Resource URL** | **RRID** | **Notes** |
|--------------|----------------|------------------|----------|-----------|
|PLINK|v.1.9,v. 2.0|http://www.nitrc.org/projects/plink|RRID:SCR_001757|Used for genetic analyses.|
|Python Programming Language|3|http://www.python.org/|RRID:SCR_008394|pandas; Used for general data wrangling/analyses|
