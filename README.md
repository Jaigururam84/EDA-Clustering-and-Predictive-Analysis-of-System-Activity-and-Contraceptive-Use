# Predictive-Modelling

## Overview
	This document outlines the analysis performed on two datasets: computer system activity measures and contraceptive prevalence survey data. The goal 	is to derive actionable insights through exploratory data analysis (EDA), clustering, and predictive modeling.
## Contents
	Problem 1: Computer System Activity Analysis
	Objective: 
		Establish a linear equation to predict 'usr' (percentage of time CPUs operate in user mode) based on various system attributes.
	Key Variables:
		lread, lwrite, scall, sread, swrite, fork, exec, rchar, wchar, pgout, ppgout, pgfree, pgscan, atch, pgin, ppgin, pflt, vflt, runqsz, 			freemem, freeswap.
	Key Steps:
		Exploratory Data Analysis (EDA):
			Checked data shape, types, and performed univariate and multivariate analyses.
			Visualized patterns and insights using appropriate plots.
		Data Preprocessing:
			Treated missing values in relevant columns.
			Detected and handled outliers.
			Performed z-score scaling for normalization.
		Model Building:
			Applied linear regression to model the relationship between variables.
			Evaluated model performance using R-squared and RMSE metrics.
	Problem 2: Contraceptive Prevalence Survey Analysis
	Objective: 
		Predict contraceptive method usage based on demographic and socio-economic attributes of married women.
	Key Variables:
		Wife's age, education levels (wife and husband), number of children ever born, religion, employment status, husband's occupation, standard-		of-living index, media exposure.
	Key Steps:
		Exploratory Data Analysis (EDA):
			Analyzed data shape and types; performed univariate and multivariate analyses.
			Visualized relationships between variables to extract meaningful insights.
		Data Preprocessing:
			Addressed missing values and outliers as necessary.
			Encoded categorical variables for modeling.
			Split data into training and test sets for model evaluation.
		Model Building:
			Developed logistic regression models and compared them with linear discriminant analysis (LDA) and CART models.
			Evaluated model performance using metrics such as accuracy and AUC-ROC curves.
## Conclusion
	The analyses conducted provide valuable insights into computer system performance and demographic trends in contraceptive use. These insights can 	inform strategic decisions aimed at improving system efficiency in computing environments and enhancing public health initiatives. This README file 	summarizes the objectives, methodologies, findings, and conclusions drawn from the analyses performed on the datasets provided. Adjustments can be 	made based on specific details or additional insights derived from your analysis.
