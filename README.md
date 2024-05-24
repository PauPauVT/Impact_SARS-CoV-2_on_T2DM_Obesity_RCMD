# Impact of SARS-CoV-2 on Diabetes, Obesity and Chronic Renal Microvascular Disease: Identification of prognostic factors and creation of a predictive score

The Covid-19 pandemic has posed unprecedented challenges to healthcare systems worldwide, particularly impacting patients with Type 2 Diabetes Mellitus (DM2), Obesity and Renal Chronic Microvascular Disease (RCMD). This study investigates the bidirectional relationship between Covid-19 and metabolic control in patients with DM2, Obesity or RCMD, aiming to understand the evolution of metabolic parameters during the pandemic. Leveraging advanced statistical techniques and supervised learning models, the study identifies distinct patient clusters based on metabolic profiles and predicts post-Covid-19 metabolic evolution. Data from patients' metabolic parameters before and after Covid-19 episodes are collected and analyzed, revealing three clusters: the renal group, lipid group, and HbA1c group, each with unique metabolic characteristics and clinical implications. Supervised learning models demonstrate moderate success in predicting cluster membership, highlighting the complexity of post-Covid-19 metabolic evolution prediction. While significant predictors include age, sex, initial metabolic values and comorbidities, discrepancies between medical interpretations and model results underscore the need for further research and validation. This study lays the groundwork for personalized care strategies for post-Covid-19 patients with DM2, Obesity or RCMD, contributing to the advancement of predictive medicine and targeted interventions in the face of complex metabolic conditions exacerbated by the pandemic

Requirements
------------

First of all, comment that data extraction has not been possible for a long time by third parties due to the privacy of the databases.

To execute the rest of the project it will be necessary to work with some interactive interface that accepts R (ex: Rstudio)

The R packages used have been:

* dplyr)
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

Organització del projecte
------------

    ├── README.md                                    <- El README de primer nivell per als desenvolupadors del projecte.
    ├── Àrea de Creació
    │   ├── dades.zip                                <- Dades intermèdies i finals.
    │   ├── select_subv_creacio.sql                  <- Script per a l'extracció de dades.
    │   ├── subv_creacio.ipynb                       <- Neteja de les dades i creació de les gràfiques.
    │   ├── subv_creacio.html                        <- Neteja de les dades i creació de les gràfiques - EXECUTAT (per a la directa visualització).
    │   └── subv_creacio_grafics.html                <- Visualitzacions finals.
    │ 
    ├── Àrea de Literatura           
    │   ├── dades.zip                                <- Dades intermèdies i finals.
    │   ├── select_subv_lite.sql                     <- Script per a l'extracció de dades.
    │   ├── subv_lite.ipynb                          <- Neteja de les dades i creació de les gràfiques.
    │   ├── subv_lite.html                           <- Neteja de les dades i creació de les gràfiques - EXECUTAT (per a la directa visualització).
    │   └── subv_lite_grafics.html                   <- Visualitzacions finals.
    │ 
    └── Àrea de Llengua i Universitats                
        ├── Subvencions
        │   ├── dades.zip                            <- Dades intermèdies i finals.
        │   ├── select_subv_llengua.sql              <- Script per a l'extracció de dades.
        │   ├── select_subv_evolucioUnis.sql         <- Script per a una segona extracció de dades.
        │   ├── subv_llengua.ipynb                   <- Neteja de les dades i creació de les gràfiques.
        │   ├── subv_llengua.html                    <- Neteja de les dades i creació de les gràfiques - EXECUTAT (per a la directa visualització).
        │   └── subv_llengua_grafics.html            <- Visualitzacions finals.
        │ 
        ├── Inscripcions (campus i estades)
        │   ├── dades.zip                            <- Dades intermèdies i finals.
        │   ├── select_inscripcions.sql              <- Script per a l'extracció de dades.
        │   ├── inscripcio.ipynb                     <- Neteja de les dades i creació de les gràfiques.
        │   ├── inscripcio.html                      <- Neteja de les dades i creació de les gràfiques - EXECUTAT (per a la directa visualització).
        │   └── inscripcio_grafics.html              <- Visualitzacions finals.
        │ 
        ├── Certificació
        │   ├── dades.zip                            <- Dades intermèdies i finals.
        │   ├── select_certificacio.sql              <- Script per a l'extracció de dades.
        │   ├── certificacio.ipynb                   <- Neteja de les dades.
        │   ├── certificacio.html                    <- Neteja de les dades - EXECUTAT (per a la directa visualització).
        │   ├── certificacio_plots.ipynb             <- Creació de les gràfiques.
        │   ├── certificacio_plots.html              <- Creació de les gràfiques - EXECUTAT (per a la directa visualització).
        │   └── certificacio_plots_grafics.html      <- Visualitzacions finals.
        │ 
        ├── Selecció de professorat
        │   ├── dades.zip                            <- Dades intermèdies i finals.
        │   ├── select_seleccio.sql                  <- Script per a l'extracció de dades.
        │   ├── seleccio.ipynb                       <- Neteja de les dades i creació de les gràfiques.
        │   ├── seleccio.html                        <- Neteja de les dades i creació de les gràfiques - EXECUTAT (per a la directa visualització).
        │   └── seleccio_grafics.html                <- Visualitzacions finals.
        │ 
        └── Memòries
            ├── dades.zip                            <- Dades intermèdies i finals.
            ├── select_memories.sql                  <- Script per a l'extracció de dades.
            ├── memories.ipynb                       <- Neteja de les dades i creació de les gràfiques.
            ├── memories.html                        <- Neteja de les dades i creació de les gràfiques - EXECUTAT (per a la directa visualització).
            └── memories_grafics.html                <- Visualitzacions finals.
