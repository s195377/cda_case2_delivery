# CDA_case_2
Computational data analysis report spring 2026, DTU

## Setup

### Option A — Conda (recommended)

```bash
conda env create -f environment.yml
conda activate cda_case_2
```

To update the environment after pulling new changes:

```bash
conda env update -f environment.yml --prune
```

### Option B — pip (virtualenv)

```bash
python -m venv .venv
source .venv/bin/activate      # macOS/Linux
# .venv\Scripts\activate       # Windows
pip install -r requirements.txt
```

### Running the notebook

Open `main.ipynb` in VS Code and select the `cda_case_2` kernel (conda) or `.venv` kernel (pip).
