MOVIE PROFITABLILITY PREDICTION
Overview

This project builds a data-driven decision support system that predicts whether a movie is likely to be profitable before production begins. Using historical data from theatrical releases, the notebook demonstrates how machine learning can support film investment and greenlight decisions in a traditionally intuition-driven industry.

The model is designed to be interpretable, business-aligned, and practically usable, rather than a black-box prediction tool.


Why This Project Is Useful

Film production involves high financial risk, with large upfront budgets and uncertain returns. Studios often approve projects based on subjective judgment, which can lead to costly failures.

This project is useful because it:
	•	Quantifies profitability risk using historical evidence
	•	Helps identify high-confidence profitable projects
	•	Reduces the likelihood of investing in unprofitable films
	•	Demonstrates how analytics can improve capital allocation decisions
	•	Provides a transparent model that business stakeholders can understand

What You Can Do With This Project

Using this notebook, you can:
	•	Predict whether a movie is likely to be profitable based on its characteristics
	•	Analyze which factors (budget, rating, runtime, studio, release timing, etc.) most influence success
	•	Explore how probability thresholds affect investment risk
	•	Adapt the framework for:
	•	Film studios
	•	Streaming platforms
	•	Independent producers
	•	Entertainment analytics research
	•	Extend the analysis with new data (e.g., streaming revenue, marketing spend)


How the Project Works (High Level)
	1.	Data Cleaning
	  •	Removes films with missing budget or revenue data
	  •	Defines profitability as Gross Revenue > Production Budget
	2.	Feature Engineering
	  •	Production company strength
	  •	Star power indicators
	  •	Genre, rating, and release timing
	  •	Runtime and audience scores
	3.	Modeling
	  •	Logistic Regression classifier
	  •	Feature scaling to improve performance
	  •	Probability-based predictions (not just yes/no)
	4.	Evaluation
	  •	Accuracy, Precision, Sensitivity, and Specificity
	  •	ROC and Precision-Recall analysis
	  •	Threshold optimization for business use
