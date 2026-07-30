# Deriving and Implementing Gradient-Based Learning

This project implements Linear Regression and a one-hidden-layer ReLU neural network from scratch with NumPy. Both models use manually derived gradients and full-batch Gradient Descent. The executed notebook contains the code, results, and graphs; the PDF contains the written report.

## Required packages

- NumPy
- Matplotlib
- Notebook
- nbconvert

Install them with:

```powershell
python -m pip install -r requirements.txt
```

## Open and run the notebook

Open it interactively:

```powershell
python -m notebook gradient_based_learning.ipynb
```

Recommended order: restart the kernel, run all cells from top to bottom, and then save the notebook. For command-line execution:

```powershell
python -m nbconvert --to notebook --execute --inplace gradient_based_learning.ipynb --ExecutePreprocessor.timeout=120
```

## Included files

- `gradient_based_learning.ipynb` - executed implementation, results, and graphs
- `report.pdf` - three-page written report
- `results.json` - numerical results from the notebook
- `requirements.txt` - required Python packages
- `figures/` - five saved visualization files
