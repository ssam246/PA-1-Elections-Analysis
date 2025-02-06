# PA-1 2024 Election Analysis

This repository provides a comprehensive analysis of the 2024 election for Pennsylvania's 1st Congressional District (PA-1). The project integrates voter turnout data, candidate engagement metrics, social media sentiment analysis, and spatial analysis to predict election outcomes. The repository is structured to include data preprocessing, exploratory data analysis, modeling, and visualization.
https://ssam246.github.io/PA-1-Elections-Analysis/


---

## Features
1. **Social Media Analysis**:
   - Tracks engagement metrics for Donald Trump and Kamala Harris across Twitter, YouTube, and Instagram.
   - Sentiment analysis of hashtags and media mentions.
2. **Spatial Analysis**:
   - Choropleth maps showcasing partisan lean and turnout trends.
3. **Predictive Modeling**:
   - Linear Regression for predicting voter turnout and candidate performance.
   - Analysis of media tone and its impact on public opinion.

---

## Requirements

### Python Libraries
To run this project, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn
- geopandas (for spatial analysis)

Install all required libraries using:
```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn geopandas
```

## Dataset Sources

- **Precinct-level Data**:  
  `Precincts_17(1).csv`  
  Provides official election results at the precinct level.

- **Summary Data**:  
  `summary_17.csv`  
  Contains engagement and turnout summaries.

- **GeoJSON Spatial Data**:  
  `Bucks_County_Voting_Precincts_2024.geojson`  
  Spatial data for mapping precincts in PA-1.

---

## How to Run

### Step 1: Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/ssam246/PA-1-2024-Election-Analysis.git
cd PA-1-2024-Election-Analysis
