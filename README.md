# Medical Data Visualizer

This project, we will analyze and visualize data using pandas, seaborn, and matplotlib. The dataset values were collected during medical examinations.

## Data Description
The rows in the dataset represent patients and the columns represent information of patients. Here is the description of each column:


| Feature                                      | Variable Type        | Variable          | Value Type                                                   |
|----------------------------------------------|----------------------|-------------------|--------------------------------------------------------------|
| Age                                          | Objective Feature    | age               | int (days)                                                   |
| Height                                       | Objective Feature    | height            | int (cm)                                                     |
| Weight                                       | Objective Feature    | weight            | float (kg)                                                   |
| Gender                                       | Objective Feature    | gender            | categorical code                                             |
| Systolic blood pressure                      | Examination Feature  | ap_hi             | int                                                          |
| Diastolic blood pressure                     | Examination Feature  | ap_lo             | int                                                          |
| Cholesterol                                  | Examination Feature  | cholesterol       | 1: normal, 2: above normal, 3: well above normal            |
| Glucose                                      | Examination Feature  | gluc              | 1: normal, 2: above normal, 3: well above normal            |
| Smoking                                      | Subjective Feature   | smoke             | binary                                                       |
| Alcohol intake                               | Subjective Feature   | alco              | binary                                                       |
| Physical activity                            | Subjective Feature   | active            | binary                                                       |
| Presence or absence of cardiovascular disease| Target Variable      | cardio            | binary                                                       |

