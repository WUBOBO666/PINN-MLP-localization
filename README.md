# Physics-Informed MLP for Robust Wi-Fi RSS Fingerprinting

This repository accompanies our IEEE *Signal Processing Letters* submission:

> **"Physics-Informed MLP for Robust Wi-Fi RSS Fingerprinting with a Reproducible Simulation Platform"**  
> Xingzhao Wu, Jieling Wang, Bin Tian, Bazhong Shen, and Mengze Sun  
> Submitted to *IEEE Signal Processing Letters*, October 2025.

---

## Repository Status
The source code and simulator will be released **after the paper is accepted**.

For now, this repository provides metadata and reproducibility documentation only.

---


## Overview
This work proposes a **Physics-Informed Multilayer Perceptron (PINN-MLP)** framework for robust indoor localization using Wi-Fi RSS fingerprints.  
A **reproducible RSS simulation platform** is developed to model access-point (AP) bias, correlated shadowing, and receiver sensitivity.

The proposed method integrates a **log-distance path-loss constraint** into coordinate regression, combined with a **Huber penalty** and **visibility masking** for improved robustness.

---

## Key Features
- Physics-informed loss term ensuring RSS–distance consistency  
- Robust regression with Huber penalty and AP visibility mask  
- Reproducible RSS simulator with configurable noise, AP bias, and path-loss jitter  
- Benchmark comparison with KNN, SVR, RF, MLP, and ResMLP baselines  

---

## Experimental Results (Summary)
- Minimum localization RMSE: **0.45 m** under non-uniform AP layouts  
- Consistent performance across various noise levels and AP counts  
- Validation on the public **UJIIndoorLoc** dataset confirming generalization  

---


