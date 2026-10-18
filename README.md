# Cardiovascular Health Data Analysis

Python project completed in **October 2025** to explore factors associated with cardiovascular disease.

## Analysis

The notebook uses 70,000 examination records, with 68,594 retained after the selected BMI and blood pressure limits and gender-code checks. It includes data cleaning, BMI calculation, visualizations, Welch's ANOVA, Games–Howell comparisons, ANCOVA, chi-square tests, distance correlation, Glass's delta and exploratory generalized additive models.

Blood pressure shows larger standardized differences between disease groups than BMI. The lifestyle variables show weaker unadjusted associations in this sample. These are exploratory associations, and do not establish causal effects or validated predictions for new patients.

## Files and running

- `Clinical data science project - revised.ipynb`: analysis with saved results and figures.
- `medical_examination.csv`: input data. Keep it in the same folder as the notebook.
- `requirements.txt`: Python package versions used to check the notebook.

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Open the notebook in Jupyter or VS Code with notebook support, then run the cells from top to bottom.

## Dataset

Age is supplied in days. Cholesterol and glucose are ordered categories rather than measured concentrations. The original dataset source, sampling method and redistribution license are not documented in the supplied CSV and still need to be identified before publishing the data.

## Acknowledgments

Thanks to my teacher, **Yves-André Chapuis**, from **Université de Strasbourg**.

[University staff listing](https://physique-ingenierie.unistra.fr/faculte/enseignants/enseignants-chercheurs/).
