# EDA-retail

# Exploratory Data Analysis on Retail Data

## Project Overview

In this project, we perform **Exploratory Data Analysis (EDA)** on a retail dataset (`SampleSuperstore.csv`). The goal is to analyze the data to find weak areas in the business where improvements can be made to increase profit. As a business manager, this analysis provides insights to help focus efforts on optimizing performance and profitability.

## Dataset

The dataset contains information about the retail operations, including sales transactions, customer segments, and geographical data.

### Key Columns:
- **Ship Mode**: Shipping method for the product.
- **Segment**: Customer segment (Consumer, Corporate, Home Office).
- **Country**: The country where the sale took place.
- **City, State, Postal Code**: Location details of the sales.
- **Region**: Regional classification within the country.
- **Category**: Main product categories (Furniture, Office Supplies, Technology).
- **Sub-Category**: More specific product types (Chairs, Labels, etc.).
- **Sales**: The revenue generated from the sales.
- **Quantity**: Number of items sold.
- **Discount**: Discount applied to the sale.
- **Profit**: Profit from the sale.

### Sample Data:
| Ship Mode      | Segment   | Country       | City            | State      | Sales    | Quantity | Discount | Profit   |
|----------------|-----------|---------------|-----------------|------------|----------|----------|----------|----------|
| Second Class   | Consumer  | United States | Henderson       | Kentucky   | 261.96   | 2        | 0.00     | 41.91    |
| Standard Class | Consumer  | United States | Fort Lauderdale | Florida    | 957.57   | 5        | 0.45     | -383.03  |

## Objectives

- Understand the business's sales performance across different regions, categories, and segments.
- Identify areas where profit margins are low and explore potential causes (e.g., high discounts, low sales).
- Provide actionable insights for improving business operations and increasing profitability.

## Tools Used

- **Python**: The programming language used for analysis.
- **Jupyter Notebook**: For writing and executing the analysis code.
- **Pandas**: For data manipulation and exploration.
- **Matplotlib and Seaborn**: For data visualization and plotting.
  
## Project Workflow

1. **Data Loading**:
   - Load the `SampleSuperstore.csv` dataset.
   - Inspect the structure and content of the data.
  
2. **Data Cleaning**:
   - Handle missing values and remove any duplicates in the dataset.
   - Ensure that the data is consistent and ready for analysis.

3. **Exploratory Data Analysis**:
   - Analyze the **Sales**, **Profit**, and **Discount** data across various segments (Regions, Categories, Customer Segments).
   - Visualize key trends using graphs like bar plots, histograms, and scatter plots.
   - Investigate patterns and correlations to find areas of improvement.

4. **Key Insights**:
   - Identify regions or product categories with low profits or high discounts.
   - Explore the effect of shipping modes and customer segments on overall profitability.

## Results and Findings

- **Sales Performance**: The analysis shows that certain regions consistently outperform others in terms of sales, while other regions may need more focus due to lower profit margins.
- **Profitability**: Some product categories, especially with high discounts, tend to result in negative profits. These areas require attention to reduce discounting strategies or increase sales.
  
## Conclusion

By identifying the weak areas in the business using EDA, managers can focus on improving sales strategies and optimizing product categories to boost profitability.

## How to Run the Project

1. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```

2. Open the Jupyter notebook `assignment2.ipynb` and execute the cells to run the analysis.

3. Visualizations and insights will be generated within the notebook to guide business decisions.
