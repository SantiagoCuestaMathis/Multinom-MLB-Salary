Predicting MLB Salary Levels Using Multinomial Logistic Regression
This project applies multinomial logistic regression to predict the salary tier of Major League Baseball (MLB) players based on their performance statistics. It was completed as part of the LUISS course Data Analysis for Business (DAB25).

📊 Overview
We aim to classify players into Low, Medium, or High salary levels using their career and season statistics. This project involves:

Data cleaning and preparation

Feature transformation and categorization

Model fitting using multinomial logistic regression

Cross-validation and model evaluation

🧠 Methods
Model: Multinomial logistic regression

Dataset: Hitters.csv – MLB player stats from 1986 and 1987

Preprocessing: Missing values (18%) were dropped, categorical variables converted

Target variable: Salary categorized into tertiles

🔧 Tools Used
R and RStudio

Libraries: nnet, caret, ggplot2, and others

R Markdown for reproducible reporting

📁 Files Included
FINALPJDATALOVERS.Rmd: Full analysis and code

Hitters.csv: DataSet containing information about MLB players

README.md: This project description

🧪 Evaluation
Cross-validation techniques (based on birthday seed) were used to estimate out-of-sample prediction error. Performance was assessed using classification accuracy and confusion matrices.

👥 Group
Group Name: DATALOVERS
Project completed as part of LUISS DAB25 course, Spring 2025.
