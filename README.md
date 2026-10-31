# Probability and Neural Network Fundamentals

A growing, hands-on project for learning probability, statistics, and the mathematical ideas behind neural networks. The material will expand over time, with notebooks that explain concepts through small Python examples and visualizations.

## Current contents

| File | Description |
| --- | --- |
| [`probability_foundations.ipynb`](./probability_foundations.ipynb) | Calculates probabilities from a sequence of activities, prints the results, and visualizes them in a bar chart. |

The current example estimates each activity's probability as its observed count divided by the total number of observations. For the sample data, walking has probability 37.5%, running and cycling each have 25%, and swimming has 12.5%.

## Getting started

### Requirements

- Python 3
- Jupyter support, such as Jupyter Notebook, JupyterLab, or the Jupyter extension in Visual Studio Code
- `numpy` and `matplotlib`

Install the Python packages in a terminal:

```bash
python -m pip install numpy matplotlib
```

### Run the notebook

1. Open `probability_foundations.ipynb` in Jupyter or Visual Studio Code.
2. Select a Python 3 kernel.
3. Run the cells from top to bottom so the imports, sample data, and probability calculation are available to the visualization cell.

## Learning path

This project is intended to develop incrementally. Possible next topics include:

1. Probability rules, sample spaces, and events
2. Conditional probability and Bayes' theorem
3. Random variables and common probability distributions
4. Descriptive statistics, sampling, and data visualization
5. Vectors, matrices, and derivatives
6. Neural network building blocks, training, and evaluation

These are planned learning directions, not a promise that every topic is already implemented. As the project grows, this README can be updated with links to new notebooks and a short description of each.

## Project structure

```text
probability_neural_network_fundamentals/
├── README.md
└── probability_foundations.ipynb
```

## Notes

- The examples are educational and use small, illustrative datasets.
- A probability calculated from observed data describes that sample; it is not necessarily the true probability of an event in a larger population.
- Notebook outputs may depend on the order in which cells are run. If variables are missing or stale, restart the kernel and run all cells from the beginning.
