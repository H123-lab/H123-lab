# Hassa Iftikhar | Cardiovascular Medicine, Computational Modeling & Clinical AI Evaluation

**PhD Candidate (Transitioning to Postdoctoral Research) | Cardiovascular Medicine / Computational & Clinical AI Research**

## 🔎 Open to Postdoctoral Positions & Research Collaborations

I work across mechanistic cardiovascular physiology, computational modeling, structural bioinformatics, and the methodological evaluation of clinical artificial intelligence. My research combines ODE/PDE-based physiological simulation and nonlinear dynamical-systems analysis with protein–ligand modeling, molecular dynamics, and structured safety evaluation of large language models (LLMs) in cardiovascular scenarios.

I am particularly interested in transparent, reproducible methods for understanding complex cardiovascular systems and for assessing the clinical reasoning, guideline concordance, and safety limitations of emerging AI models. My work is research-focused; benchmark evaluation does not imply clinical deployment or autonomous clinical use.

**Research interests:** mechanistic cardiovascular physiology • nonlinear dynamical systems, multistability and bifurcation analysis • cardiovascular electrophysiology and hemodynamics • structural bioinformatics and AI-driven molecular drug discovery • clinical AI evaluation and foundation-model safety benchmarking • guideline concordance, error-severity classification and reproducible open-science workflows

## 🌟 Featured Research

### CHAB-2026 | Cardiology AI Benchmark

**[H123-lab/CHAB-2026](https://github.com/H123-lab/CHAB-2026) · [OSF pre-registration](https://osf.io/237wu)**

CHAB-2026 is a cardiology-focused benchmark designed to evaluate clinical reasoning and safety-related failure modes in frontier LLMs under standardized vignette conditions. It uses case-matched, double-blinded expert evaluation of **GPT-5, Claude 3.5 Sonnet, Gemini 1.5 Pro, and DeepSeek-V3** across **80 canonical cardiovascular scenarios**—56 guideline-derived cases and 24 published case-report-derived prototypes—covering **10 clinical domains**.

**Benchmark and evaluation design**
- A multidimensional **nine-domain clinical reasoning framework** assesses the quality of model responses across prespecified clinical dimensions.
- A separate **four-level safety and potential-harm taxonomy (SEV-0 to SEV-3)** classifies the most consequential safety-relevant error identified in each response.
- The evaluation protocol uses standardized prompts and expert review to support matched comparisons across models and cases.

**Statistical and reproducibility framework**
- Repeated-measures **Friedman testing** and paired **Wilcoxon signed-rank tests**, with Holm–Bonferroni multiplicity correction.
- **10,000-resample bias-corrected and accelerated (BCa) bootstrap confidence intervals**.
- **Exact McNemar tests** for paired safety-endpoint comparisons.
- **Linear mixed-effects modeling** to examine case-provenance effects.
- Public benchmark materials, analysis code, dependency specifications and reproducibility instructions are maintained in the GitHub repository. Individual row-level rater-score files are subject to evaluator confidentiality and data-access restrictions and are not redistributed publicly.

CHAB-2026 is a structured benchmark study, not a deployed clinical decision-support system; its findings should not be interpreted as evidence of patient-level effectiveness or readiness for autonomous care.

### Computational Cardiovascular Multistability & Nonlinear Dynamics

**[H123-lab/cardiovascular-multistability](https://github.com/H123-lab/cardiovascular-multistability)**

A mechanistically grounded lumped-parameter cardiovascular ODE framework (MATLAB and Numba-accelerated Python) investigating coronary perfusion–contractility bistability, path-dependent hysteresis, linearized Poincaré/Floquet orbital-stability analysis, and mass-conserving transient perturbation dynamics.

**Engineering & reproducibility highlights**
- Dual-language RK4 numerical integration with cross-verified results and reported stressed-volume conservation error on the order of **10⁻¹¹ mL**.
- Linearized Poincaré monodromy and Floquet multiplier analysis of coexisting periodic responses.
- Automated GitHub Actions workflows for numerical audits, output verification, and reproducibility checks.
- **Verified source snapshot:** [main commit `3a3ee89e`](https://github.com/H123-lab/cardiovascular-multistability/commit/3a3ee89e472f4b28eda106c19ea2e4436323fc6f). A `v1.0.0` release tag is not yet published; this commit link identifies the source snapshot.

### Structural Bioinformatics & Molecular Dynamics Portfolio

**[H123-lab/bioinformatics-md-portfolio](https://github.com/H123-lab/bioinformatics-md-portfolio)**

A collection of structural bioinformatics and computational drug-discovery workflows, including molecular docking, molecular dynamics simulations, protein-structure prediction, interaction analysis, automation scripts, and reproducible computational outputs.

**Research applications:** hERG-channel modeling • protein–ligand interaction analysis • RMSD and hydrogen-bond analysis • virtual screening • protein design • computational toxicity assessment

## 🧠 Technical & Methodological Stack

### 1. Clinical AI & Statistical Auditing

- **Clinical AI evaluation:** LLM/foundation-model benchmarking, standardized prompting, guideline-concordance assessment, clinical reasoning rubrics, and safety/error-severity taxonomies.
- **Evaluation protocols:** case-matched expert review, blinded assessment workflows, structured adjudication, and reproducible benchmark documentation.
- **Statistical analysis:** Python (`pandas`, `NumPy`, `SciPy`, `statsmodels`); non-parametric testing, paired comparisons, mixed-effects modeling, multiplicity correction, and bootstrap resampling.
- **Reliability methods:** inter-rater reliability and agreement analysis, including intraclass correlation coefficients (ICC) and Cohen's κ.
- **Open and reproducible research:** Docker, Git, GitHub Actions, versioned analysis pipelines, OSF registration, and transparent data-availability documentation.

### 2. Cardiovascular & Dynamical Modeling

- **Physiological simulation:** mechanistic ODE/PDE models, lumped-parameter cardiovascular systems, numerical integration (RK4), and hemodynamic modeling.
- **Nonlinear dynamics:** periodic orbits, multistability, path-dependent hysteresis, numerical continuation, and bifurcation analysis.
- **Stability analysis:** Poincaré maps, monodromy matrices, Floquet multipliers, and local stability assessment.
- **Electrophysiology:** computational investigation of cardiac electrophysiology and ion-channel-related mechanisms.
- **Scientific computing:** MATLAB, Python, Numba, NumPy, and SciPy.

### 3. Structural Bioinformatics & Molecular Modeling

- **Molecular modeling & structure prediction:** AlphaFold2, Rosetta, ChimeraX, and PyMOL.
- **Molecular dynamics:** GROMACS, MDTraj, and NAMD.
- **Docking & virtual screening:** AutoDock Vina and Schrödinger Suite.
- **Cryo-EM data processing:** RELION and CryoSPARC.
- **Cheminformatics & machine learning:** BioPython, DeepChem, scikit-learn, and BioConductor.
- **Research applications:** protein–ligand interaction analysis, molecular dynamics characterization, computational toxicity assessment, and AI-enabled drug discovery.

### Programming & Research Tools

![Python](https://img.shields.io/badge/Python-FFD43B?style=flat-square&logo=python&logoColor=blue)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-1f1f1f?style=flat-square&logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## 📚 Publications & Manuscripts in Preparation / Submission

- **Multistability, Hysteresis, and Floquet Orbital Stability in a Closed-Loop Lumped-Parameter Cardiovascular Model** — Manuscript in preparation; reproducible code and computational datasets are archived in [H123-lab/cardiovascular-multistability](https://github.com/H123-lab/cardiovascular-multistability).
- **Computational Drug–hERG Channel Simulations and Cardiotoxicity Prediction** — Manuscript in preparation.

## 🌐 Connect

- **LinkedIn:** [Hassa Iftikhar](https://ae.linkedin.com/in/hassa-iftikhar-69371915b)
- **Email:** [hassabatool@yahoo.com](mailto:hassabatool@yahoo.com)
- **ORCID:** [0000-0002-0341-7800](https://orcid.org/0000-0002-0341-7800)
