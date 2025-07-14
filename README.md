# sleap-bombus-castes
Python code used for 'Caste-Specific Vulnerability: Pesticide Exposure Differentially Impacts Caste Development and Colony Performance in Bumblebees'

# 🐝 Bumblebee Behavior Analysis from SLEAP Tracking

This repository contains Python code for analyzing the behavior of *Bombus impatiens* individuals tracked using [SLEAP](https://sleap.ai/), a deep learning-based multi-animal pose tracking toolkit. The analyses focus on thorax movement to assess behavioral metrics such as velocity, rest time, distance traveled, and inter-individual interactions.

---

## 📂 Repository Contents

- `analyze_sleap_behavior.py` – Main analysis script (can also be converted to a Jupyter/Colab notebook)
- `README.md` – This documentation

---

## 🧪 Purpose

This script was developed to analyze and visualize behavior of individual bumblebees tracked in experimental arenas using SLEAP. The code was used in analyses for the manuscript:

> **"Caste-Specific Vulnerability: Pesticide Exposure Differentially Impacts Caste Development and Colony Performance in Bumblebees"** (Under Review)

---

## 📊 Behavioral Metrics Calculated

- **Thorax tracks** (X-Y coordinates over time)
- **Average velocity** and **standard error** per bee
- **Total distance traveled**
- **Time spent moving** (above velocity threshold)
- **Time spent resting** (below velocity threshold)
- **Speed variability**
- **Pairwise interaction frequency** (based on proximity)

All metrics are visualized with appropriate plots using `matplotlib` and `seaborn`.

---

## 🛠 Requirements

Install the required Python packages using pip:

```bash
pip install numpy matplotlib seaborn h5py scipy

