# Directory
- [Introduction](#robust-em-clustering-algorithm)
- [Authors](#authors)
- [Required Packages](#required-packages)
- [Features](#features)
- [Simulation Results](#simulation-results)
- [References](#references)

# Robust EM Clustering Algorithm
This repository contains the implementation of a Robust Expectation-Maximization (Robust EM) Clustering algorithm designed for Gaussian mixture models proposed by Miin-Shen Yang, Chien-Yo Lai, and Chih-Ying Lin ([2012](#ref-EM_cluster)) . The project includes examples of clustering Gaussian mixture models and a comparison with standard EM algorithm.

## Authors
* Yuxin Liu
* Yijia Xue
* Chenguang Yang

## Required Packages
``` r
library(mvtnorm)
library(Matrix)
library(ggplot2)
library(ggthemes)
```

## Features
* Robust EM Algorithm: Implements the Robust EM Clustering Algorithm.
* E-Step and M-Step function: Modular functions for the Expectation and Maximization steps.
* EM Algorithm: Implements the standard EM Algorithm.
* Simulation Examples: Four simulation scenarios to demonstrate the robustness of the algorithm on Gaussian mixture data.
* Comparison with Standard EM: Visual and quantitative comparison of results.

## Simulation Results 

<div style="text-align: center;">
  <img src="./figure1.png" alt="iteration 44; C 2" style="width: 80%;"/>
  <p>Simulation 1 Robust EM</p>
</div>

</br>

<div style="text-align: center;">
  <img src="./figure2.png" alt="iteration 8; C 2" style="width: 80%;"/>
  <p>Simulation 1 EM</p>
</div>

</br>

<div style="text-align: center;">
  <img src="./figure3.png" alt="iteration 38; C 3" style="width: 80%;"/>
  <p>Simulation 2 Robust EM</p>
</div>

</br>
<div style="text-align: center;">
  <img src="./figure4.png" alt="iteration 117; C 3" style="width: 80%;"/>
  <p>Simulation 2 EM</p>
</div>

</br>

<div style="text-align: center;">
  <img src="./figure5.png" alt="iteration 137; C 5" style="width: 80%;"/>
  <p>Simulation 3 Robust EM</p>
</div>

</br>
<div style="text-align: center;">
  <img src="./figure6.png" alt="iteration 68; C 5" style="width: 80%;"/>
  <p>Simulation 3 EM</p>
</div>

</br>
<div style="text-align: center;">
  <img src="./figure7.png" alt="iteration 55; C 16" style="width: 80%;"/>
  <p>Simulation 4 Robust EM</p>
</div>

</br>

<div style="text-align: center;">
  <img src="./figure8.png" alt="iteration 145; C 16" style="width: 80%;"/>
  <p>Simulation 4 EM</p>
</div>

## References

<div id="refs" class="references">

<div id="ref-EM_cluster">

Miin-Shen Yang, Chien-Yo Lai, and Chih-Ying Lin. 2012. "A Robust EM Clustering Algorithm for Gaussian Mixture Models." *Pattern Recognition* 45: 3950–3961.
<http://dx.doi.org/10.5705/ss.2013.088>.







