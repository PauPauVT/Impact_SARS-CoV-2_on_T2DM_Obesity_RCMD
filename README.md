# Tñitol

Descripció breu del projecte

Requeriments
------------

Primer de tot cal comentar que l'extracció de les dades no es podrà dur a terme per tercers a causa de la privacitat de les bases de dades.

Per a executar la resta del projecte serà necessari treballar amb alguna interfície interactiva que accepti Python (ex: Jupyter Notebook o Google Collaboratory)

Els paquets de Python utilitzats han estat:

* pandas
* files de google.colab
* altair
* numpy
* time
* difflib
* re
* datetime
* Counter de collections
* io
* matplotlib.pyplot

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
