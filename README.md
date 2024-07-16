Introduction
This repository contains two primary files used in combination to generate and analyze synthetic metabolic data.

Files
Version1.ipynb: Generates a synthetic dataset mimicking real-world metabolic data.
Calc_Syn_Data.ipynb: Iterates over the synthetic dataset and uses a metabolic calculator to analyze the data.
Introduction to Files
Version1.ipynb
Introduction
This project generates and analyzes a synthetic dataset of 10,000 adults, reflecting the age and BMI distribution of the US adult population. Using Python libraries like numpy, pandas, matplotlib, and random, the project simulates realistic health metrics to assess the prevalence and risk factors associated with metabolic syndrome.

Methods
Initial Imports: Imports essential Python libraries for data analysis and visualization.
Adult Population Dataset Generator: Creates a synthetic dataset reflecting the age and BMI distribution.
Health Metric Algorithms: Generates realistic values for waist circumference, fasting blood glucose, triglycerides, HDL cholesterol, and high blood pressure using probabilistic approaches.
Identifying Metabolic Syndrome: Applies clinical criteria to identify individuals with metabolic syndrome.
Data Visualization: Visualizes the relationship between BMI, age, and various health metrics.
Comparative Analysis: Compares synthetic data with NHANES reference data to refine the data generation process.
Calc_Syn_Data.ipynb
Introduction
This project utilizes a binary classification system to diagnose metabolic syndrome based on criteria from the NHLBI and AHA. It highlights the statistical nature of obesity and metabolic risk factors, particularly in younger individuals, and underscores the importance of BMI as a predictor of future metabolic health risks.

Methods
Risk Model: Incorporates BMI as an independent variable, acknowledging its predictive value for future metabolic health issues.
Data Iteration: Uses a synthetic dataset to reveal risk trends across BMI values and metabolic parameters.
Risk Assessment: Provides a comprehensive risk assessment, balancing immediate and future risks indicated by elevated BMI.
Conclusion
Version1.ipynb
The project successfully generated a synthetic dataset reflecting the US adult population's age and BMI distribution, simulating realistic health metrics. The identification of metabolic syndrome facilitated comprehensive analysis, showing a 34.58% prevalence, aligning with US estimates. While some metrics closely aligned with NHANES data, others showed deviations, highlighting areas for refinement.

Calc_Syn_Data.ipynb
This project emphasizes the significance of incorporating BMI in health risk models. Key findings include elevated risk across BMI categories, age-dependent risk trends, and the predictive value of BMI for future metabolic risks. The enhanced risk stratification system improves interpretability, emphasizing the need for early and continuous monitoring of metabolic health.

Real-World Implications
The findings support using comprehensive risk assessment models to identify at-risk individuals early, allowing for timely and effective interventions. Synthetic datasets are valuable for protecting privacy, testing algorithms, simulating scenarios, and educational purposes, enhancing the reliability of health-related analyses.

Usage
Run Version1.ipynb to generate the synthetic dataset.
Run Calc_Syn_Data.ipynb to analyze the synthetic dataset using the metabolic calculator.
License
This project is licensed under the MIT License - see the LICENSE file for details.
