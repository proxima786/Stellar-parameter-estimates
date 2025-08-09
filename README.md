# Stellar Parameter Estimation from High-Resolution Spectra

## 📌 Project Description
High-resolution spectroscopic data from stars serves as a valuable tool to infer their physical characteristics, which in turn are crucial for analyzing the properties of their exoplanets.  

This **Bachelor Thesis** focuses on developing a **Python version** of the original IDL script *"PARAS-SPEC"*.  

The workflow of this project is as follows:
1. **Input Data** — High-resolution stellar spectra obtained from the **PARAS spectrograph**.
2. **Gaussian Fitting** — Fit a Gaussian template to selected absorption lines in the spectrum.
3. **Chi-Square (or Least Squares) Analysis** — Perform statistical fitting to estimate stellar parameters:
   - **Surface gravity** (*log g*)
   - **Effective temperature** (*T<sub>eff</sub>*)
   - **Metallicity** (*[Fe/H]*)
4. **Best Fit Selection** — The **minimum chi-square value** corresponds to the best-fitting stellar parameters.

