# ISLP — Exercises for "An Introduction to Statistical Learning" (Python)

This repository contains a collection of Jupyter notebooks that implement and exercise the material from "An Introduction to Statistical Learning" (ISL), translated and adapted for Python (ISLP). The notebooks are organized by chapter under the `exercises/` directory. Each chapter folder includes a `README.md` with direct links to the chapter's exercise notebooks.

Repository highlights

- Organized collection of exercises and applied notebooks for ISL topics.
- Each chapter has a dedicated `README.md` linking to conceptual and applied exercises.
- Notebooks are intended for interactive use in Jupyter Notebook or JupyterLab.

Quick start

1. Clone the repository:

```bash
git clone https://github.com/youssefnoob003/ISLP.git
cd ISLP
```

2. Create a Python environment (recommended using conda) and install essentials:

```bash
# using conda (recommended)
conda create -n islp python=3.10 -y
conda activate islp
pip install jupyterlab numpy pandas matplotlib seaborn scikit-learn statsmodels notebook

# or using pip/venv
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install ISLP
```

3. Start JupyterLab or Jupyter Notebook and open the notebooks under `exercises/`:

```bash
jupyter lab    # or: jupyter notebook
```

Chapter index

The following links will take you to each chapter's exercise index (each index lists the notebooks for that chapter):

- [Chapter 2 exercises](exercises/chapter2/README.md)
- [Chapter 3 exercises](exercises/chapter3/README.md)
- [Chapter 4 exercises](exercises/chapter4/README.md)
- [Chapter 5 exercises](exercises/chapter5/README.md)
- [Chapter 6 exercises](exercises/chapter6/README.md)
- [Chapter 7 exercises](exercises/chapter7/README.md)
- [Chapter 8 exercises](exercises/chapter8/README.md)
- [Chapter 9 exercises](exercises/chapter9/README.md)
- [Chapter 10 exercises](exercises/chapter10/README.md)
- [Chapter 11 exercises](exercises/chapter11/README.md)
- [Chapter 12 exercises](exercises/chapter12/README.md)

Contributing

If you would like to contribute corrections, improvements, or additional notebooks, please open a pull request. Include a short description of the change and link to any related issues.
