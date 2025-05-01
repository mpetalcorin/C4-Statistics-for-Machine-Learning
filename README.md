# C4-Statistics-for-Machine-Learning
A hands-on, interactive collection of notebooks exploring key statistics for machine learning—featuring bootstrapping, MLE, correlation analysis, and real-world case studies with advanced visualizations and computational biology examples.
Statistics for Machine Learning 

This repository provides essential statistical concepts in machine learning. Each notebook is designed to be hands-on, with visualizations, interactive elements, and real-world case studies (including computational biology applications). Whether you are brushing up on the basics or advanced techniques, this repo has you covered.

⸻

## What’s Inside

1. Advanced Bootstrapping with Visuals
	•	Bootstrapped confidence intervals and bias/variance estimation.
	•	Violin plots, KDE curves, and distribution comparisons.
	•	Simple case study: Drug discovery—estimating drug potency with bootstrapping.
	•	Notebook: **C4_bootstrapping_visuals.ipynb**

2. Maximum Likelihood Estimation (MLE) – Intuitive & Interactive
	•	Explanation of MLE with examples.
	•	Mathematical derivations and log-likelihood plots.
	•	Drug discovery case: Estimating true IC50 potency.
	•	Interactive sliders (e.g., coin flips) and 3D likelihood surface plots using Plotly.
	•	Notebook: **C4_mle_interactive_3d_advanced.ipynb**

3. Correlation Coefficient – Computational Biology Focus
	•	Simulated gene expression data (Gene1 vs Gene2) + phenotype (Tumor Size).
	•	Pearson, Spearman, Kendall correlation coefficients + hypothesis tests.
	•	Permutation test to validate correlation significance.
	•	Plotly interactive 3D scatter plots for gene-phenotype exploration.
	•	Notebook: **C4_correlation_bio_advanced.ipynb**

⸻

## Key Concepts Covered
	•	Bootstrapping: Confidence intervals, bias-variance tradeoff, and resampling strategies.
	•	MLE: Likelihood maximization, log-likelihood, and parameter estimation for real-world data.
	•	Correlation: Measuring linear & monotonic relationships, statistical testing, and biological interpretation.
	•	Interactive Exploration: Sliders, hoverable 3D plots, and dynamic parameter changes using ipywidgets and Plotly.

⸻

## Real-World Applications
	•	Drug Discovery: Estimate drug potency, explore noisy biological data.
	•	Computational Biology: Discover gene co-expression and biomarker relationships.
	•	Medical Testing: Estimate disease prevalence from population data.

⸻

## Requirements
	•	Python 3.x
	•	Libraries:
	•	numpy, pandas, matplotlib, seaborn
	•	scipy
	•	plotly
	•	ipywidgets (for interactive sliders)

## Install dependencies using:
*!pip install numpy pandas matplotlib seaborn scipy plotly ipywidgets*

## Why This Matters

Statistics is the backbone of machine learning.
From understanding uncertainty (bootstrapping) to estimating model parameters (MLE) and uncovering hidden patterns (correlation), these tools are essential for any data scientist or ML engineer.

This repo brings theory + practice together with explanations, maths , and real-world relevance.

⸻

## Contributing

PRs and suggestions are welcome! Let’s make machine learning statistics more accessible for everyone. 
