---
author: Yao-Chung Chen
categories:
- ortholog
- transposable elements
- Bioconductor
- R
- package
date: "2022-02-15"
draft: false
excerpt: A Bioconductor R package to estimate DE and correlation of ortholog and transposable elements between two species.
layout: single
links:
- icon: github
  icon_pack: fab
  name: github
  url: https://github.com/ferygood/TEKRABber
- icon: door-open
  icon_pack: fas
  name: Bioconductor
  url: https://bioconductor.org/packages/3.15/bioc/html/TEKRABber.html
subtitle: An R/Bioconductor package to estiamte DE/correlations between two species
tags:
- hugo-site
title: TEKRABber
---

## Introduction
The name of TEKRABber comes from the idea that the largest group of transcription factors, Krüppel-associated box (KRAB) domain-containing zinc-finger play a role as a grabber of transposable elements (TEs). The aim of developing TEKRABber is to provide a user-friendly tool to estimate the correlations in selected orthologs and transposable elements between two selected species. It takes the advantage by using the orthology information to normalize expression counts, setting one species as a reference and the other as a compare one. It can also be used to compare control and treatment data within the same species. TEKRABber also provides an app function to help users have a quick view of their results.

<p align="center">
  <img src="https://user-images.githubusercontent.com/40789913/143321587-dc3dd415-89d8-44fc-8500-52960cd6a4c5.gif" width="70%" height="70%" />
</p>


## User's Guide  
You can download TEKRABber using `BiocManager::install()`:

```r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("TEKRABber")
```

or download directly from github repo:

```r
devtools::install_github("ferygood/TEKRABber")
```

Find detailed information in `vignettes/TEKRABber.Rmd`

## Contact
email: yao-chung.chen@fu-berlin.de

---

