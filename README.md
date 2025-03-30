# Student-grade-prediction

A machine learning project which utilizes linear regression to predict students' final grade (G3). The dataset used is `student-mat.csv` and model is trained using scikit-learn.

## Installation and Setup

-Clone the repository
` git clone https://github.com/coffeecookey/student-grade-prediction.git
  cd student-grade-prediction`

-install numpy, pandas, matplotlib, scikit-learn

-install the dataset `student-mat.csv`

## Features Used

The model considers the following attributes:

  - G1 (First Period Grade)
  - G2 (Second Period Grade)
  - age (Student's Age)
  - famrel (Quality of Family Relationships)
  - freetime (Free Time after School)
  - goout (Socializing Frequency)
  - traveltime (Home to School Travel Time)
  - studytime (Weekly Study Time)
  - failures (Number of Past Failures)
  - absences (Number of School Absences)
The final grade (G3) is the target variable.

## Model Training

The dataset is split into training (90%) and testing (10%) sets and linear Regression is applied to find the best fit. The model is trained multiple times (50,000 iterations) to achieve the best accuracy, which is saved as a pickle file (studentmodel.pickle). The best recorded accuracy is 97.02%.

## Visualisation 

The script generates scatter plots showing relationships between features and the final grade:

- G1 vs. G3 (Initial grades vs. final grade)
- Study Time vs. G3 (Study time vs. final grade)

## Author

Tanisha Ojha - https://github.com/coffeecookey
