# Hi, I'm Alireza Javan 👋

**Medical scientist working where clinical medicine meets computation.** My focus is chronic disease and
cardiovascular medicine: building prediction models, survival analyses and in silico pipelines that are
reproducible, honestly validated, and grounded in clinical reasoning.

- 🫀 **Research:** cardiovascular drug discovery, chronic kidney disease, diabetes, prognostic modelling
- 📊 **Methods:** meta-analysis, survival analysis, clinical prediction models (TRIPOD), decision-curve analysis, cheminformatics, network pharmacology, graph neural networks
- 🧪 **Principle:** a model is only useful if it is well-calibrated, clinically interpretable and reproducible

---

### 🔬 Featured projects

#### SGLT2 inhibitors: from molecule to trial to evidence

Three linked projects follow one drug class across levels of evidence.

| Project | What it does | Stack |
|---|---|---|
| [**cardio-drug-target-explorer**](https://github.com/alirezajavan-sys/cardio-drug-target-explorer) | **Molecule:** SGLT2-vs-SGLT1 potency and selectivity of the five outcome-trial gliflozins from ChEMBL. Shows sotagliflozin is a dual inhibitor (~20× vs ~140–1,200×) | Python · ChEMBL API |
| [**cardiometabolic-trials-landscape**](https://github.com/alirezajavan-sys/cardiometabolic-trials-landscape) | **Trials:** 826 phase 3 SGLT2 and GLP-1 trials from ClinicalTrials.gov. Charts the shift from glucose lowering to heart failure/CKD (SGLT2) and obesity (GLP-1) | Python · ClinicalTrials.gov API v2 |
| [**sglt2-inhibitor-meta-analysis**](https://github.com/alirezajavan-sys/sglt2-inhibitor-meta-analysis) | **Evidence:** random-effects meta-analysis of 13 outcome trials (90,413 patients). Pooled HR 0.78 for CV death or HF hospitalisation, consistent across diabetes, CKD and HF | R · metafor |

#### Clinical prediction and prognosis

| Project | What it does | Stack |
|---|---|---|
| [**heart-failure-survival**](https://github.com/alirezajavan-sys/heart-failure-survival) | Cox survival analysis of advanced heart failure with optimism-corrected C-index. Exposes a common outcome-leakage error in public analyses of this dataset | Python · lifelines |
| [**diabetes-risk-prediction**](https://github.com/alirezajavan-sys/diabetes-risk-prediction) | Type 2 diabetes risk model judged on discrimination, **calibration and net benefit**. Shows that a transparent logistic model matches ML on AUROC and is better calibrated | Python · scikit-learn |
| [**pbc-survival-analysis**](https://github.com/alirezajavan-sys/pbc-survival-analysis) | Survival analysis of the Mayo Clinic PBC trial: treatment effect, competing risks (death vs transplant), and re-derivation and validation of the Mayo risk score | R · survival · ggplot2 |

#### Tools and drug discovery

| Project | What it does | Stack |
|---|---|---|
| [**cardiovascular-in-silico-platform**](https://github.com/alirezajavan-sys/cardiovascular-in-silico-platform) | Reference implementation of an integrated drug-discovery platform: multi-target virtual screening, GNN hERG-cardiotoxicity prediction, dual-target generative design, network pharmacology and MIMIC-IV clinical cross-validation (*Scientific Reports*, under revision) | Python · RDKit · PyTorch Geometric · AutoDock Vina · GROMACS |
| [**ckd-toolkit**](https://github.com/alirezajavan-sys/ckd-toolkit) | Tested, dependency-free Python package: race-free CKD-EPI 2021 eGFR, KDIGO staging and the Kidney Failure Risk Equation, with a CLI | Python · pytest · GitHub Actions |

### 🛠️ Tools I work with

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![RDKit](https://img.shields.io/badge/RDKit-cheminformatics-0b7285)
![ggplot2](https://img.shields.io/badge/ggplot2-visualisation-276DC3)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

### 📚 Reporting standards I follow

PRISMA (meta-analyses) · TRIPOD (prediction models) · STROBE (observational studies) · CONSORT (trials) · FAIR data principles

---

<sub>All projects use public, de-identified data or code only. No patient-identifiable information is ever stored in these repositories.
Code is for research and education and is not a medical device.</sub>
