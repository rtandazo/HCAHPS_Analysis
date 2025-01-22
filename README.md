# **HCAHPS Patient Survey Exploratory Analysis**

---

## **Project Overview**

This project explores national and regional trends in HCAHPS (Hospital Consumer Assessment of Healthcare Providers and Systems) survey data. By leveraging Python for data cleaning, exploratory data analysis (EDA), and visualization, the project uncovers operational inefficiencies and patient satisfaction trends over time. The goal was to derive actionable insights to improve patient experience and response rates while aligning with healthcare quality metrics.

---

## **Key Features**

### **Python Pipeline**
- **Automated Data Cleaning**:
  - Processed raw data files into memory-efficient formats:
    - Optimized data types using `astype` to reduce memory usage
    - Standardized date columns for temporal analysis
    - Handled missing values and formatted categorical variables
  - Merged multiple datasets to create comprehensive analysis tables for:
    - National-level results
    - State and regional results
    - Survey response rates
  
- **Dynamic Data Aggregation**:
  - Calculated year-over-year changes in bottom-box, middle-box, and top-box percentages
  - Aggregated response rates at national, state, and regional levels

### **Exploratory Data Analysis (EDA)**
- **Key Trends Identified**:
  - National and regional response rates declined by 8% since 2015
  - Bottom-box scores showed significant improvement, but top-box scores steadily declined
  - Regions like South Atlantic and states such as D.C. and Alaska underperformed in response rates, highlighting opportunities for targeted intervention

- **Advanced Visualizations**:
  - Created dynamic bar charts, line plots, and subplots to illustrate:
    - Response rates by state and region
    - Year-over-year changes in box scores
    - Percent change in satisfaction measures like "Communication with Nurses" and "Discharge Information"

### **Insights and Findings**
- **Operational Performance**:
  - National response rates dropped 8% since 2015, limiting the dataset's representation and reliability
  - Regions like the South Atlantic and Pacific, and states such as D.C., New Jersey, and Alaska, consistently fell below the national average
- **Patient Experience**:
  - "Communication with Nurses" ranked as the lowest-scoring measure across all regions, indicating an area for significant improvement
  - Bottom-box scores improved the most, reflecting a reduction in extreme dissatisfaction

---

## **Skills Demonstrated**

### **Python Skills**
- **Data Cleaning and Transformation**:
  - Leveraged **Pandas** to efficiently clean and structure datasets
  - Used `merge` and `astype` methods to create memory-optimized, comprehensive data tables
  - Resampled time-series data to analyze trends across yearly intervals

- **Visualization and Storytelling**:
  - Designed impactful visualizations using **Seaborn** and **Matplotlib**:
    - Bar charts, line plots, and subplots to highlight trends and disparities
    - Custom annotations and dynamic legends for clear interpretation of findings

- **Data Exploration**:
  - Applied **groupby** and pivot table techniques to uncover patterns at national, state, and regional levels.
  - Automated calculation of year-over-year percentage changes for performance metrics
