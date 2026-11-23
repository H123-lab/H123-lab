# 👋 Hassa Iftikhar | Cardiovascular Medicine, Computational Modeling & Clinical AI Research

**PhD Candidate (Transitioning to Postdoctoral Research) | Cardiovascular Medicine / Computational & Clinical AI Research | Nonlinear Cardiovascular Physiology • Structural Bioinformatics • Clinical AI Evaluation & Safety Benchmarking**

## 🔎 Open to Postdoctoral Positions & Research Collaborations

I work across mechanistic cardiovascular physiology, structural bioinformatics, and computational evaluation of clinical artificial intelligence. My research combines ODE/PDE-based cardiovascular modeling and nonlinear dynamical-systems analysis with protein–ligand interaction modeling, molecular simulation, and systematic evaluation of large language models (LLMs) in cardiology.

My clinical AI work focuses on benchmark design, guideline concordance, clinically meaningful error-severity assessment, blinded expert evaluation, and reproducible statistical analysis. I aim to make computational and AI research more transparent, auditable, and reproducible, while keeping benchmark findings distinct from claims about clinical deployment or patient outcomes.

**Research interests:** mechanistic cardiovascular physiology • nonlinear dynamical systems, multistability and bifurcation analysis • structural bioinformatics and AI-driven molecular drug discovery • clinical artificial intelligence and foundation-model evaluation • cardiology LLM safety benchmarking • guideline concordance and clinical error-severity taxonomy • reproducible open-science workflows

## 🌟 Featured Research Projects

### Featured Project 1: CHAB-2026 — Cardiology AI Benchmark

**[H123-lab/CHAB-2026](https://github.com/H123-lab/CHAB-2026)** · **[Open Science Framework (OSF) registration](https://osf.io/237wu)**

CHAB-2026 is a cardiology-specific benchmark designed to evaluate clinical reasoning and safety-relevant failure modes in large language models under standardized vignette conditions. The benchmark uses **80 canonical cardiovascular scenarios**—56 guideline-derived and 24 adapted from published case-report prototypes—across **10 clinical domains**.

**Evaluation design and methods**
- Case-matched, double-blinded expert assessment of four evaluated models: **GPT-5, Claude 3.5 Sonnet, Gemini 1.5 Pro, and DeepSeek-V3**.
- A multidimensional **9-domain clinical reasoning framework**, paired with a **four-level safety and harm-severity taxonomy (SEV-0 to SEV-3)**.
- Guideline-concordance assessment, structured error-severity classification, and expert adjudication procedures.
- Reproducible statistical analyses, including **Friedman tests**, paired **Wilcoxon signed-rank tests** with **Holm–Bonferroni correction**, **10,000-resample bias-corrected and accelerated (BCa) bootstrap intervals**, exact **McNemar safety comparisons**, and **linear mixed-effects provenance modeling**.
- Open-science orientation through a public research repository and OSF registration, supporting transparent documentation and reproducible analysis.

The project is a standardized benchmark study; it does **not** establish clinical deployment readiness, autonomous clinical capability, or improved patient outcomes.

### Featured Project 2: Computational Cardiovascular Multistability & Nonlinear Dynamics

**[H123-lab/cardiovascular-multistability](https://github.com/H123-lab/cardiovascular-multistability)**

A mechanistically grounded lumped-parameter cardiovascular ODE framework (MATLAB and Numba-accelerated Python) investigating coronary perfusion–contractility bistability, path-dependent hysteresis, linearized Poincaré/Floquet orbital-stability analysis, and mass-conserving transient perturbation dynamics.

**Engineering & reproducibility highlights**
- Dual-language RK4 numerical integration with cross-verified results and reported stressed-volume conservation error on the order of **10⁻¹¹ mL**.
- Linearized Poincaré monodromy and Floquet multiplier analysis of coexisting periodic responses.
- Automated GitHub Actions CI/CD workflows for numerical audits, output verification, and reproducibility checks.
- **Verified source snapshot:** [main commit `3a3ee89e`](https://github.com/H123-lab/cardiovascular-multistability/commit/3a3ee89e472f4b28eda106c19ea2e4436323fc6f). A `v1.0.0` release tag is not yet published; this commit link identifies the exact source snapshot.

### Featured Project 3: Structural Bioinformatics & Molecular Dynamics Portfolio

**[H123-lab/bioinformatics-md-portfolio](https://github.com/H123-lab/bioinformatics-md-portfolio)**

A collection of structural bioinformatics and computational drug-discovery workflows, including molecular docking, molecular dynamics simulations, protein-structure prediction, interaction analysis, automation scripts, and reproducible computational outputs.

**Research applications:** hERG-channel modeling • protein–ligand interaction analysis • RMSD and hydrogen-bond analysis • virtual screening • protein design • computational toxicity assessment

## 🧠 Technical & Methodological Stack

### 1. Clinical AI Evaluation & Statistical Auditing

- **Clinical AI evaluation:** cardiology foundation-model and LLM benchmarking, guideline concordance, structured clinical-reasoning assessment, safety auditing, and error-severity taxonomies.
- **Evaluation methodology:** case-matched and double-blinded expert review, adjudication workflows, and inter-rater reliability assessment (**ICC** and **Cohen’s κ**, where applicable).
- **Biostatistics:** non-parametric paired testing, Friedman and Wilcoxon procedures, multiple-comparison correction, exact McNemar testing, bootstrap resampling, and mixed-effects modeling.
- **Python stack:** Python, pandas, NumPy, SciPy, and statsmodels.
- **Reproducible research:** version-controlled analysis, documented pipelines, Docker, GitHub Actions, and Open Science Framework (OSF) registration.

![Python](https://img.shields.io/badge/Python-FFD43B?style=flat-square&logo=python&logoColor=blue)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OSF](https://img.shields.io/badge/Open%20Science-OSF-5B6F8E?style=flat-square)

### 2. Cardiovascular & Dynamical Modeling

- **Physiological modeling:** mechanistic ODE/PDE models, lumped-parameter cardiovascular systems, numerical integration (RK4), electrophysiology, and hemodynamic modeling.
- **Nonlinear dynamics:** periodic orbits, multistability, path-dependent hysteresis, numerical continuation, bifurcation tracking, and stability analysis.
- **Orbital stability:** Poincaré maps, monodromy matrices, and Floquet multipliers.
- **Scientific computing:** MATLAB, Python, Numba, NumPy, and SciPy.

![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Numba](https://img.shields.io/badge/Numba-00A3E0?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 3. Structural Bioinformatics & Molecular Drug Discovery

- **Molecular modeling and structure prediction:** AlphaFold2, Rosetta, ChimeraX, and PyMOL.
- **Molecular dynamics:** GROMACS, MDTraj, and NAMD.
- **Docking and virtual screening:** AutoDock Vina and Schrödinger Suite.
- **Cryo-EM data processing:** RELION and CryoSPARC.
- **Cheminformatics and machine learning:** BioPython, DeepChem, scikit-learn, and BioConductor.
- **Research methods:** protein–ligand interaction analysis, molecular docking and dynamics, structure-based drug discovery, and computational cardiotoxicity assessment.

![GROMACS](https://img.shields.io/badge/GROMACS-2B86F0?style=flat-square)
![AutoDock Vina](https://img.shields.io/badge/AutoDock%20Vina-6600cc?style=flat-square)
![AlphaFold2](https://img.shields.io/badge/AlphaFold2-025E73?style=flat-square)
![ChimeraX](https://img.shields.io/badge/ChimeraX-660066?style=flat-square)
![RELION](https://img.shields.io/badge/RELION-334455?style=flat-square)
![CryoSPARC](https://img.shields.io/badge/CryoSPARC-444444?style=flat-square)
![Rosetta](https://img.shields.io/badge/Rosetta-FE7D37?style=flat-square)
![BioPython](https://img.shields.io/badge/BioPython-3776AB?style=flat-square)
![MDTraj](https://img.shields.io/badge/MDTraj-006400?style=flat-square)
![DeepChem](https://img.shields.io/badge/DeepChem-00CED1?style=flat-square)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

### Programming & Scripting

Python • MATLAB • R • Bash

## 📚 Publications & Manuscripts in Preparation / Submission

- **Multistability, Hysteresis, and Floquet Orbital Stability in a Closed-Loop Lumped-Parameter Cardiovascular Model** — Manuscript in preparation; reproducible code and computational datasets are archived in [H123-lab/cardiovascular-multistability](https://github.com/H123-lab/cardiovascular-multistability).
- **Computational Drug–hERG Channel Simulations and Cardiotoxicity Prediction** — Manuscript in preparation.

## 🌐 Connect

- **LinkedIn:** [Hassa Iftikhar](https://ae.linkedin.com/in/hassa-iftikhar-69371915b)
- **Email:** [hassabatool@yahoo.com](mailto:hassabatool@yahoo.com)
- **ORCID:** [0000-0002-0341-7800](https://orcid.org/0000-0002-0341-7800)
