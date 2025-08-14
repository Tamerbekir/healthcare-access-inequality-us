# Healthcare Access Inequality in the U.S.

This project investigates disparities in healthcare access across U.S. counties using SQL and publicly available datasets. It focuses on how income, race, and geography affect access to primary care and insurance coverage.

## Objectives

- Identify counties with limited access to healthcare facilities
- Analyze correlations between income level and healthcare access
- Visualize uninsured rates by race and region
- Highlight geographic disparities in primary care availability

## 📊 Datasets Used

| Dataset | Source | Description |
|--------|--------|-------------|
| CDC Social Vulnerability Index | [CDC SVI](https://www.atsdr.cdc.gov/placeandhealth/svi/index.html) | Measures socioeconomic and demographic vulnerability |
| HRSA Health Center Data | [HRSA](https://data.hrsa.gov/) | Locations and services of federally funded health centers |
| U.S. Census Health Insurance Coverage | [Census](https://data.census.gov/) | Insurance coverage by race, income, and geography |

## 🛠Tools & Technologies

- **SQL**: Data cleaning, joining, and analysis
- **Tableau / Power BI** *(optional)*: For visualizing results

## Folder Overview

- `data/`: Raw CSV files from CDC, HRSA, and Census
- `sql/`: SQL scripts for cleaning and analysis
- `visualizations/`: Charts and maps generated from the analysis

## 📈 Key Insights (Example Goals)

- Counties with high social vulnerability often lack nearby health centers
- Uninsured rates are significantly higher in rural and low-income areas
- Racial disparities persist in healthcare access, especially in Southern states

## How to Run

1. Clone the repo  
   `git clone https://github.com/yourusername/healthcare-access-inequality-us.git`

2. Load the CSV files into your SQL database (e.g., PostgreSQL, SQLite, MySQL)

3. Run the SQL scripts in the `sql/` folder:
   - `clean_svi.sql`: Cleans and formats CDC data
   - `join_healthcare_data.sql`: Joins all datasets
   - `analysis_queries.sql`: Runs key insights queries

4. Use Tableau or Power BI to visualize the results

## Contact

Open to feedback, collaboration, or questions!
