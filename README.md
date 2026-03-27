# Individual-coursework-Machine-Learning-Tutorial
Assessment 1

## Gaussian Process Classification Tutorial Submission

This submission contains a tutorial notebook and a short report on **Gaussian Process Classification (GPC)** with a focus on **how kernel choice changes decision boundaries and uncertainty**.

## Files
- `gaussian_process_classification_tutorial.ipynb` — complete runnable notebook
- `gaussian_process_classification_tutorial_report.pdf` — short tutorial report (<2000 words)
- `requirements.txt` — Python packages used
- `LICENSE` — MIT license for re-use
- `figures/` — images used in the report

## How to run
1. Create a Python environment with the packages in `requirements.txt`
2. Open the notebook in Jupyter
3. Run all cells from top to bottom

The notebook uses only standard packages:
- numpy
- pandas
- matplotlib
- scikit-learn

No external dataset download is required. All datasets come from `scikit-learn`.

## Topic summary
The tutorial teaches:
- what Gaussian Process Classification is,
- why kernels matter,
- how RBF, Matérn and linear kernels behave differently,
- how the RBF length-scale changes smoothness and uncertainty,
- how to apply GPC to a real binary classification problem.

## Sources used
The notebook and report both cite:
- Rasmussen & Williams (2006), *Gaussian Processes for Machine Learning*
- Williams & Barber (1998), *Bayesian Classification with Gaussian Processes*
- scikit-learn documentation
- Distill article on visualising Gaussian processes
