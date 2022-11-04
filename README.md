# DATA 512 PROJECT - COVID ANALYSIS

## Goal of the Project
Analyzing some of the social aspects of the pandemic by conducting a human centered data science analysis of available COVID-19 data for one specific County of the United States - **Norfolk in Massachusetts**.

Research Question to answer : *How did masking policies change the progression of confirmed COVID-19 cases from February 1, 2020 through October 1, 2021?*

## Source Data

Three main sources of the datasets:
1. The *RAW_us_confirmed_cases.csv* file from the Kaggle repository of John Hopkins University COVID-19 data.
2. The *CDC dataset* of masking mandates by county.
    - Limitations in CDC dataset: The CDC stopped collecting the policy information in September 2021.
3. The *New York Times mask compliance survey data*.

## Project Structure
```bash
data512_project
├── data
│   ├── Mask_Mandates.csv
│   ├── mask-use-by-county.csv
│   └── RAW_us_confirmed_cases.csv
├── results
│   └── visualization.png
├── source
│   └── Common Analysis.ipynb
├── LICENSE
├── Collective Analysis.pdf
└── README.md
 ```

### File Descriptions

**data**:
- *Mask_Mandates.csv* : The CDC dataset of masking mandates by county.
- *mask-use-by-county.csv* : A list of all the countries that do not have match in the population dataset.
- *RAW_us_confirmed_cases.csv* : The list of confirmed COVID cases by county.

**results**:
- *visualization.png*: Visualization of analysis of assigned county.

**source**:
- *Common Analysis.ipynb* - Code for exploring, analysis and visulaization of datasets.
 
*Collective Analysis.pdf* - Writeup on visualization and reflection statement.
