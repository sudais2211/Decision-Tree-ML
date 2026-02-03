# Decision Tree Machine Learning Project

## Overview
This project implements a Decision Tree algorithm for classification tasks using student performance data. The goal is to predict student grades based on various features.

## Project Structure
The project consists of the following files:

- **decision_tree.ipynb**: The main Jupyter Notebook containing the implementation of the Decision Tree algorithm, data preprocessing, model training, and evaluation.
- **README.md**: This documentation file that provides an overview of the project, its structure, and usage instructions.
- **student-mat.csv**: A dataset containing student performance data in mathematics.
- **student-merge.R**: An R script for merging datasets or performing additional data manipulation tasks.
- **student-por.csv**: A dataset containing student performance data in Portuguese.

## Data Description
The datasets `student-mat.csv` and `student-por.csv` contain the following features:
- **school**: Student's school (binary: "GP" - Gabriel Pereira or "MS" - Mousinho da Silveira)
- **sex**: Student's sex (binary: "F" - female or "M" - male)
- **age**: Student's age (numeric: from 15 to 22)
- **address**: Student's home address type (binary: "U" - urban or "R" - rural)
- **famsize**: Family size (binary: "LE3" - less than or equal to 3 or "GT3" - greater than 3)
- **Pstatus**: Parent's cohabitation status (binary: "T" - living together or "A" - apart)
- **Medu**: Mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education, 4 - higher education)
- **Fedu**: Father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education, 4 - higher education)
- **Mjob**: Mother's job (nominal: "teacher", "health", "services", "at_home", "other")
- **Fjob**: Father's job (nominal: "teacher", "health", "services", "at_home", "other")
- **reason**: Reason to choose this school (nominal: "home", "reputation", "course", "other")
- **guardian**: Student's guardian (nominal: "mother", "father", "other")
- **traveltime**: Travel time to school (numeric: 1 - less than 15 min, 2 - 15 to 30 min, 3 - 30 min to 1 hour, 4 - more than 1 hour)
- **studytime**: Weekly study time (numeric: 1 - less than 2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, 4 - more than 10 hours)
- **failures**: Number of past class failures (numeric: n if 1<=n<3, else 4)
- **schoolsup**: Extra educational support (binary: yes or no)
- **famsup**: Family educational support (binary: yes or no)
- **paid**: Extra paid classes within the course subject (binary: yes or no)
- **activities**: Extra-curricular activities (binary: yes or no)
- **nursery**: Attended nursery school (binary: yes or no)
- **higher**: Wants to take higher education (binary: yes or no)
- **internet**: Internet access at home (binary: yes or no)
- **romantic**: With a romantic relationship (binary: yes or no)
- **famrel**: Quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
- **freetime**: Free time after school (numeric: from 1 - very low to 5 - very high)
- **goout**: Going out with friends (numeric: from 1 - very low to 5 - very high)
- **Dalc**: Workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
- **Walc**: Weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
- **health**: Current health status (numeric: from 1 - very bad to 5 - very good)
- **absences**: Number of school absences (numeric: from 0 to 93)
- **G1**: First period grade (numeric: from 0 to 20)
- **G2**: Second period grade (numeric: from 0 to 20)
- **G3**: Final grade (numeric: from 0 to 20)

## Usage Instructions
1. Clone the repository or download the project files.
2. Open `decision_tree.ipynb` in Jupyter Notebook.
3. Run the cells sequentially to execute the Decision Tree algorithm and analyze the results.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Conclusion
This project demonstrates the application of the Decision Tree algorithm in predicting student performance based on various features. The results can be used to identify key factors affecting student grades and improve educational strategies.
