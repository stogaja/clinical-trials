# Clinical Trials Repository

<details>
  <summary>Analysis Questions for Marking(Click here)</summary>

a. **How best can you analyze the data?**

1. **Data Understanding and Exploration:**

   - Familiarize with the dataset's structure and contents.
   - Identify the variables (columns) and their data types.
   - Check for missing values and decide how to handle them.
   - Explore basic summary statistics to get a sense of the data's distribution.

2. **Data Cleaning and Preprocessing:**

   - Handle missing values: Impute or remove them based on the nature of the data.
   - Remove duplicates, irrelevant columns, or any outliers that may skew the analysis.
   - Standardize data formats (e.g., dates, numeric types, text processing for NLP tasks).
   - Encode categorical variables (if applicable) using techniques like one-hot encoding or label encoding.
   - Normalize or scale numerical features if needed.

3. **Exploratory Data Analysis (EDA):**

   - Visualize the data to identify patterns, trends, and relationships among variables.
   - Use descriptive statistics, histograms, box plots, scatter plots, and correlation matrices.
   - Conduct univariate and multivariate analyses to understand variable interactions.

4. **Feature Engineering:**

   - Create new features or transform existing ones to enhance predictive power.
   - Extract relevant information from text, dates, or other unstructured data.

5. **Hypothesis Testing (if applicable):**

   - Formulate hypotheses related to specific research questions or clinical hypotheses.
   - Use statistical tests to validate or refute these hypotheses.

6. **Model Building (if applicable):**

   - Select appropriate modeling techniques based on the nature of the data (e.g., regression, classification, time series, etc.).
   - Split the data into training and testing sets for model evaluation.
   - Train and validate models using appropriate evaluation metrics.

7. **Model Evaluation and Interpretation:**

   - Assess model performance using relevant metrics (accuracy, precision, recall, F1-score, etc.).
   - Interpret the model results to understand the impact of features on the target variable.
   - Check for overfitting or underfitting and make necessary adjustments.

8. **Clinical Interpretation and Domain Knowledge:**

   - Collaborate with domain experts or healthcare professionals to interpret the findings in a clinical context.
   - Understand the implications of the analysis on patient care or clinical decision-making.

9. **Documentation and Reporting:**

   - Document the entire analysis process, including data preprocessing steps, models used, and their performance.
   - Summarize key findings and insights in a clear, understandable format for stakeholders.

10. **Continuous Improvement and Iteration:**

- Review and refine the analysis as more data becomes available or as new research questions arise.
- Stay updated with the latest advancements in clinical research and data analysis techniques.

b. **Can you identify any trends in the clinical studies?**

1. Termination of studies was prevalent in african countries.

2. Completed studies had the highest frequency as compared to any other study types.

3. Studies with All sex were more prevalent.

4. Clusters with both adults and older adults were most common in the studies.

5. Phase 2 had the highest number of participants.

6. Funder type encapsulated in "Other" were more than those funded by Industry, Govt, NIH.

7. Most study results were not released.

8. Interventional study types were much more copared to Expanded Access and Observational.

```
9.              Drug                                    Disease  Count
0   DRUG: Pembrolizumab  Metastatic Breast Cancer|Brain Metastases    114
1       DRUG: Metformin                         Endometrial Cancer     79
2       DRUG: Nivolumab                  Colon Cancer Stage II/III     76
3  BEHAVIORAL: Exercise                                    Fatigue     72
4    DRUG: Lenalidomide                             Acute Leukemia     65
```

The mentioned drugs and the matching diseases were the most prevalent in interventional studies.

10. US and china had the highest number of trials

11. US had a high number of studies completed. Disclaimer: this is relative to the population as higher number of studies were done in the US.

12. The studies conducted in Kenya focused on the following diseases; HIV, Malaria, Pneumonia and contraception.

13. Top sponsors.University are sponsoring studies more than other organisations for studies done in Kenya.

c. **Write the conclusions and recommendations derived from the analysis**

Based on the analysis we made the following recommendations.

1. Emphasis should be put on conducting more clinical trials in African countries and ensuring higher participation. This will contribute to the availability of better-quality medicine for the African population.
2. Studies should be more focused on getting more male participants to prevent bias when into comes to drawing conclusions for drugs.
3. More trials should be done on different age groups equally in order to counter diseases that come at different ages i.e., studies should not be all focused-on adults and older adults.
4. More interventional study types should be done on the African continent because very few of them get terminated.
5. More participation globally should be encouraged to ensure more study results are available and released even after termination in phase2.
6. Studies on more conditions other than HIV and AIDS, Malaria, and pneumonia should be conducted in Kenya so that the trials are well representative of most conditions affecting the population.

</details>

![My Portfolio](https://github.com/stogaja/clinical-trials/blob/main/clinical-trials-process.png)

This repository contains a curated collection of information related to clinical trials conducted in various medical fields. Our goal is to provide valuable insights and resources for researchers, medical professionals, and anyone interested in the advancement of healthcare.

**The file with code work for marking is [clinical-trials.ipynb](https://github.com/stogaja/clinical-trials/clinical-trials.ipynb)**

## Table of Contents

- [About Clinical Trials](#about-clinical-trials)
- [Dataset Overview](#dataset-overview)
- [Getting Started](#getting-started)
- [Data Fields](#data-fields)
- [Contributors](#contributors)
- [License](#license)

## About Clinical Trials

Clinical trials are research studies conducted to evaluate the safety and effectiveness of medical treatments, interventions, or devices. They play a crucial role in advancing medical knowledge and improving patient care.

## Dataset Overview

Our dataset comprises information on a diverse range of clinical trials conducted globally. It includes details on trial phases, participant demographics, intervention methods, and outcomes. Researchers can use this dataset for various analyses and studies.

## Getting Started

To get started with the Clinical Trials Repository, follow these steps:

1. Clone the repository to your local machine:

```
git clone <https://github.com/stogaja/clinical-trials>
```

2. Install any required dependencies or libraries (if applicable).

3. Explore the dataset and leverage the information for your research or analysis.

## Data Fields

The dataset includes the following key fields:

- **NCT_Number**: Unique identifier for each clinical trial.
- **Phases**: The phase of the clinical trial (e.g., Phase I, Phase II, Phase III & Phase IV).
- **Study_status**: Details about the intervention or treatment being tested.
- **Age**: Different ages of the participants.
- **Study_results**: Its binary and contains whether or not the study results are available.
- **Start Date**: Date when the trial commenced.
- **End Date**: Date when the trial concluded (if available).
- [Dataset Link](https://drive.google.com/drive/folders/1_Mwd5TC1enoaBoXYpZYhSuJ_Y6lF-EnX)

## Contributors

<details>
  <summary>Colaborators in the project were:</summary>
  
- [Mutheu Nguta](https://github.com/mutheu-array)
- [Prudence Muchangi](https://github.com/PrudenceMu)
- [Stephen Ogaja](https://github.com/stogaja)

</details>

## License

This Clinical Trials Repository is licensed under the [MIT License](LICENSE).
