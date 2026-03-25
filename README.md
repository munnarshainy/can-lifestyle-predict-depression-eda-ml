# Can Lifestyle Factors Predict Depression?

An exploratory data analysis and machine learning project investigating whether lifestyle factors can predict self-perceived depression severity in Indian students.

## Research Question
Can dietary habits, sleep duration, and genetic predisposition distinguish between students with no depression, depression without suicidal ideation, and depression  with suicidal ideation?

## Dataset
- **Source:** [Student Depression Dataset](https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset)
- **Size:** 27,901 responses
- **Note:** Depression is self-perceived, not clinically diagnosed

## Project Structure
```
├── data/
├── images/         
├── notebooks/
│   └── can-lifestyle-predict-depression.ipynb

```

## Key Findings
- Strong comorbidity between self-perceived depression and suicidal thought/s (Cramér's V = 0.546)
- Dietary habits was the strongest lifestyle predictor (RF importance = 0.74)
- Lifestyle factors alone are insufficient to predict depressive severity (RF accuracy = 41%)
- Suicidal ideation cannot be inferred from lifestyle signals alone

## Disclaimer
This is an academic exercise. Results should not be interpreted as a clinical tool.

## Setup

Create a new folder named 'data' > download the dataset from Kaggle and place it in `data/`.
