## Team 2 Stocks Analysis

Group Members: 
- Samson Xu
- Pranav Singh
- Colby Tran
- Cristian Navarro

## Notebooks
- `notebooks/01_stock_feature_engineering.ipynb` : explore the data and perform basic transformations and visualizations 
- `notebooks/02_stock_transforms_groups_visuals.ipynb` : transforms, groupby aggregations, seaborn visuals, and linear regression for AAPL
- `notebooks/03_stock_advanced_visuals.ipynb` : additional visualizations to help with analysis: lineplot & heatmap

## Data Setup
See `data/README.md` for download instructions.
- note: data set cannot be pushed due to the large file size. 

## Set up environment via IDE buttons (easiest):
- In the notebook environment / directory (ie: `notebooks/02_stock_transforms_groups_visuals.ipynb`), press 'Select Kernel' located on the top right of the notebook. Select 'Python Environments', then select the `.venv` kernel created from the Quick Start.
- install dependencies via `pip install -r requirements.txt`.
- run a cell

## Set up environment via Terminal:
- From the `CS122` repo root (do not `cd notebooks` first).

### macOS / Linux (zsh or bash)
```bash
# create & activate a venv
python3 -m venv .venv
source .venv/bin/activate

# install dependencies
pip install -r requirements.txt

# register this venv as a Jupyter kernel (one-time setup)
python -m ipykernel install --user --name cs122-venv --display-name "Python (.venv - CS122)"

# open notebook directly (no VS Code environment button needed)
jupyter notebook notebooks/02_stock_transforms_groups_visuals.ipynb

# or start Jupyter Lab
jupyter lab
```

### Windows (PowerShell)
```powershell
# create & activate a venv
python -m venv .venv
.venv\Scripts\Activate.ps1

# install dependencies
pip install -r requirements.txt

# register this venv as a Jupyter kernel (one-time setup)
python -m ipykernel install --user --name cs122-venv --display-name "Python (.venv - CS122)"

# open notebook directly (no VS Code environment button needed)
jupyter notebook notebooks/Project_Assignment_02.ipynb

# or start Jupyter Lab
jupyter lab
```
## How to run
- Open the notebook(s) and run cells top-to-bottom. Select the `.venv` Python kernel in VS Code / Jupyter so packages match `requirements.txt`.

## Dependencies
- See `requirements.txt`
