# extinction-prevention-modeling-MO434
This repository contains the final project baseline for the subject MO434 (Deep Learning) at Unicamp.

### Installation and Setup
Fist of all you need to download this file with the input required input data and extract on the folder
`extinction-prevention-modeling-MO434/Data`

This algorithm **must** be runned on Google Colab, because the geographic libs are very complicate to install on Windows, can't being done by easily. Moreover, the enverionment provides a free GPU, so it is perfect for this project.

### How to Run?
Firstly, you must rub the notebooks inside [Pre-Pipeline](/repository/relative/link.txt) only once, in any order to generate the base data required for the study. Those alorithys are:
*   `0_Standarize_Rasters.ipynb`: This notebook converts all the raster data to the same sizes and metadata. OBS: The mean and standard deviation values were provided directly on  [Pre-Pipeline](/repository/relative/link.txt) because create it takes long hours
*   
*   `0_Study_Case_Baseline_Data.ipynb`: This notebooks create `.csv` files with study cases, that must have a focus species and could have auxiliary species wich are spected to affect on the focus species positively or negatively.
*   
###  Data
1.  Raster Data
|Variable     | Description     | Source                                           |
|:-------------|:---------------|:-----------------------------------------------------|
| Atributo alvo     | `feature` | Seu modelo será treinado para prever os valores do alvo. |

2. Ocurrences Data
The ocurrences data were queried in GBIF. The main info about the species are:

### Result Example


