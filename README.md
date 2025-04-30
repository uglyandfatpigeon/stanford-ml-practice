# Stanford ML – Practical Exercises

This repository contains hands-on coding exercises accompanying the [Stanford/Coursera course](https://www.coursera.org/learn/machine-learning) “Supervised Machine Learning: Regression and Classification”.

The goal is to deepen your understanding by implementing key concepts in Python using real-world datasets.

---

## ✅ Environment Setup

This project uses [Mambaforge](https://github.com/conda-forge/miniforge) (a fast Conda-compatible Python package manager) for environment management.

### 1. Install Mambaforge (macOS ARM64 – Apple Silicon)

Download and run the installer:

```bash
curl -L https://github.com/conda-forge/miniforge/releases/download/23.11.0-0/Mambaforge-MacOSX-arm64.sh -o Mambaforge.sh
chmod +x Mambaforge.sh
bash Mambaforge.sh
```

After installation, restart your terminal or run:

```bash
source ~/.bash_profile   # or ~/.zshrc depending on your shell
```

---

### 2. Create and activate the project environment

```bash
mamba env create -f environment.yml
mamba activate stanford-ml
```

### 3. Register the environment for use with Jupyter

```bash
python -m ipykernel install --user --name=stanford-ml --display-name "Python (stanford-ml)"
```

---

## 🚀 Launch JupyterLab

```bash
jupyter lab
```

> In the notebook, select kernel: **Python (stanford-ml)**

---

## 📂 Project structure

```
stanford-ml-praktyka/
├── environment.yml              # Environment definition
├── README.md                    # This file
└── notebooks/
    └── 01_regression_baseline.ipynb   # First regression notebook
```

---

## 📚 Dependencies

The environment includes:

- Python 3.11
- numpy, pandas
- scikit-learn
- matplotlib, seaborn
- jupyterlab, ipykernel

See `environment.yml` for exact package definitions.

---

## 💡 Notes

This is a parallel practice track to the Stanford Supervised ML course and is intended to apply theoretical knowledge through practical implementation and experimentation.
