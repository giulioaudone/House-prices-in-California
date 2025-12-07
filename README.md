# House-prices-in-California
## **Project Goal**
The objective is twofold:
  - Develop a robust predictive model to estimate the median house price in specific California housing blocks.
  - Identify and quantify the main drivers (influencing factors) that determine real estate value.
  - This work supports strategic decisions regarding resource allocation, investment, and market valuation.

## **Methodology and Model**
The methodological focus was placed on correlation analysis and the selection of the most impactful features.
**Chosen Algorithm**: A Random Forest Regressor model was used for its ability to model complex relationships and its excellent interpretability through feature importance.
**Key Metrics**: The model was evaluated using R^2 (coefficient of determination) to measure the proportion of explained variance
**Feature Importance**: The evaluation of feature importance is a key deliverable, as it directly answers business questions about the main valuation factors.

## **Results and Business Implications**
The model demonstrates strong predictive capability. However, the Exploratory Data Analysis (EDA) and feature importance offer the most significant insights:
**Identified Value Drivers**:
  - Median Income: As expected, the median income within the housing block is the strongest predictive driver.
  - Ocean Proximity: The categorical variable related to ocean proximity is the second most influential feature, quantifying the impact of the "location factor."
  - Median House Age: The age of the houses contributes significantly, often in inverse correlation with value (unless they are valuable historical buildings).

**Strategic Recommendations**:
  - Market Segmentation: I recommend dividing the analysis by region (e.g., Coastal vs. Inland) to develop localized models. Model accuracy can be significantly improved by modeling distinct markets separately.
- Data Investment: Integrating external data such as school quality index or local crime rates is recommended, as these are believed to have a strong correlation with income and real estate value but were not included in the current dataset.

## **Tools Used**
**Language**: Python
**Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
**Environment**: Jupyter Notebook
