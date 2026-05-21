# Social Media Impact on Teen Mental Health
## An Exploratory Data Analysis

## Objective
To analyze how social media usage, sleep patterns, stress 
and anxiety levels relate to depression risk in teenagers 
aged 13-19.

## Dataset
- Source: Kaggle
- 1200 records, 13 features
- Target variable: depression_label (0 = No Depression, 1 = Depression)

## Data Cleaning
- No missing values found
- Dataset had severe class imbalance:
  - No Depression (0): 1169 patients (97%)
  - Depression (1): 31 patients (3%)

## Key EDA Findings
- Sleep hours is the strongest factor associated with depression (correlation = -0.19)
  - Less sleep = higher depression risk
- Social media hours positively correlates with depression (0.18)
- Stress level correlates with depression (0.17)
- Anxiety level correlates with depression (0.17)
- Platform type (Instagram/TikTok) showed no significant difference in stress levels
- Gender showed no significant difference in anxiety levels

## Key Visual Finding
Teens with depression clustered in a specific region:
- Sleep hours: below 6 hours
- Social media hours: 5 to 8 hours daily

## Conclusion
Four key factors associated with depression risk in teenagers:
1. SLEEP DEPRIVATION — Teens sleeping less than 6 hours show higher depression risk
2. HIGH SOCIAL MEDIA USAGE — Teens using social media 5-8 hours daily show higher risk
3. HIGH STRESS LEVELS — Strongly correlates with depression
4. HIGH ANXIETY LEVELS — Strongly correlates with depression

## Limitations
- Severe class imbalance (97% vs 3%) limits predictive modeling
- Dataset may not represent all teen demographics
- Self reported data may have bias

## Future Improvements
- Apply SMOTE to handle class imbalance
- Build ML classification model to predict depression risk
- Deploy using Streamlit for real time risk assessment

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
