# Traitement des Données Manquantes

Preprocessing of missing data within the **Wiki4HE dataset** to enhance data quality and enable effective analysis. This project includes handling missing values using various techniques to ensure accurate and reliable outcomes for further analysis.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

Handling missing data is a crucial step in data preprocessing. This repository focuses on:
- Identifying missing data in the Wiki4HE dataset.
- Applying various imputation techniques to handle missing values effectively.
- Improving data quality for downstream tasks like analysis and model training.

---

## Features

- Support for multiple imputation techniques, including:
  - Mean/Median/Mode Imputation
  - K-Nearest Neighbors (KNN) Imputation
  - Advanced techniques like Multiple Imputation by Chained Equations (MICE)
- Visualization of missing data patterns.
- Evaluation metrics for assessing the quality of imputations.

---

## Setup Instructions

### Prerequisites
Ensure that you have the following installed:
- Python (>= 3.7)
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/eyabesbes/Traitement-donnees-manquantes.git
   cd Traitement-donnees-manquantes
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Navigate to the notebook files provided in the repository and execute the cells step-by-step to:
   - Load the Wiki4HE dataset.
   - Visualize missing data patterns.
   - Apply various imputation techniques.
   - Evaluate the quality of the imputed data.
