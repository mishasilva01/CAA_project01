# CAA_project01

### Dataset
The dataset is here: https://archive.ics.uci.edu/dataset/45/heart+disease . The data is already divided into Training&Validation and Test datasets.
The data gives the following features:
1) age (integer)
2) trestbps (integer) - resting blood pressure /mm Hg (on
admission to the hospital)
3) chol (integer) - serum cholesterol in mg/dl
4) thalach (integer) - Maximum heart rate achieved /bpm
5) oldpeak (integer) - ST depression induced by exercise
relative to rest
6) ca (integer) - Number of major vessels (0-3) colored by
fluoroscopy
7) sex (categorical)
  - 0: female
  - 1: male
8) cp (categorical) - chest pain
- 1: typical angina
- 2: atypical angina
- 3: non-anginal pain
- 4: asymptomatic
9) fbs (categorical) - fasting blood sugar > 120 mg/dl
- 0: False
- 1: True
10) restecg (categorical) - Resting electrocardiographic results
- 0: Normal
- 1: Having ST-T wave abnormality (T wave inversions
and/or ST elevation or depression of > 0.05
mV)
- 2: Showing probable or definite left ventricular
hypertrophy by Estes’ criteria
11) exang (categorical) - Exercise induced angina
- 0: No
- 1: Yes
12) slope (categorical) - The slope of the peak exercise ST
segment
- 1: Up sloping
- 2: Flat
- 3: Down sloping
13) thal (categorical)
- 3: Normal
- 6: Fixed defect
- 7: Reversible defect
14) num (label) - The final diagnosis of heart disease (angiographic
disease status)
- 0: Absence of CAD
- 1: First Level of Severity for CAD
- 2: Second Level of Severity for CAD
- 3: Third Level of Severity for CAD
- 4: Fourth Level of Severity for CAD

### Goal
Use deep learning to improve the previous work (paper is on git). Use CNN and DNN, vary the parameters (number of hidden layers, number of filters, number of neuros per layers, optimization function, activation function) and get the best model.
