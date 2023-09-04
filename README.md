# Employee Attrition Prediction
This project aims to analyze and predict employee attrition, focusing on understanding the factors that influence whether an employee will leave their current employer. Employee attrition can be costly for organizations, and predicting and preventing it can be crucial for maintaining a stable and productive workforce.

## Data Description
The dataset contains various features related to employee demographics, job satisfaction, and work-related factors. Here is a brief description of some key attributes:

**Education**
1. 'Below College'
2. 'College'
3. 'Bachelor'
4. 'Master'
5. 'Doctor'
   
**EnvironmentSatisfaction**
1. 'Low'
2. 'Medium'
3. 'High'
4. 'Very High'
   
**JobInvolvement**
1. 'Low'
2. 'Medium'
3. 'High'
4. 'Very High'
   
**JobSatisfaction**
1. 'Low'
2. 'Medium'
3. 'High'
4. 'Very High'
   
**PerformanceRating**
1. 'Low'
2. 'Good'
3. 'Excellent'
4. 'Outstanding'
   
**RelationshipSatisfaction**
1. 'Low'
2. 'Medium'
3. 'High'
4. 'Very High'
   
**WorkLifeBalance**
1. 'Bad'
2. 'Good'
3. 'Better'
4. 'Best'


* **Employee Count:** The number of people represented by the entry.
* **Monthly Rate:** Monthly income, the amount the employer pays to the employee.
* **Daily Rate:** Similar to Monthly Rate.
* **Attrition:** Information about whether an employee quit their job or not.
* **Stock Options Level:** What percentage of shares the employee owns or can hold.
* **Percent Salary Hike:** Percentage increase in salary over the last 2 years

## Problem Statement

The primary goal of this project is to build a predictive model that can determine the likelihood of employee attrition based on the provided features. By identifying key factors contributing to attrition, organizations can take proactive steps to improve employee retention and job satisfaction.

## Approach

We will explore the dataset, preprocess the data, and then apply various machine learning models to predict attrition. The models will be evaluated based on metrics like accuracy, precision, recall, and F1-score to assess their performance.

## Project Structure

* **data.csv:** The dataset containing employee information.
* **Employee_Attrition_Prediction.ipynb:** Jupyter Notebook with code and analysis.
* **README.md:** This README file providing an overview of the project.

## Dependencies

This project relies on Python and various libraries for data analysis and machine learning. You can install these libraries using pip if you haven't already. Additionally, you will need Plotly, Seaborn, and Lazypredict libraries for this project. To install the required dependencies, open your terminal or command prompt and run the following commands:
```bash
pip install pandas numpy scikit-learn matplotlib
pip install plotly seaborn lazypredict
```
Make sure you have Python and pip installed on your system before proceeding with the library installations.

## Usage
1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/Employee-_classification_project.git
```
2. Open the Jupyter Notebook:

```bash
cd Employee-_classification_project
jupyter notebook Employee-_classification_project.ipynb
```
3. Follow the notebook for detailed analysis and model building.

## Author

Natalia Pawłowska

Feel free to reach out with any questions or feedback.



