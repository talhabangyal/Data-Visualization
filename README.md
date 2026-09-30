# Data Visualization

Coursework and lecture materials for the Data Visualization course.

## Assignment 1

Assignment 1 is implemented as five Jupyter notebooks. Each notebook contains the data preparation, charts, and written interpretation required by `Assignment 1/TASKS.md`.

| Notebook | Topic |
| --- | --- |
| `task1.ipynb` | Summary statistics and the Datasaurus datasets |
| `task2.ipynb` | Life-expectancy trends and the spaghetti problem |
| `task3.ipynb` | Penguin distributions, relationships, and Simpson's paradox |
| `task4.ipynb` | Choosing charts for the `mpg` dataset |
| `task5.ipynb` | Airline passenger trends and seasonality |

### Run the assignments

Install the notebook dependencies:

```bash
pip install pandas numpy matplotlib jupyter ipykernel
```

Open a notebook from the Assignment 1 directory so its relative `data/` path resolves correctly:

```bash
cd "Assignment 1"
jupyter notebook
```

The assignment datasets are already included in `Assignment 1/data/`. To download fresh copies, run:

```bash
python download_assignment_data.py
```

## Week 1

The `week1/` folder contains the executed lecture notebook, lecture datasets, exported charts, and the Assignment 1 brief.
