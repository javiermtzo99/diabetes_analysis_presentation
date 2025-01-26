# Diabetes Analysis Presentation

This repository contains the Quarto presentation for **Team 15** on **diabetes analysis**. The presentation explores the prediction of diabetes in Pima Indian women using **logistic regression** and includes key visualizations and findings.

## Setup Instructions

### 1. Clone the Repository
```sh
git clone https://github.com/YOUR_USERNAME/diabetes_analysis_presentation.git
cd diabetes_analysis_presentation
```

2. Create the Conda Environment

Make sure you have Conda installed. Then, create and activate the environment:
```sh
conda env create --file environment.yml
conda activate diabetes_presentation
```
3. Add or Modify Images

If you want to add additional figures or update existing ones, place them inside the figures/ directory.

4. Render the Presentation

After making changes to presentation.qmd, render the updated presentation:
```sh
quarto render
```
This will generate a new presentation.html file.

Notes
	•	The dataset used is the Pima Indian Diabetes Dataset, which is publicly available on Kaggle.
	•	The study examines feature importance in predicting diabetes using logistic regression.
	•	If you run into Quarto issues, ensure Quarto is installed and correctly set up by running:
```sh
quarto check
```