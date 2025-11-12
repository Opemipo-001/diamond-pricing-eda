
# Diamond Pricing EDA

This repository contains an **exploratory data analysis (EDA)** of the famous **diamonds dataset**. The analysis is performed using **Python**, leveraging **Pandas, NumPy, Seaborn, Matplotlib, and Plotly** for data manipulation and visualization. The goal is to uncover insights about diamond prices and their relationships with other features such as carat, cut, color, clarity, and volume.

## Dataset

The dataset used is the classic `diamonds.csv`, which contains information about approximately 54,000 diamonds, including:

- **price**: Price of the diamond in US dollars
- **carat**: Weight of the diamond
- **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- **color**: Diamond color from D (best) to J (worst)
- **clarity**: Diamond clarity (I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF)
- **x, y, z**: Length, width, and depth of the diamond in mm
- **depth**: Total depth percentage
- **table**: Width of the top of the diamond relative to width

Additional features derived in this analysis:
- **volume** = x * y * z
- **price_per_carat** = price / carat

## Analysis

The analysis includes:

1. **Data Cleaning and Preprocessing**
   - Removing unnecessary columns
   - Checking for missing values
   - Feature engineering (volume, price_per_carat)

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots of price, carat, and volume
   - Count plots for categorical variables (cut, color, clarity)
   - Scatter plots showing price vs carat and price vs volume
   - Correlation analysis with heatmaps

3. **Interactive Visualizations**
   - Interactive bar charts and scatter plots using Plotly
   - Insights on diamond pricing trends based on features

## Insights

Some key observations from the dataset:

- Diamond price increases non-linearly with carat.
- Ideal and Premium cuts generally have higher prices per carat.
- Larger diamonds (by volume) tend to be more expensive, but there are outliers.
- Clarity and color significantly impact diamond pricing trends.
