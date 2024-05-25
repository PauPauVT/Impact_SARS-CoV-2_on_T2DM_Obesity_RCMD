# Impact of SARS-CoV-2 on Diabetes, Obesity and Chronic Renal Microvascular Disease: Identification of prognostic factors and creation of a predictive score

The Covid-19 pandemic has posed unprecedented challenges to healthcare systems worldwide, particularly impacting patients with Type 2 Diabetes Mellitus (DM2), Obesity and Renal Chronic Microvascular Disease (RCMD). This study investigates the bidirectional relationship between Covid-19 and metabolic control in patients with DM2, Obesity or RCMD, aiming to understand the evolution of metabolic parameters during the pandemic. Leveraging advanced statistical techniques and supervised learning models, the study identifies distinct patient clusters based on metabolic profiles and predicts post-Covid-19 metabolic evolution. Data from patients' metabolic parameters before and after Covid-19 episodes are collected and analyzed, revealing three clusters: the renal group, lipid group, and HbA1c group, each with unique metabolic characteristics and clinical implications. Supervised learning models demonstrate moderate success in predicting cluster membership, highlighting the complexity of post-Covid-19 metabolic evolution prediction. While significant predictors include age, sex, initial metabolic values and comorbidities, discrepancies between medical interpretations and model results underscore the need for further research and validation. This study lays the groundwork for personalized care strategies for post-Covid-19 patients with DM2, Obesity or RCMD, contributing to the advancement of predictive medicine and targeted interventions in the face of complex metabolic conditions exacerbated by the pandemic

Requirements
------------

First of all, comment that data extraction has not been possible for a long time by third parties due to the privacy of the databases.

To execute the rest of the project it will be necessary to work with some interactive interface that accepts R (ex: Rstudio)

The R packages used have been:

* dplyr
* readxl
* tidyr
* kableExtra
* compareGroups
* ggplot2
* factoextra
* cluster
* fpc
* mice
* corrplot
* hopkins
* FactoMineR
* vroom
* caret
* scales
* clValid
* nnet
* lmtest
* e1071
* randomForest
* tree

Project organization
------------

    ├── README.md                                                 <- The first level README for the project developers.
    ├── State of the art
    │   ├── dois.ods                                              <- List of the dois of the articles
    │   └── State_of_the_art.Rmd                                  <- Analysis of the titles and abstracts of the articles
    │ 
    └── Data Preprocessing and data analysis           
        └── Data_Preprocessing_and_data_analysis.Rmd              <- Preprocessing data and analysis of it with ML

