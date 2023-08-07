# Salary-Insights
Salary Insights: Analyzing Demographic Factors

Salary Analysis Git
This repository contains Python code for analyzing salary data based on country, race, gender, education level, 
years of experience, and salary. The analysis utilizes various data visualization techniques and statistical tests to 
gain insights into the salary distribution and identify potential differences among different demographic groups.

Installation
To run the code in this repository, you need to have Python installed on your system. 
Additionally, ensure you have the required Python packages installed by running the following command:
pip install plotly pandas matplotlib seaborn scipy

Usage
1. Clone the repository
2. Install the required packages above
3. Run the python code

Data
The dataset used for analysis is stored in a CSV file named "Salary_Data_Based_country_and_race.csv" and contains information on salary, gender, education level, job title, country, race, age, and years of experience.

Analysis
The Python script "salary_analysis.py" performs the following analysis:

Descriptive statistics: Provides an overview of the dataset by displaying the summary statistics of numerical columns.
Histogram: Visualizes the age distribution using a histogram.
Boxplot: Displays the distribution of salaries using a box plot.
Barplot: Illustrates the gender distribution using a bar plot.
Scatter plot: Demonstrates the relationship between years of experience, salary, and gender using a 3D scatter plot created with Plotly.
Welch's t-test: Performs a statistical test to determine if there is a significant difference in salaries between male and female employees.
One-way ANOVA: Conducts an analysis of variance to evaluate salary differences based on years of experience, education level, country, and race.
