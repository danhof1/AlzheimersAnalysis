README: Exploring the Impact of Behavioral and Physical Features on Alzheimer's Disease
Overview
This project explores the influence of behavioral and physical features on the diagnosis of Alzheimer's Disease (AD). Leveraging statistical techniques such as bootstrapping, logistic regression, and Random Forest Classifiers, the study identifies key predictors and their relevance to AD. The findings aim to contribute to early detection and diagnosis, addressing a significant medical challenge given AD's increasing prevalence.

Authors
Daniel Doyon
Bartolomeo Zaino
Department of Mathematics, Hofstra University
Course: Math 137: Mathematical Probability and Statistics
Instructor: Dr. Angel Pineda
Date: December 17, 2024
Abstract
Alzheimer's Disease (AD) is a leading cause of death globally and primarily affects individuals over 65. Characterized by progressive neurodegeneration, symptoms include cognitive decline, memory loss, and speech difficulties. This study applies statistical methods to analyze features from a partially synthetic dataset to evaluate their diagnostic relevance. Techniques such as bootstrapping, measures of center, and logistic regression were employed, yielding insights into the role of various features in predicting AD.

Methods
Data
Dataset Source: Kaggle
Features: 35 distinct variables including demographic, lifestyle, and health-related data
Sample Size: ~26,000 records
Feature Engineering
Created new variables, such as the Comorbidity Index, derived from BMI, blood pressure, and cholesterol levels.
Statistical Techniques
Bootstrapping: Used to generate sampling distributions for variability analysis.
Logistic Regression: Identified features with significant linear relationships to AD diagnosis.
Random Forest Classifier: Captured non-linear relationships and calculated feature importance via GINI impurity.
T-Tests: Assessed the statistical significance of individual features.
Tools
R programming language for data manipulation and analysis.
Key Findings
Influential Features
Positive Correlations: Memory Complaints, Behavioral Problems
Negative Correlations: Mini-Mental State Examination (MMSE), Functional Assessment, Activities of Daily Living (ADL)
Notable Insights
Sleep Quality was initially hypothesized as a significant predictor but exhibited weaker-than-expected correlations.
Cholesterol levels (e.g., LDL, triglycerides) showed notable correlations, aligning with existing research on lifestyle factors and AD risk.
Statistical Significance
The majority of symptomatic features, such as confusion and disorientation, had near-zero p-values, confirming their importance.
Cholesterol levels and smoking, though categorized as indicative rather than symptomatic, also displayed notable correlations.
Discussion
This study highlights the complexity of AD diagnosis. While symptomatic features showed strong predictive power, lifestyle factors like smoking and cholesterol levels emerged as significant risk factors. The findings validate prior research and emphasize the importance of both linear and non-linear modeling approaches in understanding AD.

Conclusion
By combining advanced statistical techniques, this project identifies key predictors for Alzheimer's Disease and provides a foundation for further research. The results underscore the importance of both symptomatic and lifestyle factors in AD diagnosis, suggesting areas for future exploration.

References
Kaggle Alzheimer's Dataset
Kang, S. H., et al. (2023). "Distinct Effects of Cholesterol Profile Components on Amyloid and Vascular Burdens." BMC Geriatrics.
Rudajev, V., & Novotny, J. (2022). "Cholesterol as a Key Player in Amyloid β-Mediated Toxicity in Alzheimer's Disease." Frontiers in Molecular Neuroscience.
Mochizuki, H., et al. (2017). "The Impact of Amyloid-β Oligomers on Alzheimer’s Disease Pathogenesis." Alzheimer's & Dementia.
Figures and Tables
Figure 1: Sleep Quality Distribution
Figure 2: Feature Importance via Random Forest Classifier
Additional histograms and visualizations in Figures 1a-1i and 2a.
This repository documents the methodology, results, and conclusions from our study, providing a detailed roadmap for replicating or extending the analysis.
