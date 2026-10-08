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

Assignment 2 investigates **visual perception**, cognitive load, and human visual processing constraints (CLO1: *Identify how the human brain processes visual information*). Implemented as five fully executed Jupyter notebooks in `Assignment 2/` adhering to the specifications in `Assignment 2/TASKS.md` and `week2/README.md`.

| Notebook | Topic | Data | Key Concepts & Findings |
| --- | --- | --- | --- |
| `task1.ipynb` | Preattentive attributes and visual search | `stimuli_search.csv` | Parallel search (flat slopes: Colour ~0.4 ms/item, Shape ~0.7 ms/item) vs. serial conjunction search (steep slope: ~23.9 ms/item) tested on human observer; Feature Integration Theory; accidental conjunction pitfalls. |
| `task2.ipynb` | Gestalt principles of grouping | `stimuli_gestalt.csv`, `tips.csv` | Empirical evaluation of Proximity, Similarity, Enclosure, Continuity, Closure, and Connection; perceptual competition proving Connection beats Proximity and Similarity; Proximity manipulation in bar charts; direct labelling vs. legends. |
| `task3.ipynb` | Cognitive load and the data-ink ratio | `car_crashes.csv`, `tips.csv` | Classification of Intrinsic, Extraneous, and Germane load; data-ink ratio working (~13.1%); 5-panel progressive decluttering; 4 ± 1 regional chunking; over-stripping failure and stopping rule; adding ink to lower cognitive load. |
| `task4.ipynb` | Channel effectiveness, measured | `channel_trials.csv`, `iris.csv` | Empirical reproduction of Cleveland & McGill hierarchy (Position < Length < Angle < Area < Colour); Stevens' power law area underestimation; application to Iris petal length; single-subject statistical limitations vs. psychophysical laws. |
| `task5.ipynb` | Capstone: Redesigning for the human visual system | `gapminder.csv` | Full perception audit of 142-country spaghetti chart; single-message redesign highlighting Rwanda's 1994 crisis and recovery; 1 pop-out element; grey context; verbatim reader testing; 300 DPI export (`perception_redesign.png`). |

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
