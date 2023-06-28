# Diamond Analysis Project

## Objective
To analyze the characteristics and pricing of diamonds using the built-in `diamonds` dataset from the `ggplot2` library in R. The project aims to answer specific questions about diamond attributes and their relationship to price, particularly focusing on engagement ring selection.

## Dataset Used
The analysis uses the `diamonds` dataset from the `ggplot2` library in R. This dataset contains information on 53,940 round-cut diamonds, including attributes such as carat weight, cut quality, color, clarity, and price.

## Analysis Techniques

The project employs various data analysis and visualization techniques using R:

1. **Data Loading and Exploration**: 
   - Utilized **`tidyverse`** and **`dplyr`** for data manipulation
   - Used **`glimpse()`** function to review data structure

2. **Data Visualization**:
   - Employed **`ggplot2`** for creating various types of plots:
     - Histograms and boxplots for price distribution
     - Boxplots for comparing table values across cut grades
     - Pie charts for clarity segment analysis
     - Scatter plots with trend lines for price-carat correlation
     - Bar charts for average price analysis
   - Used **`patchwork`** library for combining multiple plots

3. **Statistical Analysis**:
   - Calculated percentages and averages using **`dplyr`** functions like `group_by()`, `summarise()`, and `mutate()`
   - Applied sampling techniques using **`sample_n()`** function

4. **Data Transformation**:
   - Created new segments for clarity using **`mutate()`** and conditional statements
   - Filtered data for specific analyses using **`filter()`** function

5. **Advanced Visualization Techniques**:
   - Implemented faceting with **`facet_wrap()`** for multi-panel plots
   - Used **`geom_smooth()`** for adding trend lines to scatter plots
   - Applied custom color palettes and themes for enhanced aesthetics

6. **Scale and Axis Manipulation**:
   - Utilized **`scale_x_continuous()`** and **`scale_y_continuous()`** for customizing axis scales
   - Implemented **`scale_fill_manual()`** and **`scale_color_manual()`** for custom color schemes

## Results

1. The distribution of diamond prices is positively skewed with outliers.
2. Ideal-cut diamonds have a narrower range of table values compared to other cut grades.
3. Only 3.3% of the diamonds in the dataset are categorized as Internally Flawless (IF).
4. There's a positive correlation between carat weight and price for colorless diamonds (D, E, F colors).
5. For 1.00-1.25 carat Ideal-cut diamonds, prices increase significantly with higher clarity and color grades.

For a detailed view of the analysis and visualizations, you can access the [RPub Document here](https://rpubs.com/).

These insights provide valuable information for understanding diamond characteristics and pricing, particularly useful for engagement ring selection.