---
output: rmarkdown::github_document
---

<!-- README.md is generated from README.Rmd. Please edit that file -->

# rdimensions

R client for interacting with [Dimensions](https://www.dimensions.ai/) Analytics API.

# ------ This is a work in progress ------

## Prerequisites

Access to the Dimensions Analytics API requires that you have a Dimensions account with the necessary authorization priviledges.

At the current time, Dimensions offers free access to the Analytics API for scientometric researchers and research projects. To apply for free access, visit [this page](https://www.dimensions.ai/scientometric-research/) and click on 'request access'. You will be required to fill in an application to request non-cost use of Dimensions.

Note that Dimensions has an agreement with the [International Society for Scientometrics and Informetrics](http://issi-society.org/) (ISSI) to provide no-cost access to all ISSI members directly. 

## Installation

Install the development version from Github:


```r
install.packages("devtools")
devtools::install_github("nicholasmfraser/rdimensions")
```

## Usage

`rdimensions` currently only supports a single function, `dimensions_raw`. This function takes two inputs: `query` and `format`.



## Roadmap

## Collaboration

Collaborators are extremely welcome! Please contribute here directly, or contact me directly at nicholasmfraser@gmail.com.