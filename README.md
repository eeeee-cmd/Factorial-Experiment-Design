# Factorial-Experiment-Design

## Overview
This repository provides readers with all the necessary data, R scripts, and files to understand how different combinations of study method (Active Recall vs. Passive Reading), environment (Quiet vs. Noisy), and study duration (Short vs. Long) affect learning outcomes. 

Using a full factorial 2³ experimental design with replication, the analysis evaluates both individual and interaction effects of these factors on test scores. Results from a three-way ANOVA show that all three main effects are significant, with study duration having the strongest impact. Some interactions are also significant, suggesting that the effectiveness of a study method can depend on the environment and duration. The findings offer practical guidance for optimizing study habits to improve academic performance.

## File Structure

The repo is structured as:

-   `data/raw_data` contains the raw data constructed in the .rmd file
-   `data/num_data` contains the converted numerical datasets that were constructed.
-   `Paper.rmd` contains the file used to generate the paper.


## 🧪 Experimental Design

- **Design Type**: Full factorial 2³ design
- **Factors**: 3 (each with 2 levels)
- **Replications**: 5 per condition (total of 40 observations)
- **Response Variable**: Test Score

| Factor     | Level 1         | Level 2       |
|------------|------------------|---------------|
| Method     | Passive Reading  | Active Recall |
| Environment| Noisy            | Quiet         |
| Time       | Short            | Long          |
