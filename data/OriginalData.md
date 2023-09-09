# Dataset

## Introduction

This repository contains a dataset that has been prepared for research or analysis purposes. The original dataset was quite large, exceeding 100 MiB, making it impractical to upload directly to GitHub. To make the data accessible, we have provided a download link for the original dataset.

**Original Dataset Size:** >100 MiB

**Link to Original Dataset:** [Dataset Download Link](https://drive.google.com/file/d/1mi7RC0HwBDfVUrlVp7njD-0Z22rfayNA/view?usp=drive_link)

After performing data cleaning and preprocessing steps, we managed to reduce the dataset's size to approximately 60 MiB. This cleaned and preprocessed dataset is included in the repository and can be easily accessed.

**Cleaned Dataset Size:** ~60 MiB

## Cleaned Dataset

### Description

The cleaned dataset is a refined and processed version of the original data. It is designed to be more user-friendly and suitable for analysis or research tasks. Below are details about the cleaned dataset:

- **File Name:** `CleanedData.csv`
- **Size:** ~60 MiB
- **Format:** Comma-separated values (CSV)
- **Structure:** The dataset is organized into rows and columns, where each row represents an individual data point or observation, and each column represents a specific attribute or feature.

### Columns

The cleaned dataset contains the following columns:

1. **subject:** Describes the subject or category of the data point.
2. **transformed text:** Contains the preprocessed and transformed text data.

### Data Cleaning and Preprocessing

To create the cleaned dataset, we performed the following data cleaning and preprocessing tasks:

1. **Handling Null Values:** Initially, the dataset contained 29 null values, which were removed to ensure data quality.

2. **Handling Duplicated Values:** There were 865 duplicated data points, which were also removed to avoid redundancy.

3. **Handling Incorrect Categories:** Nine data points had incorrect categories and were dropped.

4. **Empty Columns:** The dataset originally had more than 10 empty columns filled with NaN values, which contributed to the larger file size. These columns were removed.

5. **Category Merging:** Two categories, 'politicsNews' and 'politics,' which had the same meaning, were merged into a single category called 'politics.'

### Data Distribution

The final distribution of data points by category in the cleaned dataset is as follows:

- **politics:** 17636
- **worldnews:** 9989
- **News:** 9050
- **left-news:** 4303
- **Government News:** 1499
- **US_News:** 775

### Data Transformation

After data cleaning, the following transformations were applied to the 'text' column:

1. Lowercasing
2. Removal of stop words
3. Lemmatization
4. Removal of punctuation
5. Tokenization
6. Stemming

The transformed text data were then stored in a new column called 'transformed text.'

### Usage

The cleaned dataset is provided here for your convenience. You can use this dataset for various purposes, including but not limited to:

- Data analysis
- Machine learning
- Research projects
- Educational purposes

### Download

You can download the cleaned dataset directly from this repository by clicking on the following link:

[Download Cleaned Dataset (CleanedData.csv)](https://github.com/Firoz1402/Semantic-Text-Classification-Research/blob/main/data/CleanedData.csv)

# Important

Please note that the original dataset should be considered the source of truth, and any analyses or findings should ideally be based on the cleaned and preprocessed dataset included in this repository.


