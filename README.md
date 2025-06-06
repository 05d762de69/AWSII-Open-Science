# Brain Volume Loss in Alzheimer’s Disease: The Roles of Age and Gender in the Relationship Between Atrophy and Cognitive Decline
*Open-science companion repository*

This repo accompanies the final assignment for **Academic Writing Skills II**.  
It contains:

* the full Quarto analysis notebook (code + results)  
* the manuscript source that pulls results inline  
* raw data and a reproducible R environment via **renv**

>[!IMPORTANT]
>Please view the analysis companion [here](https://05d762de69.github.io/AWSII-Open-Science/analysis.html).

## Project structure

+ `analysis/`    – Quarto notebook + helper functions  
+ `manuscript/`  – paper.qmd (pulls results inline)  
+ `data/`        – anonymised CSV 
+ `output/`     – rendered PDFs, figures  
+ `docs/`        - interactive HTML file for analyses

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
