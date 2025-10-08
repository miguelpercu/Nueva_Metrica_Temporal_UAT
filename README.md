# Nueva_Metrica_Temporal_UAT
Estudio sobre la validacion de UAT una nueva metrica temporal
# UAT_realistic_analysis: Decisive Evidence for Quantum Gravity-Based Resolution of the Hubble Tension

## 🎯 Project Overview

This repository contains the full results, data files, analysis outputs, and key figures supporting the manuscript:

**Title:** "Resolution of the Hubble Tension via the Unified Applicable Time (UAT) Framework: Decisive Evidence from Early Quantum Gravity"

The project provides statistical validation (MCMC Bayesian Analysis) of the Unified Applicable Time (UAT) Framework, demonstrating that a modification of the early universe expansion rate ($k_{\text{early}} \approx 0.967$), derived from Loop Quantum Gravity (LQG) principles, successfully resolves the Hubble Tension.

**Key Result:** The analysis yields $\mathbf{H_0 = 73.03 \pm 1.63 \text{ km/s/Mpc}}$ and $\mathbf{\ln B_{01} = 12.64}$ (Decisive Evidence for UAT over $\Lambda\text{CDM}$).

---

## 📁 Directory Structure and Content

The following structure organizes the input data, analysis output, and final presentation files:

UAT_realistic_analysis/
├── analysis/              # Detailed analysis documents and interpretations
│   ├── analysis_configuration.txt     # Configuration settings for the MCMC run (priors, steps, datasets used)
│   ├── executive_summary.txt          # High-level summary of the methodology and final H0/r_d constraints
│   └── physical_interpretation.txt    # Detailed text on the meaning of k_early and the sound horizon shift
├── data/                  # Input and raw data files
│   └── bao_observational_data.csv     # Observational Baryon Acoustic Oscillation (BAO) data used for the chi-squared and MCMC likelihoods
├── figures/               # Final figures used in the manuscript
│   ├── model_residuals.png            # Plot of residuals comparing UAT predictions to observational data (Figure 5)
│   ├── parameter_optimization.png     # Chi-squared optimization plot for the k_early parameter (Figure 3)
│   └── UAT_BAO_comparison.png         # Plot comparing the UAT and LambdaCDM fits to BAO data (Figure 4)
├── tables/                # Quantitative output data from the modeling
│   ├── detailed_predictions.csv       # Table with UAT model predictions for various observables (e.g., D 
M/r d, H(z)) at different redshifts
│   ├── final_results_summary.csv      # Summary of parameter constraints (H 
0, k 
early, Ω b , Ω cdm ) and Bayesian Evidence (lnZ, lnB 
01 )
│   ├── future_predictions.csv         # Predicted values for future high-precision measurements (e.g., DESI, Euclid)
│   └── model_predictions.csv          # Raw output data from the best-fit UAT model
└── .ipynb_checkpoints/    # (Ignored) Temporary files from Jupyter notebooks, not relevant for analysis review.

## 🛠️ Reproducibility and Usage

To reproduce the primary analysis, you would typically need the Python code used to generate these results (which is not included here but is detailed in the manuscript's Supplementary Information).

**For Peer Review:**
* The **`analysis/`** directory provides the necessary documentation to understand the MCMC setup and the physical conclusions.
* The **`data/bao_observational_data.csv`** file allows reviewers to cross-reference the input data used for the likelihood calculation.
* The **`tables/final_results_summary.csv`** contains the final constraint values that form the basis of the conclusions and the core data for Table 1 in the manuscript.

**Note:** The figures clearly illustrate the primary conclusion: the UAT model provides a significantly better fit to the BAO data, reconciling the early-universe derived sound horizon with the high local $H_0$.

---

## 🧑‍💻 Corresponding Author

**Miguel Ángel Percudani**
* **Affiliation:** Independent Researcher in Cosmology and Theoretical Physics
* **Contact:** miguel_percudani@yahoo.com.ar
