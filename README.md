# Online Machine Learning Lab

This project studies online regression, classification, drift detection, and performs comparisons using Riverm and CapyMOA.


## Running the work

Clone the repository and enter its directory:

```bash
git clone https://github.com/coulibalyadama/lab-online-machine-learning.git
cd lab-online-machine-learning
```

Create the Python environment from `pyproject.toml` and `uv.lock`:

```bash
uv sync
```

Open `notebook.ipynb` in VS Code or Jupyter, select the created environment, and run the cells from top to bottom. The notebook uses a fixed seed and evaluates models with prequential test-then-train processing. The report can be compiled with a LaTeX installation after the notebook has been executed.