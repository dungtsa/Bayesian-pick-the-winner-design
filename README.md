# Bayesian-pick-the-winner-design
The tool is to calculate power for the Bayesian pick-the-winner design in a randomized phase II clinical trial. It also generates report and statistical plan so clinicians could easily incorporate it into the clinical trial protocol.
(reference: A Bayesian pick-the-winner design in a randomized phase II clinical trial; Chen et al; submitted).

## Features

* The shiny applictaion provide power calculation for the Bayesian pick-the-winner design in a randomized phase II clinical trial and generates a statistical plan to be easily incorporated  into the clinical trial protocol. 

## Installation

Simply run the following from an R console:

```r
if (!require("devtools"))
  install.packages("devtools")
devtools::install_github("dungtsa/BayesianPickWinner",force = TRUE)
```

## Getting Started

```r
require("BayesianPickWinner")
bayes.pick.winner()
```
-------------------------------
Snapshot of shiny app: initial 
![snapshot of shiny app: initial](inst/img/powershiny1.png)

-------------------------------
Snapshot of shiny app: output
![snapshot of shiny app: output](inst/img/powershiny2.png)

-------------------------------
Snapshot of shiny app: output in Word format (through "download" button)
![snapshot of shiny app: output](inst/img/powershiny3.png)
