# Supervised Learning on Breast Cancer
## Supervised Learning Experiments on Wisconsin Breast Cancer Dataset

This repository contains various experiments with supervised machine learning models on the Wisconsin Breast Cancer dataset.

### Table of Contents
1. [Introduction](#introduction)
2. [Regression Study](#regression-study)
3. [Classification Study](#classification-study)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)
9. [Acknowledgements](#acknowledgements)
10. [Contact](#contact)

### Introduction

This project aims to explore and analyze the Wisconsin Breast Cancer dataset using different supervised learning techniques. The experiments are divided into two main studies: Regression and Classification.

### Regression Study

- **Objective**: Investigate how much the **mean radius** feature is affected by other tumor features.
- **Methods**: Two linear regression models were utilized.
- **Approach**:
  - Determine the feature that **most affects** the mean radius
  - Evaluate the performance of the two models with different training set sizes.
  - Analyze how the **change in training set size** impacts model performance.

### Classification Study

- **Objective**: Predict the **diagnosis** (benign or malignant) based on tumor characteristics.
- **Methods**: Five supervised learning algorithms were evaluated.
- **Approach**:
  - Define the features most associated with the diagnosis of **a malignant mass.**
  - Determine the **outstanding algorithm** for diagnosis prediction.
  - Identify features most associated with the diagnosis of a **malignant mass**.

### Installation

To run the code in this repository, ensure you have the following dependencies installed:

- Python 3.10.13
- Pandas 2.2.1
- Scikit-learn 1.5.0
- NumPy 1.26.4
- Matplotlib 3.8.3
- Seaborn 0.13.2
- Statsmodels 0.14.1

### Usage

To use the code in this repository, follow these steps:

Clone the repository

```bash
git clone https://github.com/yourusername/breast_cancer_supervised.git
```

Navigate to the project directory

```bash
cd breast_cancer_supervised
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

# Run the regression analysis
Run the regression analysis:

  Convert the notebook to a script and execute it:

```bash
jupyter nbconvert --to script regression_analysis.ipynb
python regression_analysis.py
```

Alternatively, run the notebook directly:

  Firstly you need to install papermill:

```bash
pip install papermill
```

```bash
papermill regression_analysis.ipynb output_regression.ipynb
```

Run the classification analysis:

Convert the notebook to a script and execute it:

```bash
jupyter nbconvert --to script classification_analysis.ipynb
python classification_analysis.py
```

Alternatively, run the notebook directly with papermill:

```bash
papermill classification_analysis.ipynb output_classification.ipynb
```

### Results
Regression Study

    Objective: Investigate the influence of other tumor features on the mean radius.
    Methods: Two linear regression models with different training set sizes.
    Key Findings:
        Model performance varies with training set size.
        The features that most/least or positively/negatively affect the mean radius feature were identified.
        Detailed results and performance metrics (e.g., R², MAE) can be found in the wisconsin_lnr_reg.ipynb file in the wisconsin_regression folder

Classification Study

    Objective: Predict the diagnosis (benign or malignant) based on tumor features.
    Methods: Evaluation of five Supervised Learning algorithms 
    Key Findings:
        The best performing algorithm was identified based on classification reports and graphs.
        Important features associated with malignant diagnoses highlighted.
        Detailed results and performance metrics can be found in the wisconsin_models.ipynb file in the wisconsin_classification folder

### Contributing

I am open to any criticism and contribution to this project! 
To contribute:

  Fork the repository.
  Create a new branch for your feature or bugfix:

```bash
git checkout -b feature-name
```

  Commit your changes:

```bash
git commit -m 'Add new feature'
```

  Push to the branch:

```bash
git push origin feature-name
```

### License

This project is licensed under the MIT License. See the [LICENSE file](./LICENSE) for more details.

### Acknowledgements
I would like to thank everyone who contributed to the language/packages and dataset I used in this project.

Wolberg,William, Mangasarian,Olvi, Street,Nick, and Street,W.. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.

### Contact

If you have any questions, suggestions or topics you would like to discuss, feel free to contact me:

- **Linkedin:** [LinkedIn](https://www.linkedin.com/in/huseyincavus/)
- **Email:** [huseyincavus@tuta.io](mailto:huseyincavus@tuta.io)
- **GitHub Issues:** [Project Issues](https://github.com/huseyincavusbi/breast_cancer_supervised/issues)
