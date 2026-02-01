# Policy Pathways for Sustainable Cooling Markets

This repository contains the analytical code and datasets supporting my Master’s thesis, *Policy Pathways for Sustainable Cooling Markets: Enabling Business Model Innovation in the Global South*. The project applies unsupervised clustering techniques to identify distinct country profiles among Article 5 countries under the Montreal Protocol, based on policy, financial, and digital enabling conditions for sustainable cooling business models. 

This quantitative approach is supported by a qualitative analysis of policy instruments, which are identified and structured to capture how different regulatory, financial, and digital tools shape the feasibility of business model innovation. These instruments are used not only to inform the construction of the clustering framework, but also to analyse the policy implications of each cluster and identify differentiated policy pathways tailored to specific country profiles.

## Project Scope
The analysis examines how differences in governance, financing frameworks, and digital readiness shape the feasibility of innovative cooling business models such as Cooling-as-a-Service, ESCOs, and PAYGo in developing countries. Rather than measuring policy outcomes directly, the project clusters countries according to proxy indicators that approximate their institutional and structural capacity to support these models.

The objective is to provide a comparative typology that can inform differentiated policy strategies for governments, donors, and international organisations working on sustainable cooling.

### Key Objectives
* Identify and map policy instruments relevant to business model innovation for sustainable cooling
* Construct a cross-country dataset of proxy indicators capturing enabling conditions
* Apply clustering analysis to group Article 5 countries into distinct profiles
* Interpret clusters in terms of policy implications and potential intervention pathways

## Dataset Description
The final dataset covers 98 Article 5 countries and combines indicators from global sources including the World Bank, IMF, and ESMAP. Variables are organised around three dimensions:
* Governance and institutional capacity
* Finance and business dynamics
* Data and digital infrastructure

Indicators include energy efficiency policy proxies, regulatory quality, AI and digital readiness, and GDP per capita. The cleaned dataset used for clustering is provided in `DATA_final.xlsx`.

## Methods Used
* Systematic literature review and policy instrument mapping
* Indicator selection and data preprocessing
* Feature standardisation using z-scores
* K-Means clustering with model selection using the Elbow Method and Davies–Bouldin Index
* Cluster profiling and comparative interpretation

## Repository Structure
* `Clustering_BMI4Cool.ipynb`  
  Main notebook containing data preparation, clustering analysis, and visualisations
* `DATA_final.xlsx`  
  Cleaned and processed dataset used for the final clustering
* Thesis document  
  Full thesis providing conceptual framework, methodology, and interpretation

## How to Run the Analysis
* Clone this repository
* Open `Clustering_BMI4Cool.ipynb` in JupyterLab or another notebook environment
* Ensure standard Python data science libraries are installed
* Run all cells sequentially to reproduce the analysis and figures

## Scope and Limitations
This repository supports a cross-sectional, exploratory analysis. The clusters reflect relative enabling environments based on proxy indicators and should not be interpreted as direct measures of policy effectiveness or implementation readiness. Country-level case studies are required to complement and validate the results.

## Author
Julieta Pappano  
Policy and Innovation Specialist  
