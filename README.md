# Data Scientist Home Assignment - Sleek

## Dataset

The dataset can be retrieved from [UNB CIC IDS 2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html).

## Notebooks - make sure to run them in order

- **1. Initial Preprocessing**: Data loading, initial inspection, and basic preprocessing.
- **2. EDA and Feature Selection**: Exploratory data analysis and feature selection.
- **3. Modeling ML Approach**: Building and evaluating machine learning models.
- **4. Advanced Processing and EDA**: Further data processing and advanced EDA.

## Overview and Main Points

- The dataset is split over several days. However, predictability for each day does not necessarily align with other days due to different types of attacks. Specific days should be analyzed individually, or the distribution should be understood.
- During EDA, additional points were raised. It seems some features can predict benign attacks versus malicious ones. This should be further investigated and the features understood.
- The label was split into two categories: Benign and Malicious, due to several reasons:
  1. Lack of data on several attacks.
  2. Obtaining a baseline for further improvement.
  3. Understanding what is important, i.e., Benign vs. Malicious.

## Modeling

1. The most up-to-date models did a good job in separating attack vs. non-attack.
2. The temporal nature of the dataset is not yet fully resolved due to different label distributions.

## To-Do

- **Remove Duplicate Code**: Refactor duplicate code into reusable functions or classes.
- **Consider Temporal Variables**: Incorporate time-based features for a more comprehensive analysis.
- **Enhance Model Granularity**: Improve the granularity of the label prediction for more precise results.
