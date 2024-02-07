# Salary Predictions of Data Professions

In this project, I've built a predictive model for the salaries of data professionals. Salaries in the field of data professions vary widely based on factors such as experience, job role, and performance. Accurately predicting salaries for data professionals is essential for both job seekers and employers. The goal is to predict the salaries of data professionals based on rich datasets.

I have performed several regression tasks and gained hands-on experience in Exploratory Data Analysis (EDA), feature engineering, data preprocessing, model evaluation, and model development.


## DATASET
This dataset is taken from : [Mentorness Internship Program](https://drive.google.com/file/d/1qu4vWboJBgceI07k78I8Zr-eZgrsfUf3/view?usp=sharing) <br/>

The dataset contains the following columns:

- `FIRST NAME`: First name
- `LAST NAME`: Last name
- `SEX`: Gender
- `DOJ`: Date of joining the company
- `CURRENT DATE`: Current date of data
- `DESIGNATION`: Job role/designation
- `AGE`: Age
- `SALARY`: Target variable, the salary of the data professional
- `UNIT`: Business unit or department
- `LEAVES USED`: Number of leaves used
- `LEAVES REMAINING`: Number of leaves remaining
- `RATINGS`: Ratings or performance ratings
- `PAST EXP`: Past work experience

## Acknowledgements
Thanks to the `Mentorness Internship Program` for providing an exciting opportunity to apply machine learning techniques to predict salaries in the data profession domain.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/CodeWithCharan/Salary-Predicition-Project.git
   ```

2. Create a virtual environment (optional): [Virtual Environment Set Up](https://github.com/CodeWithCharan/virtual-env-setup)

3. Install the required dependencies:

    ```
    pip3 install -r requirements.txt # Python3
    pip install -r requirements.txt # Python2
    ```

4. Run the flask app:
    ```
    python app.py
    ```

## Usage
After running the flask app, open your browser and go to the development server `http://127.0.0.1:####` to use the app. Now, Enter your Age, Leaves used, Ratings, Experience, Sex, Designation and UNIT to predict the Salary.