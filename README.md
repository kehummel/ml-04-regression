# ml-04-regression

[![Workflow Guide](https://img.shields.io/badge/Pro--Guide-pro--analytics--02-green)](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
[![Python 3.14](https://img.shields.io/badge/python-3.14%2B-blue?logo=python)](./pyproject.toml)
[![MIT](https://img.shields.io/badge/license-see%20LICENSE-yellow.svg)](./LICENSE)

> Professional Python project: building and evaluating regression models.

## Project Description

This project focuses on learning to build models that predict a number.

We learn to:

- train and evaluate a regression model
  (e.g., linear regression, decision tree regressor)
- read regression metrics: MAE, RMSE, R^2
- interpret what the model learned
- compare models and choose the better one

## Example Notebook

Links:

- [ml_04_case.ipynb](notebooks/ml_04_case.ipynb)

## Working Files

You'll work with these areas:

- **data/raw** - raw data for exploration (only if you add a dataset)
- **docs/** - project narrative and documentation
- **src/mlstudio/** - the app is an example; run only (no need to modify)
- **notebooks/** - interactive analysis
- **pyproject.toml** - update authorship & links
- **zensical.toml** - update authorship & links

## Instructions (pro-analytics-02)

Follow the
[step-by-step workflow guide](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to complete:

1. Phase 1. **Start & Run**
2. Phase 2. **Change Authorship**
3. Phase 3. **Read & Understand**
4. Phase 4. **Modify**
5. Phase 5. **Apply**


### In a machine terminal (open in your `Repos` folder)

After you get a copy of this repo in your own GitHub account,
open a machine terminal in your `Repos` folder:

```shell
# Replace username with YOUR GitHub username.
git clone https://github.com/kehummel/ml-04-regression

cd ml-04-regression
code .
```

### In a VS Code terminal

These are listed for convenience.
For best results, follow the detailed instructions in
[pro-analytics-02 guide](https://denisecase.github.io/pro-analytics-02/).


## Findings and Visuals

### Phase 4
In phase 4 I made a technical change to the example notebook. I changed the data used from 'penguins' to 'taxis' from the seaborn library.
I calculated the relationship between the distance and the fare (price in dollars).
I used the RMSEs for the training and testing data to confirm 1 degree, a linear equation, was the best fit.
This was also proven when we looked at the residuals vs predicted dot plot.


(./docs/images/04 - P4 Residuals vs Predicted.png)

(./docs/images/04 - P4 RMSE.png)

### Phase 5
In phase 5, we created regression models first for different cases in which we were trying to predict the fare cost for all of them.
Then we compared different regression models.
Finally we looked at the degrees of a polynomial regression model.

Comparing 6 Cases, trying to predict the fare cost:
(./docs/images/04_P5_models_per_case.png)

Comparing 4 regression models:
(./docs/images/04_P5_comparing_regression_models.png)

## Project Documentation

[docs/index.md](docs/index.md)

[Phase 4 Notebook: ml_04_regression_hummel](notebooks/ml_04_regression_hummel.ipynb)

[Phase 5 Notebook: ml04_hummel](notebooks/04 project/ml04_hummel.ipynb)

## Citation

[CITATION.cff](./CITATION.cff)

## License

[MIT](./LICENSE)
