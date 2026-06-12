# Thesis B Framework

## First-Time Setup

Create the virtual environment in the project root directory:

```powershell
python -m venv .venv
```

Activate the virtual environment:

```powershell
.\.venv\Scripts\Activate.ps1
```

The terminal should now start with:

```text
(.venv)
```

Install required packages:

```powershell
python -m pip install numpy scipy matplotlib pandas control jupyter ipykernel
```

Install the Jupyter kernel:

```powershell
python -m ipykernel install --user --name thesis-framework
```

Create a notebook folder:

```powershell
mkdir notebooks
```

## Daily Use

Go to the project root directory:

```powershell
cd C:\Users\smayb\Desktop\THESIS\THESIS_B
```

Activate the virtual environment:

```powershell
.\.venv\Scripts\Activate.ps1
```

Run Python scripts from the project root directory:


Deactivate when finished:

```powershell
deactivate
```

## Jupyter Notebooks in VS Code

Open VS Code.

Open the project folder:

```text
C:\Users\smayb\Desktop\THESIS\THESIS_B
```

Create a new notebook file inside the `notebooks` folder:

```text
notebooks/exploration.ipynb
```

Open `exploration.ipynb`.

At the top right of the notebook, click **Select Kernel**.

Choose:

```text
thesis-framework
```

If `thesis-framework` does not show up, close and reopen VS Code, then try **Select Kernel** again.

Test the notebook by running this in the first cell:

```python
import numpy as np
import matplotlib.pyplot as plt

print("Notebook is working")
```