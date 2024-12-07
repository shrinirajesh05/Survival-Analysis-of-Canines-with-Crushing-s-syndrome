Overview

This project focuses on analyzing survival characteristics and identifying prognostic factors in dogs diagnosed with hyperadrenocorticism (Cushing's syndrome) in primary care settings. By utilizing a dataset of 219 canine patients from 110 veterinary practices in England, this study provides valuable insights into the disease's natural history and its management in real-world clinical environments.

Data

Source: Primary care veterinary practices in England
Sample Size: 219 canine patients

Attributes:

Demographics: Age, sex, breed, weight, neutering status

Disease Information: Type (pituitary-dependent or adrenal-dependent), cortisol levels

Treatment Details: Trilostane treatment, dose adjustments, and treatment duration

Comorbidities: Diabetes mellitus, urinary tract infections, hypertension

Survival Outcomes: Date of death or last clinical visit, cause of death, censored status

Research Objectives

Median Survival Time: Estimate the median survival time for dogs diagnosed with hyperadrenocorticism in primary care settings.

Treatment Impact: Assess the effect of trilostane treatment on survival outcomes.

Prognostic Factors: Identify key factors influencing survival, including age, weight, breed, disease type, and comorbidities.

Comorbidity Analysis: Evaluate the impact of concurrent conditions such as diabetes and hypertension on survival outcomes.

Breed and Neutering Effects: Analyze the influence of purebred status and neutering on survival.

Methodology

The analysis employs a range of statistical techniques to explore survival trends and prognostic factors:

Kaplan-Meier Survival Analysis: To estimate survival probabilities and visualize survival curves.

Log-Rank Test: To compare survival distributions between groups (e.g., treated vs. untreated).

Cox Proportional Hazards Regression: To quantify the effects of prognostic factors on survival.

Random Survival Forests: To identify non-linear relationships and interactions among variables.

Preprocessing Steps

Data Cleaning:

Removed irrelevant columns (e.g., PatientID).

Addressed missing values using imputation or exclusion strategies.

Converted date fields to datetime format for time-based calculations.

Variable Transformation:

Encoded categorical variables for compatibility with statistical models.

Created new time-based features (e.g., intervals between diagnosis and treatment).

Exploratory Analysis:

Generated descriptive statistics for continuous variables (e.g., cortisol levels, weight).

Analyzed categorical data distributions (e.g., breed frequency, cause of death).

Visualized correlations among continuous variables.

Subset Creation:

Focused on uncensored cases (dogs with known outcomes) for detailed analysis.

Results and Insights

The median survival time varied based on treatment status and comorbidities.

Trilostane-treated dogs demonstrated improved survival compared to untreated counterparts.

Comorbidities such as diabetes significantly influenced survival outcomes.

Breed-specific trends were observed, with crossbreeds showing different survival patterns compared to purebreds.

Applications

Clinical Decision-Making: Provide evidence-based guidance for managing canine hyperadrenocorticism in primary care settings.

Treatment Optimization: Inform dosing strategies and adjustments for trilostane therapy.

Prognostic Tool Development: Help veterinarians predict outcomes based on patient-specific factors.

Future Work

Incorporate additional variables to refine prognostic models.

Extend the study to include larger datasets from diverse geographic regions.

Explore machine learning techniques for enhanced predictive accuracy.
