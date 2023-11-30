# Smooth-and-Featured-Galaxy-Detection-Using-Classification-Tree-and-Machine-Learning

## Author
Bryan Jianjun Chen

## Date
2023-08-21

---

This project explores the intriguing world of galaxies using data from the Galaxy Zoo survey. The primary focus is on understanding the differences in size distributions between smooth and featured galaxies and identifying factors that influence a galaxy's classification as smooth or featured.

## Research Questions

1. **How do the size distributions of smooth and featured galaxies differ?**  
   This question is addressed through the construction of a linear regression model using indicator variables to compare size distributions.

2. **What factors determine whether a galaxy is classified as smooth or featured?**  
   A classification tree approach is employed to unravel the features influencing galaxy classification.

## Data Sources

The analysis leverages two primary datasets:
- `gz2_catalog_with_modern_schema_no_paths.parquet`: The Galaxy Zoo 2 catalog.
- `nsa_v1_0_1_key_cols.parquet`: Key columns from the NASA-Sloan Atlas.

## Methodology

### Data Preparation and Exploration
- The data is read and preprocessed using R libraries like `tidyverse`, `rpart`, and `arrow`.
- The study involves filtering, mutating, and merging datasets to create a comprehensive view of galaxy characteristics.

### Statistical Analysis
- Linear regression models are developed to understand the size distributions.
- Classification trees are constructed to identify key factors influencing galaxy classification.

### Visualization
- Histograms and scatter plots are used to visualize the data.
- Customized plots are created using `ggplot2` to enhance interpretability.

### Model Evaluation
- The classification tree model is evaluated using a confusion matrix.
- Key metrics like accuracy, sensitivity, and specificity are calculated to assess model performance.

## Installation

To run this project, you will need R and the following libraries:
- tidyverse
- rpart
- partykit
- dplyr
- arrow

## Usage

The code is organized into R markdown chunks, each addressing specific aspects of the analysis. Run the chunks sequentially to reproduce the findings.

## Conclusion

This project provides insights into the fascinating differences and determinants of galaxy types. The findings contribute to a better understanding of galactic characteristics in the universe.

---
