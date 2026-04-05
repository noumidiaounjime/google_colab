# Manipulating Different Datasets in Google Colab

This notebook provides a hands‑on guide to loading, cleaning, transforming, and visualizing various types of datasets using **Google Colab** and popular Python data‑science libraries.

## 📌 Overview

Working with real‑world data often involves multiple formats: CSV, Excel, JSON, images, and even SQL databases. This notebook shows how to:

- Load datasets from different sources (local upload, Google Drive, URLs, Kaggle)
- Perform common data manipulation tasks (filtering, grouping, merging)
- Handle missing values and data type conversions
- Visualize insights with `matplotlib` and `seaborn`
- Export processed data back to various formats

## 🚀 Features

- **Mount Google Drive** – access files stored in Drive
- **Upload from local machine** – use `files.upload()`
- **Read multiple formats** – `pandas.read_csv()`, `read_json()`, `read_excel()`, `read_sql()`
- **Data cleaning** – drop duplicates, fill missing values, rename columns
- **Feature engineering** – create new columns, apply functions, binning
- **Visualization** – histograms, scatter plots, heatmaps, pair plots
- **Image manipulation** – resize, convert to grayscale, basic augmentation
- **Export results** – save as CSV, JSON, or back to Google Drive
