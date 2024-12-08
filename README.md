# Directory
- [Introduction](#robust-em-clustering-algorithm)
- [Authors](#authors)
- [Features](#features)
- [Result](#result)
- [References](#references)

# Robust EM Clustering Algorithm
This repository contains the implementation of a Robust Expectation-Maximization (Robust EM) Clustering algorithm designed for Gaussian mixture models proposed by Miin-Shen Yang, Chien-Yo Lai, and Chih-Ying Lin ([2012](#ref-EM_cluster)) . The project includes examples of clustering Gaussian mixture models and a comparison with standard EM algorithm.

## Authors
* Yuxin Liu
* Yijia Xue
* Chenguang Yang

## Features
* Robust EM Algorithm: Implements the Robust EM Clustering Algorithm.
* E-Step and M-Step function: Modular functions for the Expectation and Maximization steps.
* EM Algorithm: Implements the standard EM Algorithm.
* Simulation Examples: Four simulation scenarios to demonstrate the robustness of the algorithm on Gaussian mixture data.
* Comparison with Standard EM: Visual and quantitative comparison of results.

## Result 

<div style="text-align: center;">
  <img src="./it_44%20C_2.png" alt="iteration 44; C 2" style="width: 80%;"/>
  <p>iteration 44; C 2</p>
</div>

</br>

<div style="text-align: center;">
  <img src="./it_55%20C_16.png" alt="iteration 55; C 16" style="width: 80%;"/>
  <p>iteration 55; C 16</p>
</div>
</br>

<div style="text-align: center;">
  <img src="./it_38 C_3.png" alt="iteration 38; C 3" style="width: 80%;"/>
  <p>iteration 38; C 3</p>
</div>

## References

<div id="refs" class="references">

<div id="ref-EM_cluster">

Miin-Shen Yang, Chien-Yo Lai, and Chih-Ying Lin. 2012. "A Robust EM Clustering Algorithm for Gaussian Mixture Models." *Pattern Recognition* 45: 3950–3961.
<http://dx.doi.org/10.5705/ss.2013.088>.
