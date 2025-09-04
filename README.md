# Survival Analysis of Veteran Cancer Patients

This project applies **survival analysis** methods to a veteran lung cancer dataset using **R**.
The notebook demonstrates statistical modeling and visualization of survival data.

---

## 📊 Project Description

The goal is to explore patient survival time and assess prognostic factors.
Steps include:

1. **Dataset Overview** – Veteran lung cancer data with clinical variables.
2. **Kaplan–Meier Estimation** – Survival probability curves.
3. **Cox Proportional Hazards Model** – Assess influence of covariates.
4. **Visualization** – Plot survival curves, hazard ratios, and confidence intervals.

---

## 🛠️ Requirements

This project requires **R** (≥ 4.0) and the following packages:

* `survival`
* `survminer`
* `ggplot2`

---

## 🚀 Usage

Clone this repository and open the notebook:

```bash
git clone https://github.com/MihaiBudurean/SurvivalAnalysisVeteranCancer.git
cd SurvivalAnalysisVeteranCancer
```

Then, open `SurvivalAnalysisVeteranCancer.ipynb` in Jupyter with the **IRkernel** (R kernel).

To install the required R packages:

```r
install.packages(c("survival", "survminer", "ggplot2"))
```

---

## 📈 Results

* Survival curves for different patient groups
* Kaplan–Meier estimation of survival probabilities
* Cox model showing significant covariates affecting survival time

---

## 📂 Files

* `SurvivalAnalysisVeteranCancer.ipynb` – Main notebook with analysis and results
* `README.md` – Project documentation

