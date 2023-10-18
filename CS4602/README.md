# CS4602 Introduction to Machine Learning

| Assignment | Title |
| :-: | :-: |
| 1 | Systolic Blood Pressure Prediction |
| 2 | Hospital Death and Diabetes Mellitus Classification |
| 3 | TBA |
| 4 | TBA |

## Assignment 1
### Goal
| Part | Description | Features |
| :-: | :-: | :-: |
| Basic | Predict the SBP of one patient | DBP |
| Advanced | Predict the SBP for mutiple patients using multiple variables | subject_id, charttime, tempearture, heartrate, resprate and o2sat |

### Requirement
| Part | Method | Testing MAPE |
| :-: | :-: | :-: | :-: |
| Basic | Matrix Inversion | <= 10% |
| Basic | Gradient Descent | <= 10% |
| Advanced | Matrix Inversion / Gradient Descent | <= 15% |

### Result
| Part | Method | Validation MAPE | Testing MAPE |
| :-: | :-: | :-: | :-: |
| Basic | Matrix Inversion | 5.7285% | <= 10% |
| Basic | Gradient Descent | 5.2695% | <= 10% |
| Advanced | Matrix Inversion | 11.7953% | <= 15% |

## Assignment 2
### Goal
| Part | Description | Features |
| :-: | :-: | :-: |
| Basic | Predict the hospital_death | ventilated_apache, gcs_eyes_apache, gcs_motor_apache, gcs_verbal_apache, albumin_apache, bilirubin_apache, bun_apache, creatinine_apache and fio2_apache |
| Advanced | Predict the diabetes_mellitus | age, bmi and glucose_apache |

### Requirement
| Part | Method | Testing f1-score |
| :-: | :-: | :-: | :-: |
| Basic | Naive Bayesian Classifier | > 0.3 |
| Advanced | Gaussian Naive Bayesian Classifier | > 0.35 |

### Result
| Part | Method | Validation f1-score | Testing f1-score |
| :-: | :-: | :-: | :-: |
| Basic | Naive Bayesian Classifier | - | -
| Advanced | Gaussian Naive Bayesian Classifier | - | -