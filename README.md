# Netflix Content Analysis

An exploratory data analysis project focused on examining Netflix's content catalog through content type, geographic representation, release year trends, ratings, and genre composition.

## Project Overview

This project explores Netflix's content catalog using Python-based data analysis and visualization techniques. The objective is to understand the overall composition of the catalog, identify relevant patterns across multiple content dimensions, and translate analytical findings into potential business insights.

The project follows a structured analytical workflow, starting with data cleaning and exploratory data analysis, followed by integrated business insights and recommendations.

The final analysis will also be presented through an interactive Tableau dashboard.

## Project Objectives

- Examine the distribution of Movies and TV Shows.
- Analyze geographic representation across countries.
- Explore content distribution by release year.
- Investigate content rating classifications.
- Identify the most frequently represented genres.
- Develop business insights and recommendations based on analytical findings.
- Present key findings through an interactive dashboard.

## Dataset Description

The dataset contains Netflix content metadata, including information about titles, content types, directors, countries, release years, ratings, durations, and genre classifications.

**Dataset Overview:**
- Initial records: 8,790
- Cleaned records: 8,786
- Total columns: 10
- Content types: Movies and TV Shows

The dataset was cleaned and validated before being used for subsequent analysis.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Plotly | Interactive visualizations |
| Jupyter Notebook | Analytical workflow |
| Tableau | Interactive dashboard development |

## Project Workflow

The project consists of six analytical stages:

| Notebook | Description |
|---|---|
| 01 - Data Cleaning | Data inspection, missing value assessment, standardization, duplicate identification, and data validation. |
| 02 - Content Type Analysis | Analysis of Movie and TV Show distribution. |
| 03 - Country Analysis | Examination of geographic content representation and distribution by content type. |
| 04 - Release Year Trend | Analysis of content distribution across release years. |
| 05 - Rating & Genre Analysis | Exploration of content ratings and genre composition. |
| 06 - Business Insights | Integration of analytical findings, business insights, recommendations, limitations, and conclusion. |

## Repository Structure

```text
Netflix-Content-Analysis/
│
├── Dataset/
│   ├── Raw_Dataset.csv
│   └── Cleaned_Netflix_Data.csv
│
├── Notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_Content_Type_Analysis.ipynb
│   ├── 03_Country_Analysis.ipynb
│   ├── 04_Release_Year_Trend.ipynb
│   ├── 05_Rating_Genre_Analysis.ipynb
│   └── 06_Business_Insights.ipynb
│
└── README.md
```

## Key Analytical Findings

The analysis of 8,786 cleaned records reveals several characteristics of Netflix's content catalog.

### 1. Content Type Distribution
- Movies account for 69.69% of the catalog.
- TV Shows represent 30.31%.
- Movies have a larger representation than TV Shows.

### 2. Geographic Representation
- The United States is the most represented country, accounting for 38.12% of records with available country information.
- The five most represented countries account for 66.18% of records with available country information.
- Geographic representation varies across content types.

### 3. Release Year Trends
- 2018 represents the largest release year group, with 1,144 titles.
- Movie records peak in 2018 with 766 titles.
- TV Show records peak in 2020 with 436 titles.

### 4. Content Ratings
- TV-MA is the most common rating category, representing 36.47% of the catalog.
- TV-14 follows with 24.53%.
- Rating distributions differ between Movies and TV Shows.

### 5. Genre Composition
The three most frequently represented genre labels are:
- International Movies: 31.31%
- Dramas: 27.58%
- Comedies: 19.04%

*Note: Genre percentages are based on multi-label classifications. A title may belong to multiple genres, so the percentages are not mutually exclusive.*

## Business Insights & Recommendations

Based on the analytical findings, several areas may warrant further evaluation:

- **Content Portfolio Balance:** Evaluate the distribution of Movies and TV Shows in relation to broader content portfolio objectives.
- **Geographic Representation:** Review the distribution of content across countries and identify potential areas for further geographic analysis.
- **Genre and Rating Diversity:** Examine the representation of genres and content classifications across the catalog.
- **Catalog Recency:** Monitor the distribution of titles by release year to better understand the composition of older and newer content.

These recommendations are intended to support further portfolio evaluation. Actual content investment or acquisition decisions would require additional business performance data.

## Tableau Dashboard

An interactive Tableau dashboard will be published to provide a consolidated visual overview of the analytical findings.

**Dashboard Link:** [View Interactive Tableau Dashboard](https://public.tableau.com/shared/TGYSKQM8C?:display_count=n&:origin=viz_share_link)

## Analysis Limitations

- The analysis is based on content metadata, not actual viewing or business performance data.
- The dataset contains missing values, particularly in the director and country columns.
- Genre classifications are multi-label, meaning individual titles can be associated with multiple genres.
- Movie and TV Show rating classifications are not entirely equivalent.
- The available release years range from 1925 to 2021.
- The findings describe the available dataset and should not be interpreted as a complete representation of Netflix's current global catalog.

Consequently, this analysis cannot directly establish audience preferences, viewing behavior, engagement, revenue, profitability, or content performance.

## Conclusion

This project provides an integrated overview of Netflix's content catalog through multiple analytical dimensions.

The findings highlight a catalog with a larger representation of Movies, substantial geographic concentration, diverse content classifications, and varying genre and release year distributions.

Through Python-based exploratory analysis and Tableau visualization, this project demonstrates a structured approach to transforming raw content metadata into meaningful analytical findings and potential business insights.

## Author

**Muhammad Ziko Ananda Setyawan**

Data Analyst | Business Intelligence Enthusiast

GitHub: [zikosetyawan](https://github.com/zikosetyawan)