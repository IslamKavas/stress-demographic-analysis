# Stress & Psychological Pressure: Demographic Risk Factors

## Problem
Why do some people experience higher psychological stress than others?  
This project explores whether demographic factors — gender, age, and marital status — are associated with stress levels, using a large-scale survey dataset of 39,775 participants.

## Dataset
**Source:** [DASS Responses — Kaggle](https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses)  
**Origin:** OpenPsychometrics.org (2017–2019)  
**Size:** 39,775 participants  
**Tool used:** Google Sheets

The dataset contains responses to the Depression Anxiety Stress Scales (DASS-42), along with demographic information including age, gender, and marital status.

## Analysis

### 1. Stress Score Calculation
Stress scores were calculated by summing 14 DASS subscale items:  
Q1, Q6, Q8, Q11, Q12, Q14, Q18, Q22, Q27, Q29, Q32, Q33, Q35, Q39  
Score range: 14–56 (higher = more stress)

### 2. Age vs Stress (Correlation)
| Metric | Value |
|--------|-------|
| Pearson r | -0.07 |

Age shows almost no correlation with stress scores. Stress levels appear largely independent of age in this dataset.

### 3. Stress by Gender
| Gender | Avg Stress Score |
|--------|-----------------|
| Male | 32.63 |
| Female | 35.81 |
| Other | 39.26 |

### 4. Stress by Marital Status
| Marital Status | Avg Stress Score |
|----------------|-----------------|
| Never married | 35.61 |
| Currently married | 32.08 |
| Previously married | 33.14 |

## Key Insights

**1. Gender is the strongest predictor**  
Female participants scored 9.7% higher than males on average stress. The "Other" gender group showed the highest stress levels of all three groups.

**2. Marriage is associated with lower stress**  
Currently married individuals show the lowest average stress (32.08) — 3.5 points lower than never-married participants. This suggests stable relationships may act as a stress buffer.

**3. Age is not a significant factor**  
With r = -0.07, age has virtually no relationship with stress in this dataset. Stress is shaped more by social and relational factors than by age alone.

## Charts
![Average Stress Score by Gender](Average%20Stress%20Score%20by%20Gender.png)
![Average Stress Score by Marital Status](Average%20Stress%20Score%20by%20Marital%20Status.png)

## About
This project was completed as part of a data analyst portfolio.  
Analysis conducted in Google Sheets using AVERAGEIF, CORREL, INDEX/MATCH functions.
