# Assessment Submission

This repository contains my submission for the Applied Statistics assessment.
The work is completed in `problems.ipynb` and uses the Iris dataset stored in
`data/iris.csv`.

## Assessment overview

The notebook explores the relationship between petal measurements across the
150 observations in the Iris dataset. It uses descriptive statistics, probability
distributions, correlation analysis, and visualisations to answer two main
problems:

1. **Exploring petal length**
   - Plot the distribution of petal length for all flowers.
   - Superimpose a normal distribution using the sample mean and standard
     deviation.
   - Compare the distributions for the setosa, versicolor, and virginica
     species.
   - Calculate and interpret the mean and standard deviation.

2. **Correlation between petal length and petal width**
   - Calculate Pearson's correlation coefficient for all flowers.
   - Create a scatter plot with a fitted trend line.
   - Calculate correlations separately for each species.
   - Compare species-specific scatter plots and trend lines.

## Project files

- `problems.ipynb` - the assessment notebook containing code, plots, calculations,
  and written interpretations.
- `data/iris.csv` - the Iris dataset with 150 observations and the variables
  `sepal_length`, `sepal_width`, `petal_length`, `petal_width`, and `species`.
- `requirements.txt` - the Python packages required for the assessment.
- `AGENTS.md` - repository-specific guidance for AI-assisted work.

## Dataset

The dataset contains measurements for 50 flowers from each of three Iris species:

- Setosa
- Versicolor
- Virginica

Each row contains one flower's two sepal and two petal measurements. The
analysis mainly focuses on petal length and petal width.

## Requirements

The notebook uses Python with pandas, NumPy, Matplotlib, SciPy, and optionally
Seaborn. Install the project dependencies with:

```bash
pip install -r requirements.txt
```

## Running the notebook

From the repository root, start Jupyter with:

```bash
jupyter notebook
```

Then open `problems.ipynb`. It is designed to be run from the repository root
because `data/iris.csv` is loaded with a relative path.

You can also run the notebook in VS Code by opening `problems.ipynb` and
choosing a Python kernel. If the required packages are not available, install
the dependencies listed in `requirements.txt` first.

## Main methods

- **Histogram:** Displays the frequency distribution of petal lengths.
- **Normal curve:** Uses the sample mean and standard deviation to show the
  shape expected from a normal distribution.
- **Descriptive statistics:** Reports the mean and standard deviation for
  overall and species-specific distributions.
- **Pearson correlation:** Measures the strength and direction of the linear
  relationship between petal length and petal width.
- **Scatter plots and trend lines:** Visualise petal measurements and fitted
  linear relationships.
