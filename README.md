# Supervised Learning on Breast Cancer
## Supervised Learning Experiments on Wisconsin Breast Cancer Dataset

This repository contains various experiments with supervised machine learning models on the Wisconsin Breast Cancer dataset.

### Table of Contents
1. [Introduction](#introduction)
2. [Regression Study](#regression-study)
3. [Classification Study](#classification-study)
4. [Results](#results)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgements](#acknowledgements)
8. [Contact](#contact)

### Introduction

This project aims to explore and analyze the Wisconsin Breast Cancer dataset using different supervised learning techniques. The experiments are divided into two main studies: Regression and Classification.

### Regression Study

- **Objective**: Investigate how much the **mean radius** feature is affected by other tumor features.
- **Methods**: Two linear regression models were utilized.
- **Approach**:
  - Determine the feature that **most affects** the mean radius
  - Analyze how the **change in training set size** impacts model performance.

### Classification Study

- **Objective**: Predict the **diagnosis** (benign or malignant) based on tumor characteristics.
- **Methods**: Five supervised learning algorithms were evaluated.
- **Approach**:
  - Define the features most associated with the diagnosis of **a malignant mass.**
  - Determine the **outstanding algorithm** for diagnosis prediction.


### Results
Regression Study

    Objective: Investigate the influence of other tumor features on the mean radius.
    Methods: Two Linear Regression models with different training set sizes were employed.
    Key Findings:
        Model performance varies with training set size.
        The features that most/least or positively/negatively affect the mean radius feature were identified.
        Detailed results and performance metrics (e.g., R², MAE) can be found in the [wisconsin_lnr_reg.ipynb](./wisconsin_lnr_reg.ipynb)  [LICENSE file](./LICENSE) file.
        
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
