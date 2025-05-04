# covid19-analysis
This project explores the relationship between happiness scores and COVID-19 statistics across different countries using data analysis and visualization techniques in Python.

📁 Dataset Sources
World Happiness Report: Contains scores and contributing factors for happiness by country.

COVID-19 Data: Includes confirmed cases, deaths, and recoveries for each country.

📌 Project Objectives
Merge happiness and COVID-19 datasets using the country name.

Perform exploratory data analysis (EDA).

Visualize key relationships such as:

Deaths vs Happiness Score

Correlation heatmaps between variables

Identify possible trends or insights linking happiness and pandemic outcomes.
📂 Project Structure
├── data/
│   ├── happiness.csv
│   └── covid.csv
├── analysis.ipynb
└── README.md

⚠️ Notes
Make sure column names match when merging data (Country vs Country/Region).

Non-numeric columns must be excluded before computing correlations.

📈 Sample Visualizations
Scatter plots comparing happiness scores to COVID deaths

Heatmap of correlations between happiness factors and pandemic stats
