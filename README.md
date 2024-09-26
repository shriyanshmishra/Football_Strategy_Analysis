# **Football Strategy Data Analysis**

## **Project Overview**
This project analyzes a dataset of football game scenarios to provide insights into coaching decisions made during different plays. Using data analytics, we explore relationships between various attributes, such as decision types (antecedents), confidence levels, and the timing of judgments. The aim is to extract key metrics that can inform future strategies based on the data provided.

## **Technologies Used**
- **Python**: For data analysis and cleaning.
- **Pandas**: To handle and process the dataset.
- **Matplotlib & Seaborn**: For creating visualizations that highlight key insights.
- **Power BI**: Optional tool used to visualize trends interactively.

## **Key Insights**
1. **Confidence Levels by Decision Type**:
   - Decisions like "pass", "run", and "kick a field goal" were the most common actions taken.
   - Confidence levels for these decisions varied, with certain actions being made with higher confidence on average.

2. **Judgments Over Time**:
   - We analyzed the frequency of judgments made over several days and found patterns in how coaching decisions changed as the game progressed.
   - The busiest periods in the dataset occurred on certain dates, indicating peaks in decision-making activity.

3. **Distribution by Time of Day**:
   - The dataset was further explored to see how decisions were distributed across different times of day (Night, Morning, Afternoon, and Evening).
   - Evening sessions saw the most frequent decisions, particularly for actions like "pass" and "run".

## **Project Structure**
- **Data Cleaning and Preprocessing**:
  - Missing values in the dataset were handled.
  - The dataset was prepared by converting relevant columns into appropriate formats, especially timestamps.
  
- **Exploratory Data Analysis (EDA)**:
  - Confidence levels were grouped and visualized by decision types.
  - Judgments were analyzed over time, providing insights into the busiest periods.
  - The analysis also considered the distribution of decisions across various times of day.

## **How to Run**
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/shriyanshmishra/Football_Strategy_A
   nalysis.git
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the Jupyter notebook or run the Python script to view the data analysis and visualizations.

## **Conclusion**
This analysis offers valuable insights into football coaching decisions based on real game scenarios. The project reveals patterns in decision-making that can help inform strategies in similar situations.


