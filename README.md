# **Demographic Data Analyzer**

**Project Description**:  
This Python project analyzes demographic data extracted from the 1994 Census database using **Pandas**. The dataset contains information such as age, work class, education, marital status, occupation, and salary, and is used to answer various analytical questions, such as race distribution, average age of men, and percentage of individuals earning more than 50K based on education level.

This project is part of a curriculum challenge to develop a deeper understanding of data analysis using Python and Pandas.

---

### **Table of Contents**:
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Getting Started](#getting-started)
5. [Usage](#usage)
6. [License](#license)

---

### **Project Overview**:
- **Objective**: Analyze demographic data and answer various questions about the dataset using Python and Pandas.
- **Dataset Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult) (Dua, D. and Graff, C. 2019).
- **Key Tasks**: 
  - Analyze the number of people of each race.
  - Calculate the average age of men.
  - Determine the percentage of people with a Bachelor's degree.
  - Calculate the percentage of people with advanced education making more than 50K.
  - Find out the country with the highest percentage of people earning >50K.
  - Identify the most popular occupation for those who earn more than 50K in India.
  - And more...

---

### **Technologies Used**:
- Python 3 🐍
- Pandas 📊
- Git & GitHub 🦸‍♀️

---

### **Features**:
- **Race Analysis**: Computes how many people of each race are represented in the dataset.
- **Age Calculation**: Computes the average age of men.
- **Education Insights**: Determines the percentage of people with a Bachelor's degree and the percentage of people with advanced education earning more than 50K.
- **Work Hour Analysis**: Calculates the minimum number of hours worked per week and analyzes earnings based on work hours.
- **Country Analysis**: Identifies the country with the highest percentage of people earning more than 50K.
- **Occupation Popularity**: Identifies the most popular occupation for those earning more than 50K in India.

---

### **Getting Started**:

1. **Clone the repository**:

```bash
git clone https://github.com/your-username/demographic-data-analyzer.git
Install dependencies:

Ensure that you have Python 3 installed. You can install the necessary Python packages by running:

bash
Copy
Edit
pip install pandas
Run the project:

The main script for the project is demographic_data_analyzer.py. To run the analysis, execute the following command:

bash
Copy
Edit
python demographic_data_analyzer.py
Testing:

The unit tests for this project are in test_module.py. To ensure the code works as expected, you can run the tests using:

bash
Copy
Edit
pytest test_module.py
Usage:
The project reads the demographic dataset (typically in CSV format) and performs various analyses, including:

Race distribution: How many people of each race are in the dataset.

Average age of men: Calculate the average age of male individuals.

Percentage of Bachelor's degree holders: Calculate how many people hold a Bachelor's degree.

Advanced education earnings: Calculate the percentage of people with advanced education (Bachelors, Masters, Doctorate) who earn more than 50K.

Country with highest earnings: Identify the country with the highest percentage of people earning more than 50K.

License:
This project is licensed under the MIT License - see the LICENSE file for details.

pgsql
Copy
Edit
