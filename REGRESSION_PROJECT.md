# Final Project: Regression Analysis

> Submission: GitHub Repository with Jupyter Notebook and Peer Review

---

## Overview
Businesses and organizations often need to understand the relationships between different factors to make better decisions.
For example, a company may want to predict the fuel efficiency of a car based on its weight and engine size or estimate home prices based on square footage and location.
Regression analysis helps identify and quantify these relationships between numerical features, providing insights that can be used for forecasting and decision-making.

This project demonstrates your ability to apply regression modeling techniques to a real-world dataset. You will:
- Load and explore a dataset.
- Choose and justify features for predicting a target variable.
- Train a regression model and evaluate performance.
- Compare multiple regression approaches.
- Document your work in a structured Jupyter Notebook.
- Conduct a peer review of a classmate's project.

---

## Dataset Options
Select one dataset from the list below. If you get good results, you can try the process on a suitable dataset of your own. 
Suitable datasets contain **numerical features** and a **numerical target variable** for regression.

1. Auto MPG Dataset (Predict fuel efficiency based on engine specs and weight)
   - [UCI Auto MPG Dataset](https://archive-beta.ics.uci.edu/ml/datasets/auto+mpg)
2. Housing Prices Dataset (Predict home values based on features like square footage and location)   
   - [Kaggle Housing Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
3. Medical Costs Dataset (Predict insurance charges based on age, BMI, smoking status)  
   - [Medical Cost Dataset](https://www.kaggle.com/mirichoi0218/insurance)

---

## Assignment Requirements
Your Jupyter Notebook must follow a structured format with clearly numbered second-level headings and reflection remarks after each section.

Start your notebook professionally with:
- a single top-level title
- your name (or alias)
- the date
- a brief introduction that describes the problem and the dataset.
- Import the external Python libraries used (e.g., pandas, numpy, matplotlib, seaborn, sklearn).

### Section 1. Load and Explore the Data
- 1.1 Load the dataset and display the first 10 rows.
- 1.2 Check for missing values and display summary statistics.

Reflection 1: What do you notice about the dataset? Are there any data issues?

---

### Section 2. Visualize Feature Distributions
- 2.1 Create histograms, boxplots, and scatterplots.
- 2.2 Identify patterns or anomalies in feature distributions.

Reflection 2: What patterns or anomalies do you see? Do any features stand out?

---

### Section 3. Feature Selection and Justification
- 3.1 Choose two input features for predicting the target.
- 3.2 Justify your selection with reasoning.

Reflection 3: Why did you choose these features? How might they impact predictions?

---

### Section 4. Train a Linear Regression Model
- 4.1 Define X (features) and y (target).
- 4.2 Train a Linear Regression model using Scikit-Learn.
- 4.3 Report R², MAE, RMSE.

Reflection 4: How well did the model perform? Any surprises in the results?

---

### Section 5. Improve the Model: Implement Regression Pipelines
- 5.1 Implement Pipeline 1: Imputer → StandardScaler → Linear Regression.
- 5.2 Implement Pipeline 2: Imputer → Polynomial Features (degree=3) → StandardScaler → Linear Regression.
- 5.3 Compare performance of all three models.

Reflection 5: Did polynomial features improve predictions? How does scaling impact results?

---

### Section 6. Final Thoughts & Insights
- 6.1 Summarize findings.
- 6.2 Discuss challenges faced.
- 6.3 If you had more time, what would you try next?

Reflection 6: What did you learn from this project?

---

## Tasks to Complete the Assignment

1. Create a GitHub repository named ml_regression_yourname.  
1. Upload your dataset to a data/ folder in the repository.  
1. Develop a Jupyter Notebook (final_yourname.ipynb) structured as outlined above.  
1. Complete and write reflections for each section as you work.
1. Write a README.md summarizing your project, dataset, and findings.  
1. Review a classmate’s project and provide feedback in peer_review.md.

---

## Peer Review (Required)

Review one other GitHub repository and provide feedback on:

1. Clarity & Organization (Is the notebook structured and easy to follow?)
1. Feature Selection & Justification (Do the chosen features make sense?)
1. Model Performance & Comparisons (Is the evaluation well explained?)
1. Reflection Quality (Are insights well thought out?)

Submission: Submit a short peer review document in your own repository titled peer_review.md.  
The peer review must contain a **clickable Markdown link to the notebook (.ipynb) file reviewed** along with your personal, well-organized and presented 4-pont review. 

## README.md (Required)

Include a professional README.md that introduces your project. Include:
- a clickable link to your notebook file.
- a clickable link to your your peer review Markdown file.
- Instructions on how to set up your virtual environment and run your notebook locally. 

---

## 4-point Repository Checklist

Verify your repository contains:

[ ] Jupyter Notebook (final_project.ipynb) with numbered sections and reflections.  
[ ] README.md (see above)
[ ] Dataset stored in a data/ folder.  
[ ] Peer Review (peer_review.md).  

---

