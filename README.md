# Data Visualization

**Student Name:** Talha Abdullah Bangyal  
**Course:** Data Visualization
**Roll Number:** SU92-BAIFM-F25-002
**Section:** BS(AI)-7C
**Department:** Software Engineering

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

## Assignment 2

Assignment 2 applies principles of visual perception and cognitive processing to five fully executed Jupyter notebooks in `Assignment 2/`.

| Notebook | Topic | Data | Key Concepts & Findings |
| --- | --- | --- | --- |
| `task1.ipynb` | Preattentive attributes and visual search | `stimuli_search.csv` | Renders colour, shape, and conjunction search trials, measures observer response times, compares search slopes against set size, and explains accidental conjunctions. |
| `task2.ipynb` | Gestalt principles of grouping | `stimuli_gestalt.csv`, `tips.csv` | Demonstrates Proximity, Similarity, Enclosure, Continuity, Closure, and Connection; records observer grouping responses; and applies proximity to grouped bar charts. |
| `task3.ipynb` | Cognitive load and the data-ink ratio | `car_crashes.csv`, `tips.csv` | Classifies intrinsic, extraneous, and germane load; calculates data-ink; progressively declutters an overloaded chart; applies regional chunking; and shows when additional reference ink reduces cognitive load. |
| `task4.ipynb` | Channel effectiveness, measured | `channel_trials.csv`, `iris.csv` | Compares Position, Length, Angle, Area, and Colour through observer trials, ranks channels by mean absolute error, and applies the results to an Iris petal-length chart. |
| `task5.ipynb` | Redesigning for the human visual system | `gapminder.csv` | Audits a 142-country spaghetti chart, redesigns it around Rwanda's 1994 life-expectancy collapse and recovery, tests the message with an observer, and exports `perception_redesign.png`. |

### Run Assignment 2

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter ipykernel
```

Open a notebook from the `Assignment 2` directory so relative `data/` paths resolve correctly:

```bash
cd "Assignment 2"
jupyter notebook
```

Datasets and generated stimuli files (`SEED = 42`) are located in `Assignment 2/data/`. To re-download or regenerate fresh copies, run:

```bash
python download_assignment_data.py
```

Generated outputs include:
- `search_results.csv`: Empirical reaction times from 18 search trials.
- `channel_results.csv`: Empirical ratio estimates and absolute error across 30 perceptual channel trials.
- `perception_redesign.png`: 300 DPI publication-grade figure of the Gapminder life expectancy redesign.
