# Hi, I'm Pamela 👋🏽

**Computational Physicist → ML/Data Science for Materials**  
Postdoctoral Researcher @ Uppsala University · PhD in Physics (USP) · MBA in Data Science (ESALQ/USP)

I build end-to-end pipelines that turn physics simulations into predictive ML models — from raw HPC outputs to published datasets and production-ready tools.

---

## 🔬 What I do

- **ML for Materials Science** — Graph Neural Networks, Random Forest and Gradient Boosting to predict structural and electronic properties of materials
- **High-throughput workflows** — automated pipelines for large-scale first-principles simulations on HPC clusters (SLURM, Python, YAML-driven)
- **Data engineering** — from simulation output → structured dataset → publication. Built and released [TBHubbard](https://doi.org/10.7910/DVN/ZKLRLF), a 10,000+ MOF database published in *Nature Scientific Data*
- **Predictive modelling** — correcting systematic DFT errors in formation enthalpies using ML (active research, Uppsala University)
- **MLOps / production ML** — packaging research models into APIs, dashboards, Docker, CI, and AWS-hosted demos

---

## 🚀 Featured Projects

### [EMTOFlow](https://github.com/pcostacarvalho/emtoflow)
> Python toolkit for automating high-throughput EMTO physics simulations on HPC clusters

- Single YAML config drives input generation, parameter sweeps, SLURM scheduling and results extraction
- Designed for reproducibility and scalability across hundreds of concurrent jobs
- `Python` · `pandas` · `scipy` · `matplotlib` · `SLURM`

### [TBHubbard ML Analysis](https://github.com/pcostacarvalho/tbhubbard-ml-analysis)
> Predicting Hubbard U and V parameters in MOFs using the dataset I built and published

- Benchmarked Linear Regression and Random Forest against DFT reference values on 464,509+ pair-level observations from 242 MOFs
- Best model for U: **Linear Regression** (R² = 0.970, MAE = 0.181 eV); best model for V: **Random Forest** (R² = 0.782, MAE = 0.026 eV)
- Full pipeline: EDA → preprocessing (IQR outlier filtering, VIF multicollinearity check, group-aware train/test split) → modelling → evaluation
- Based on the [TBHubbard dataset](https://doi.org/10.7910/DVN/ZKLRLF) — 785+ downloads since release
- `scikit-learn` · `statsmodels` · `pandas` · `matplotlib` · `seaborn`

### [TBHubbard Production](https://github.com/pcostacarvalho/tbhubbard-production)
> From thesis notebooks to a deployable ML system: train → register → serve → demo

- Serves U/V Hubbard predictions with **MLflow** model registry (`@champion`), **FastAPI**, and a **Streamlit** dashboard (Explore / Predict live / Prediction log)
- Containerized with **Docker Compose** and deployed on **AWS EC2**; GitHub Actions CI (train → pytest → image build)
- Live demo: [dashboard](http://98.92.201.17:8501) · [walkthrough video](https://youtu.be/954mYFDQLuc)
- Built on top of [TBHubbard ML Analysis](https://github.com/pcostacarvalho/tbhubbard-ml-analysis)
- `scikit-learn` · `MLflow` · `FastAPI` · `Streamlit` · `Docker` · `AWS EC2` · `pytest` · `GitHub Actions`

---

## 📄 Selected Publications

| Year | Work | Journal |
|------|------|---------|
| 2025 | [TBHubbard: tight-binding and Hubbard parameters for 10,000+ MOFs](https://www.nature.com/articles/s41597-025-06054-w) | *Nature Scientific Data* |
| 2025 | [Proximity-induced flipped spin state in Pt/Co/Gd heterolayers](https://www.nature.com/articles/s41467-025-56040-6) | *Nature Communications* |
| 2023 | [Interface interdiffusion and skyrmionic phases](https://pubs.acs.org/doi/10.1021/acs.nanolett.3c00428) | *Nano Letters* |

---

## 🧰 Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-3776AB?style=flat&logo=python&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-web-services&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![HPC](https://img.shields.io/badge/HPC-0071C5?style=flat&logo=intel&logoColor=white)

---

## 📊 GitHub Stats

<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=pcostacarvalho&show_icons=true&theme=default&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pcostacarvalho&layout=compact&theme=default&hide_border=true" />
</p>

---

## 🏅 Recognition

- 🥇 **Best Physics Phd Thesis in 2025** — awarded by the Physics Institute in the University of São Paulo
- 🥇 **Bernard Gross Prize** — Best oral presentation, XXI B-MRS Meeting (Brazilian Materials Research Society, 2023)
- 🔬 Research internships at **IBM Research Brazil** and **Uppsala University** during PhD

---

## 📬 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pamela-costa-carvalho)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:pamelacosta.res@gmail.com)
