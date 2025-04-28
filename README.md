Titanic-EDA
Exploratory Data Analysis (EDA) of the Titanic Disaster Dataset

📚 Overview:
This project performs an in-depth Exploratory Data Analysis (EDA) on the famous Titanic dataset.
The goal is to extract meaningful insights, detect important patterns, and understand feature relationships that influenced the survival probability of passengers.

The analysis includes:

Statistical summaries

Handling missing values smartly

Visualizations to uncover hidden patterns

Observations for each major step

Insightful conclusions

📋 Requirements:
Python 3.x

Jupyter Notebook (or any preferred IDE supporting notebooks)

Numpy

Pandas

Matplotlib

Seaborn

Install required libraries using:
pip install numpy pandas matplotlib seaborn

 Major Insights Extracted:
Gender Priority:
Females were given a significantly higher priority during the rescue operations compared to males.

Class Influence:
First-class passengers had a greater survival probability compared to second and third-class passengers. Higher socio-economic status positively impacted survival chances.

Minimal Influence of Certain Features:
Features like Age, Number of Siblings/Spouses aboard (SibSp), and Number of Parents/Children aboard (Parch) did not show a strong influence on survival probability individually.

Advanced Missing Value Imputation:
Instead of filling missing values in the Age column randomly or with mean/median, a smarter approach was used.
Information was extracted from the Name field (titles like Mr., Mrs., Miss, Master, etc.) to better estimate missing Ages based on social norms and titles.

📊 What the Analysis Covers:
Dataset overview using .info(), .describe(), .head(), and .value_counts().

Univariate Analysis: Distribution plots for single features (Age, Fare, Embarked, etc.).

Bivariate Analysis: Survival rates based on gender, class, and age groups.

Heatmaps and Correlation Analysis using sns.heatmap() and sns.pairplot().

Handling missing data with logical techniques.

Detailed visualizations (histograms, boxplots, scatterplots) with observations.

Final summary of findings with important business and practical interpretations.

🚀 How to Run:
Clone this repository:
git clone https://github.com/<your-username>/Titanic-EDA.git

Open Titanic_EDA.ipynb in Jupyter Notebook.

Run all the cells sequentially to reproduce the complete analysis.

💬 Feedback and Contributions:
Feel free to raise an issue or submit a pull request if you have any suggestions, questions, or improvements!
I'm open to discussions regarding any aspect of the EDA process or further analysis ideas.

⭐️ If you found this project useful, don't forget to star the repo and share your feedback!



