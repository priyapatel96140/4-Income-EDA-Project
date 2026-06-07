# 4-Income-EDA-Project
# Adult Income - Exploratory Data Analysis (EDA)

This project is an exploratory data analysis (EDA) focused on analyzing demographic and employment factors that influence an individual's income level. Using a census dataset, the notebook walks through data cleaning, feature adjustment, and conditional queries to understand what traits are most common among high and low earners.


## Project Structure

The repository includes:
* **`4-Income-EDA-Project-questions.ipynb`**: The Jupyter Notebook containing the data analysis steps, column conversions, and Python code.
* **`4income.csv`**: The dataset containing demographic information like age, education, occupation, and income classification.


## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Libraries Used:** Pandas, NumPy
* **Environment:** Jupyter Notebook / JupyterLab


## Dataset Overview

The `4income.csv` dataset contains information across the following 15 attributes:
* **age:** The age of the individual.
* **workclass:** Employment sector (e.g., Private, Self-emp, Local-gov, State-gov).
* **fnlwgt:** Final weight representing census parameters.
* **education:** Highest level of education achieved.
* **educational-num:** Numeric representation of education level.
* **marital-status:** Marital status of the individual.
* **occupation:** The individual's profession or job role.
* **relationship:** Household relationship role (e.g., Husband, Own-child, Unmarried).
* **race:** Racial demographics.
* **gender:** Male or Female.
* **capital-gain:** Financial gains recorded.
* **capital-loss:** Financial losses recorded.
* **hours-per-week:** Number of hours worked weekly.
* **native-country:** Country of origin.
* **income:** Income classification bucket (<=50K or >50K).


## Key Tasks & Insights Covered

The notebook handles data profiling and addresses specific structural questions:
1. **Data Discovery:** Displaying random samples, inspecting top and bottom rows, checking column datatypes, and calculating dataset dimensions.
2. **Data Cleaning:** Finding total null values, replacing placeholder markers, and dropping incomplete rows.
3. **Univariate Analysis:** Finding the distribution profiles for specific attributes like age, workclass, and education.
4. **Bivariate Queries:** Comparing correlations between demographics, tracking hours worked per week across different groups, and calculating whether males or females show statistical differences in reaching the >50K income bracket.
5. **Data Type Casting:** Optimizing the dataset memory by converting object columns (like workclass) into category datatypes.


## How to Run This Project

Choose the option below that works best for you:

### Option 1: The Quick Way (No Git Required)
1. Click the green **Code** button at the top right of this GitHub page.
2. Click **Download ZIP** and unzip the files into a folder on your computer.
3. Move your dataset (`4income.csv`) into the same folder if it isn't already there.
4. Open your terminal or command prompt, navigate to that folder, and run:
   ```bash
   pip install pandas numpy notebook
   jupyter notebook


## Author

Priya Patel  
Aspiring Data Analyst  
Email: patelpriya18217@gmail.com  
GitHub: [priyapatel96140](https://github.com/priyapatel96140)  

If you like this project, feel free to give it a star!
