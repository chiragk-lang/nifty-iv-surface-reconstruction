# NIFTY IV Surface Reconstruction

## Overview

This project focuses on reconstructing missing implied volatility (IV) values in the NIFTY options volatility surface.

The approach combines:

- Strike-space interpolation
- Moneyness-space interpolation
- Adaptive volatility surface modeling
- Region-wise interpolation selection
- Validation-driven weight optimization

The final model was developed through extensive cross-validation across multiple interpolation methods and blending strategies.

---

## Dataset

The dataset contains:

- Timestamp
- Underlying NIFTY price
- Call option implied volatilities
- Put option implied volatilities

Several IV observations are missing and need to be reconstructed while preserving realistic volatility surface behavior.

---

## Methodology

1. Exploratory Data Analysis (EDA)
2. Missing Value Analysis
3. Volatility Smile Investigation
4. Strike-Space Interpolation
5. Moneyness-Space Interpolation
6. Extreme Surface Detection
7. Validation-Based Weight Optimization
8. Final Blended Surface Reconstruction

---

## Final Model

The final submission uses a blend of:

- Moneyness-space reconstruction
- Adaptive strike-space reconstruction

The blending weights were selected through cross-validation and further refined using leaderboard feedback.

Best Kaggle Public Leaderboard Score: 0.0000380722

---

## Repository Contents

- `24117040-finclub-project2.ipynb` – Complete notebook

---

## Author

Chirag Kumar
