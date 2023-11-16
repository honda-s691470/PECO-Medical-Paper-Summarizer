# PECO-Summarizer
Friendly clinical medical study summarizer in PECO (Patients, Exposure, Comparison, Outcome) plus alpha format. <br>
[PECO-Summarizer](https://chat.openai.com/g/g-3Ylvxx5GH-peco-summarizer)

# Supported Study Designs
meta-analysis, randomized controlled trials, cross-sectional studies, cohort studies, and case-control studies. 
Please be careful about the output results when other study designs than these are input.

# Update History
Nov 16, 2023: If an unsupported study design is entered, a warning is displayed.

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
- meta-analysis
  -Input Example: https://doi.org/10.1002/hep.23623
  
Additional Information for Meta-Analysis:<br>
1. Comprehensive Study Collection:<br>
  - Databases Searched: MEDLINE, Ovid MEDLINE In-Process, Cochrane CENTRAL Register of Controlled Trials, Cochrane Database of Systematic Reviews, 
  - Excerpta Medica Database, PubMed, clinicaltrials.gov, and various association meeting abstracts.<br>
  - Search Terms: Included NASH, NAFLD, nonalcoholic steatohepatitis, fatty liver, liver enzymes, and related terms.<br>
  - Period Covered: Up to January 2010.<br>
  - Study Types Examined: Randomized controlled trials.<br>
  - Researcher Contact: Ten authors were contacted to verify results and methodological quality.<br>
2. Study Collection Comprehensiveness:<br>
  - Number of Studies: 49 RCTs.<br>
  - Publication Bias Assessment: Funnel plots were used to assess publication bias.<br>
3. Risk of Bias Assessment:<br>
  - Multiple Evaluators: Yes, data extracted by two authors independently, with kappa coefficient for agreement.<br>
  - Assessment Criteria: Cochrane Risk of Bias Tool.<br>
4. Assessment of Results:<br>
  - Types and Number of Studies: 49 RCTs, including 23 with post-treatment histology (22 in NASH, 1 in NAFLD).<br>
  - Significant Differences and Integrated Results: Specific results not detailed in the quoted sections.<br>
  - Heterogeneity Assessment: I2 statistic and random-effects or fixed-effects models were used.<br>
  - Sub-Analysis/Sensitivity Analysis: Planned a priori for various criteria including NASH vs. NAFLD population, diabetic vs. nondiabetic population, treatment duration, and different drugs or doses.<br>

- RCT
  - Input Example: https://doi.org/10.1002/art.40493

Other Information<br>
 - Baseline Characteristics Equivalence: Baseline characteristics, including RA duration, tender joint count, and DAS28-ESR, were comparable between both groups.
 - Intention to Treat Analysis: The study followed an intent-to-treat approach.
 - Drop-out Rates and Sample Sizes: Among 718 patients enrolled, 296 were randomized (147 to TCZ monotherapy and 147 to TCZ plus MTX). Drop-out rates were 12.2% for TCZ monotherapy and 10.2% for TCZ plus MTX.
