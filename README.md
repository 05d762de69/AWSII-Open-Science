# Brain Volume Loss in Alzheimer’s Disease: The Roles of Age and Gender in the Relationship Between Atrophy and Cognitive Decline

## Introduction

This repository holds my Open Science approach to the final assignment of the course Academic Writing Skills II. The goal of the assignment was to conduct
analyses on a given dataset and write up the _Introduction_, _Results_, and _Discussion_ in the form of a partial replication.

I wanted to use this assignment to familiarize myself with the Quarto extension for R, and test out some workflows in Academic Writing.

[!important]
>Please view the analysis companion [here](https://05d762de69.github.io/AWSII-Open-Science/analysis.html).

## Project structure

analysis/    – Quarto notebook + helper functions  
manuscript/  – paper.qmd (pulls results inline)  
data/        – anonymised CSV 
outputs/     – rendered PDFs, figures  
docs/        - interactive HTML file for analyses

## Quickstart

Feel free to run the analyses in your local environment.

```bash
git clone https://github.com/05d762de69/AWSII-Open-Science.git
cd AWSII-Open-Science
```

From here you can replicate the environment using:

```r
install.packages("renv")
renv::restore()            
```

After the packages install, you can render everything with:

```r
quarto_render("analysis/analysis.qmd")
quarto render("manuscript/paper.qmd")
```


## Contact
679693hs@eur.nl  - Issues welcome!
