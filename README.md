# PECO-Medical-Paper-Summarizer
Friendly clinical medical study summarizer in PECO (Patients, Exposure, Comparison, Outcome) plus alpha format. <br>
[PECO-Medical-Paper-Summarizer](https://chat.openai.com/g/g-3Ylvxx5GH-peco-summarizer)

# Update History
Nov 29, 2023: Adjusted output of Primary and Secondary outcome.<br>
Nov 26, 2023: Adjusted output items.<br>
Nov 16, 2023: If an unsupported study design is entered, a warning is displayed.

# Supported Study Designs
meta-analysis, randomized controlled trials, cross-sectional studies, cohort studies, and case-control studies. 
Please be careful about the output results when other study designs than these are input.

# Output Format
Study design: <br>
PECO Summary:<br>
Population: <br>
Exposure/Intervention: <br>
Comparison: <br>
Outcome: <br>
Additional Information based on study design:<br>
Primary Outcomes:<br>
Secondary Outcomes:<br>
Comments:<br>
  Strong Points: <br>
  Weak Points:<br>
  
# Example of Additional Information section output 
**meta-analysis**<br>
  Input Example: https://doi.org/10.1002/hep.23623

1. Comprehensive Study Collection:<br>
  Databases Searched: MEDLINE, Ovid MEDLINE In-Process, Cochrane CENTRAL Register of Controlled Trials, Cochrane Database of Systematic Reviews, 
  Excerpta Medica Database, PubMed, clinicaltrials.gov, and various association meeting abstracts.<br>
  Search Terms: Included NASH, NAFLD, nonalcoholic steatohepatitis, fatty liver, liver enzymes, and related terms.<br>
  Period Covered: Up to January 2010.<br>
  Study Types Examined: Randomized controlled trials.<br>
  Researcher Contact: Ten authors were contacted to verify results and methodological quality.<br>
2. Study Collection Comprehensiveness:<br>
  Number of Studies: 49 RCTs.<br>
  Publication Bias Assessment: Funnel plots were used to assess publication bias.<br>
3. Risk of Bias Assessment:<br>
  Multiple Evaluators: Yes, data extracted by two authors independently, with kappa coefficient for agreement.<br>
  Assessment Criteria: Cochrane Risk of Bias Tool.<br>
4. Assessment of Results:<br>
  Types and Number of Studies: 49 RCTs, including 23 with post-treatment histology (22 in NASH, 1 in NAFLD).<br>
  Significant Differences and Integrated Results: Specific results not detailed in the quoted sections.<br>
  Heterogeneity Assessment: I2 statistic and random-effects or fixed-effects models were used.<br>
  Sub-Analysis/Sensitivity Analysis: Planned a priori for various criteria including NASH vs. NAFLD population, diabetic vs. nondiabetic population, treatment duration, and different drugs or doses.<br>

**RCT** <br>
  Input Example: https://doi.org/10.1002/art.40493

  Baseline Characteristics Equivalence: Baseline characteristics, including RA duration, tender joint count, and DAS28-ESR, were comparable between both groups.<br>
  Intention to Treat Analysis: The study followed an intent-to-treat approach.<br>
  Drop-out Rates and Sample Sizes: Among 718 patients enrolled, 296 were randomized (147 to TCZ monotherapy and 147 to TCZ plus MTX). Drop-out rates were 12.2% for TCZ monotherapy and 10.2% for TCZ plus MTX.

**Cross-Sectional Study** <br>
  Input Example: https://doi.org/10.1002/clc.23976
  
  Patients Inclusion/Exclusion criteria: Excluded participants under 18 years and those with missing data on HF status.<br>
  Sample sizes: Total of 28,764 participants after exclusions.<br>
  Measures taken to avoid bias: Utilization of a nationally representative sample, multivariate logistic regression models for adjustments.<br>
  Methods of adjustment for confounders: Adjusted for age, sex, race, hypertension, diabetes mellitus, smoking, alcohol consumption, coronary heart disease, kidney disease, liver disease, eGFR, systolic blood pressure, diastolic blood pressure, serum uric acid, albumin,   hemoglobin, hematocrit, and neutrophil-lymphocyte ratio.<br>
  How to deal with missing data: Participants with missing HF data were excluded.<br>
  Methods of sensitivity analysis: Performed for different subgroups, including sex, age, race, smoking status, hypertension, diabetes, coronary heart disease, liver disease, serum uric acid, and eGFR.<br>

**Cohort Study** <br>
  Input Example: [https://doi.org/10.1002/clc.23976](https://doi.org/10.1183/13993003.01257-2018)
  
  Patients Inclusion/Exclusion Criteria: Included individuals aged ≥50 who had filled at least three prescriptions for an inhaled anticholinergic medication or a short-acting β-agonist in a 1-year rolling window. Excluded if they had a total follow-up time <1 year.<br>
  Follow-up Period: Average follow-up time was 5.2 years.<br>
  Drop-out Rates: Not specifically mentioned.<br>
  Methods of Adjustment for Confounders: Multivariable Cox regression models adjusted for age, sex, region, income quintile, hospitalizations, physician encounters, COPD hospitalization, year of cohort entry, Charlson  Comorbidity Index score, total number of prescriptions received, oral glucocorticoid use, and statin exposure.<br>
  Dealing with Missing Data: Not explicitly mentioned, but administrative data sources typically have complete prescription and diagnosis records.<br>
