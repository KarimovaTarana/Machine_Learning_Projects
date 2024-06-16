# Music Genre Classification Project

## Overview

In recent years, streaming services with extensive catalogs have become the primary means through which most people enjoy music. However, the vast amount of available music can be overwhelming when users try to discover new tracks that match their tastes. To address this, streaming services categorize music to offer personalized recommendations. One effective method involves analyzing raw audio information and scoring it on various metrics.

This project focuses on classifying songs as either 'Hip-Hop' or 'Rock' using a dataset compiled by a research group called The Echo Nest. Our objective is to clean the data, perform exploratory data visualization, reduce features, and use machine learning algorithms such as decision trees and logistic regression to classify the songs—all without listening to them.

## Project Structure

- `data/`: Directory containing the dataset files.
  - `tracks.csv`: CSV file with metadata about the tracks.
  - `features.json`: JSON file with musical features of each track.
- `notebooks/`: Jupyter notebooks with step-by-step project processes.
- `src/`: Source code for data processing, visualization, and modeling.
- `README.md`: Project overview and instructions.


## Dataset

The dataset consists of two files:

- **Metadata** (`tracks.csv`): Contains details about each track such as title, artist, and number of listens.
- **Musical Features** (`features.json`): Includes musical features like `danceability` and `acousticness` on a scale from -1 to 1.

## Project Workflow

1. **Data Loading**: Load the metadata and musical features from the CSV and JSON files, respectively.
2. **Data Cleaning**: Handle missing values, normalize feature scales, and merge datasets.
3. **Exploratory Data Analysis (EDA)**: Visualize the data to understand distributions, correlations, and patterns.
4. **Feature Reduction**: Use techniques like PCA (Principal Component Analysis) to reduce the dimensionality of the dataset.
5. **Modeling**: Train machine learning models such as decision trees and logistic regression to classify the songs.
6. **Evaluation**: Assess the performance of the models using metrics like accuracy, precision, recall, and F1-score.



Enjoy exploring and classifying music with this project!
