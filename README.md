# Unified GPR Model for Sharp- and Broad-Crested Trapezoidal Side Weirs

This repository contains a MATLAB-based graphical user interface (GUI) developed for predicting the discharge coefficient (Cd) of trapezoidal side weirs using a Gaussian Process Regression (GPR) model.

## Features
- Prediction of Cd for sharp and broad-crested side weirs
- User-friendly GUI (MATLAB App Designer)
- Built-in trained GPR model
- Input range validation

## Input Parameters
- y1: upstream flow depth
- L: crest length
- P: weir height
- t: crest thickness
- Z: relative parameter
- Fr1: Froude number

## Reference
This repository and the included GPR model are developed based on the following research article:

**Kiyoumars Roushangar, Aydin Panahi, & Ismail Farajpour.** (2026). Simultaneous prediction of discharge coefficients for sharp and broad-crested trapezoidal side weirs using machine learning models. *Flow Measurement and Instrumentation, 111*, Article 103473. https://doi.org/10.1016/j.flowmeasinst.2026.103473

If you use this code or model in your research or project, please cite the above paper.

## How to Use
1. Download and run `SideWeir_Cd_Predictor.exe`
2. Select weir type (Sharp or Broad)
3. Enter parameters: y₁, L, P, t, z, Fr₁
4. Click **Predict Cd**


## Author
Aydin Panahi
Ph.D candidate in Water and Hydraulic Structures Engineering
