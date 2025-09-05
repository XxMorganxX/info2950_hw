# INFO 2950 — Homework 1: Forest Fires Analysis

This project contains the notebook and supporting data for Homework 1. It analyzes the Forest Fires dataset and includes exploratory analysis and modeling. Pre-rendered HTML and PDF versions of the notebook are included for quick viewing.

## Repository contents

- `HW1_FA2025.ipynb` — Main Jupyter notebook
- `forest-fires.csv` — Input dataset (Forest Fires)
- `HW1_FA2025.html` — Rendered HTML version of the notebook
- `HW1_FA2025.pdf` — Rendered PDF version of the notebook
- `venv/` — Optional local Python virtual environment (you may use your own)

## Requirements

- Python 3.9+ (3.10/3.11 recommended)
- Jupyter and common scientific Python packages
  - pandas, numpy, matplotlib, seaborn, scikit-learn

If any packages are missing when you run the notebook, install them with pip as shown below.

## Quick start

Option A — Use the existing `venv/` (if present):

```bash
source venv/bin/activate
python -m pip install -U pip
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

Option B — Create your own environment (recommended if `venv/` is not usable):

```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\\Scripts\\activate
python -m pip install -U pip
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

## Run the notebook

Interactive session:

```bash
jupyter lab   # or: jupyter notebook
```

Then open `HW1_FA2025.ipynb` and run all cells.

Headless (execute and update the notebook in place):

```bash
python -m jupyter nbconvert --to notebook --execute --inplace HW1_FA2025.ipynb
```

## Export outputs

Rebuild the HTML export:

```bash
python -m jupyter nbconvert --to html HW1_FA2025.ipynb --output HW1_FA2025.html
```

Rebuild the PDF export (requires a LaTeX installation such as TeX Live or MiKTeX):

```bash
python -m jupyter nbconvert --to pdf HW1_FA2025.ipynb --output HW1_FA2025.pdf
```

## Data

The dataset `forest-fires.csv` is included locally for convenience. See the notebook for a brief description of the variables and any preprocessing steps applied.

## Notes

- If you prefer Conda, create an environment and install the same packages with `conda install` or `mamba install`.
- If PDF export fails due to missing LaTeX, use the included `HW1_FA2025.html` or view the notebook directly.


