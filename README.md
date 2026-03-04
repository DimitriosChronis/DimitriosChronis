# Dimitrios Chronis

**Civil Engineer · Quantitative Risk Analyst · RICS Student Member**
National Technical University of Athens (NTUA) · Athens, Greece

[![ORCID](https://img.shields.io/badge/ORCID-0009--0001--9557--4175-brightgreen?logo=orcid)](https://orcid.org/0009-0001-9557-4175)
[![RICS](https://img.shields.io/badge/RICS-Student%20Member-003D6B)](https://www.rics.org)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org)


---

## About

I bridge **structural engineering** and **quantitative finance** — applying stochastic modeling, copula theory, and machine learning to construction cost risk.

Currently a 3rd-year Civil Engineering student at NTUA, I work concurrently as a Quantity Surveyor & Risk Engineer on public infrastructure projects (€15M+) and conduct independent academic research on tail dependence in construction cost overruns.

---

## Research

### From Statistical Error to Profit Erosion (2026)
> *Quantifying Tail Dependence in Construction Cost Overruns using Gumbel Copulas*
> Target: **ASCE Journal of Construction Engineering and Management**

Standard industry models assume Gaussian dependence between construction material prices — a structural flaw that hides catastrophic risk during crises. Using 24 years of Greek ELSTAT data and 100,000 Monte Carlo simulations, this study quantifies a **EUR 45,806 hidden risk gap** at P85 during the 2021-2024 energy crisis — equivalent to **38–48% erosion of contractor net profit margins**.

[![Repo](https://img.shields.io/badge/Code-quant--risk--copula-181717?logo=github)](https://github.com/DimitriosChronis/quant-risk-copula)
[![Status](https://img.shields.io/badge/Status-Ready%20for%20Submission-yellow)]()

**Key results:**
- Gumbel copula (θ=6.67, λU=0.80) outperforms Gaussian by AIC/BIC in Crisis Regime
- R-Vine robustness check: Δ = 0.04% at P85
- Bootstrap 95% CI (full period): [EUR 14,498 ; EUR 25,971]
- Egnatia Odos retrospective: 0.80% material-cost tail premium per contract phase

---

## Stack

```python
# Core toolkit
import numpy as np          # Stochastic simulation
import pandas as pd         # Time-series processing
import scipy.stats          # MLE, Kendall tau, Jarque-Bera
import pyvinecopulib        # R-Vine copula (pinned 0.7.5)
import matplotlib.pyplot    # Publication figures (300 DPI)
import statsmodels          # ARIMA, VAR (Paper 2)
import sklearn              # Isolation Forest, ML pipelines
import torch                # Deep learning (Paper 3 - LSTM)
```

| Domain | Tools |
|---|---|
| Risk Modeling | Monte Carlo, Gumbel/Vine Copulas, VaR, P85/P99 |
| Structural | ETABS, AutoCAD, Revit (BIM), Civil3D |
| Data | Python, MATLAB, SQL, QGIS |
| Project Controls | MS Project, BoQs, Navisworks |

---

## Experience

**AIRKAM ATEE** — Quantity Surveyor & Risk Engineer *(Sept 2023 – Present)*
Public infrastructure projects (€15M+), Chalkida & Corinthia · Probabilistic risk assessments · Budget control under public work contracts

**CHRONIS GROUP** — Commercial Manager & Project Lead *(Sept 2023 – Present)*
Residential & PV infrastructure · Value engineering · Client advisory

**CERN HSSIP** — Engineering Intern *(Sept 2021)*
Top 25 nationwide selection · Particle detection systems · Safety protocol simulations

---

## Education & Certifications

🎓 **NTUA** — Diploma in Civil Engineering (Integrated M.Eng.), Expected 2028
🏛️ **Università Bocconi** — Financing and Investing in Infrastructure
⚖️ **Yale University** — American Contract Law I
🏗️ **Columbia University** — Construction Management Specialization
📊 **IBM** — Data Analysis & Visualization (Certified)
🏅 **RICS** — Student Member

**Awards:** High School Valedictorian (19.9/20) · Eurobank Scholarship · G.A. Mavroulias Foundation Scholarship

---

## Languages

🇬🇧 English — C2 (ECPE Proficiency)
🇫🇷 French — B2 (DELF)
🇬🇷 Greek — Native

---

*"The contingencies were calibrated for a Gaussian world — not a Gumbel one."*
