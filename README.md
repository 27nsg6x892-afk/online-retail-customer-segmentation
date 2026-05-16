# Online Retail Customer Segmentation

## Overview

This project is a data mining and customer segmentation project using online retail customer behavior data. The goal is to analyze customers, group them into meaningful segments, and support decision-making using clustering, fuzzy inference, and optimization techniques.

The project applies RFM analysis, K-Medoids clustering, Hierarchical Clustering, a Fuzzy Inference System, and Genetic Algorithm optimization.

## Objectives

- Analyze online retail customer behavior
- Build RFM features using Recency, Frequency, and Monetary values
- Segment customers using clustering algorithms
- Compare K-Medoids and Hierarchical Clustering
- Apply a Fuzzy Inference System for customer classification
- Use Genetic Algorithm optimization to improve segmentation-related logic
- Visualize customer groups and interpret segmentation results

## Dataset

The project uses online retail transaction data.

The full dataset is not included in this repository because of file size limitations. A small sample dataset is included in the `sample_data/` folder only to show the expected data structure.

Expected data may include columns such as:

- Customer ID
- Invoice number
- Invoice date
- Quantity
- Unit price
- Country
- Product description

## Sample Data

A small sample file is included to make the repository easier to understand without uploading the full dataset.

Sample file:

- `sample_data/sample_online_retail.csv`

This sample is only for viewing the dataset structure. To fully run the project, download or use the complete dataset and place it in the correct local data folder.

## Methods Used

- Data cleaning
- Exploratory Data Analysis
- RFM analysis
- Feature scaling
- K-Medoids clustering
- Hierarchical Clustering
- Fuzzy Inference System
- Genetic Algorithm optimization
- Data visualization
- Cluster interpretation

## Project Workflow

1. Load the online retail dataset
2. Clean invalid or missing transaction records
3. Create RFM features:
   - Recency
   - Frequency
   - Monetary value
4. Scale the RFM features
5. Apply K-Medoids clustering
6. Apply Hierarchical Clustering
7. Compare and interpret customer segments
8. Build fuzzy rules for customer classification
9. Apply Genetic Algorithm optimization
10. Summarize final segmentation insights

## Tools & Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Scikit-learn-extra
- Jupyter Notebook

## Repository Structure

- online_retail_customer_segmentation.ipynb
- DM Report.pdf
- requirements.txt
- README.md
- sample_online_retail.csv

## How to Run

1. Clone the repository:

`git clone https://github.com/27nsg6x892-afk/online-retail-customer-segmentation.git`

2. Install the required libraries:

`pip install -r requirements.txt`

3. Open the notebook:

`jupyter notebook online_retail_customer_segmentation.ipynb`

4. Place the full dataset in the expected local data folder if needed.

5. Run the notebook cells in order.

## Notes

## Sample Data

A small sample file is included to make the repository easier to understand without uploading the full dataset.

Sample file:

- `sample_online_retail.csv`

## Project Status

Completed as an academic Data Mining project.

## Author

Mark Samy Sabry
