# LendingClub Loan Default Prediction 🏦 

## Introduction

LendingClub is a US-based peer-to-peer lending company. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), making it the world's largest peer-to-peer lending platform.

This project aims to leverage data from LendingClub to identify patterns indicating the likelihood of a loan applicant defaulting. Such insights can help in decision-making, such as denying the loan, reducing the loan amount, or lending at a higher interest rate to risky applicants.

## Business Understanding

Two major risks are associated with LendingClub's loan approval process:

1. Not approving a loan for an applicant who is likely to repay it, resulting in lost business.
2. Approving a loan for an applicant who is unlikely to repay it, leading to potential financial losses.

The project uses past loan application data and their outcomes (whether the applicant defaulted or not) to predict the likelihood of future loan defaults. 

## Business Objectives

LendingClub facilitates various types of loans, but lending to risky applicants is the biggest source of financial loss. The aim of this project is to identify these risky loan applicants using Exploratory Data Analysis (EDA) and Machine Learning. This will help reduce credit loss and enable the company to manage its portfolio and risk assessment more effectively.

## Data Description

The dataset for this project comprises various features, including loan amount, term, interest rate, employment title, home ownership status, annual income, and loan status, among others. For a full description of the dataset features, please refer to the 'data_dictionary.csv' file in the 'data' directory.

## Prerequisites

This project is implemented in Python and requires the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Please make sure to have them installed or run `pip install -r requirements.txt` in your environment.

## Directory Structure

The repository contains the following directories and files:

- `data/`: Directory to hold the dataset. The actual dataset is not included due to its large size.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model building.
- `src/`: Python scripts for data cleaning and model training.
- `requirements.txt`: Required Python libraries for this project.
- `README.md`: Project description and guide.

## Getting Started

Clone the repository and navigate into the directory in your local environment, then install the necessary dependencies:

- git clone <repo_link>
- cd <directory_name>
- pip install -r requirements.txt

After setting up, you can start by running the Jupyter notebooks in the `notebooks/` directory to understand the data analysis and model building process.
