# Sleep Quality and Disorder Prediction Using Lifestyle Factors

Tools Used: R, Linear Regression, Random Forest, Genetic Algorithm, Dask, Profiling

---

## Objective
To predict the quality of sleep and presence of sleep disorders using lifestyle and health-related factors such as stress level, physical activity, and sleep duration.

---

## Dataset
- Source: [Kaggle – Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)
- Size: 400 rows, 13 columns
- Includes variables like: age, gender, BMI, sleep duration, physical activity, stress level, heart rate, blood pressure, and sleep disorder status.

---

## Methods Used
- Linear Regression: Modeled sleep quality using stress level, physical activity, and sleep duration.
- Profiling: Compared performance of `read.csv` vs `fread` in R; optimized data load speed.
- Random Forest Classifier: Achieved 97.3% accuracy on sleep disorder prediction.
- Parallelization: Tested model performance with and without parallel execution.
- Genetic Algorithm + Dask: Simulated group-based analysis for stress/activity and sleep disorders.
- Visualization: Violin plots, Sankey diagrams, heatmaps, and execution time graphs.

---

## Key Insights
- Stress level and physical activity are strong predictors of sleep quality.
- Sleep disorders are more common in individuals with high stress and low physical activity.
- Parallel processing doesn't always improve performance — especially on small datasets.


## Acknowledgments

This project was completed as part of the Health Data Science curriculum at Saint Louis University.
