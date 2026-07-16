# ABC-XYZ Inventory Analysis

## Project Goal

The objective of this project was to classify products according to their business importance and demand stability using the **ABC-XYZ analysis** methodology. The analysis aims to identify which products require strict inventory control, which can be managed using standard replenishment strategies, and which may be candidates for inventory reduction or discontinuation.

---

## Dataset

The dataset contains transactional sales data for multiple products and includes information required for inventory segmentation and demand analysis.

**Main features:**
- Product ID
- Product Name
- Sales Date
- Quantity Sold
- Sales Revenue

The data was aggregated at the product level to calculate total sales and demand variability for each product.

---

## Tools & Libraries

**Programming Language**
- Python

**Libraries**
- pandas
- numpy
- matplotlib
- seaborn

**Methods**
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- ABC Analysis
- XYZ Analysis
- Coefficient of Variation (CV)
- Data Visualization

---

## Project Workflow

1. Imported and explored the sales dataset.
2. Cleaned and prepared the data for analysis.
3. Calculated total sales for each product.
4. Performed **ABC analysis** by ranking products according to cumulative sales contribution.
5. Calculated the **Coefficient of Variation (CV)** to measure demand variability.
6. Classified products into **X, Y, and Z** demand stability groups.
7. Combined both classifications to build the **ABC-XYZ matrix**.
8. Visualized the distribution of products across all inventory categories.
9. Interpreted the results and developed business recommendations for inventory optimization.

---

## Results

The analysis segmented products into nine inventory categories based on their sales contribution and demand stability.

### ABC Classification

- **Category A** products generated the majority of total revenue and require the highest management priority.
- **Category B** products represent medium business importance and require regular inventory control.
- **Category C** products contribute the least to total sales and can be managed with simplified inventory policies.

### XYZ Classification

- **Category X** products exhibit stable demand and can be forecast with high accuracy.
- **Category Y** products show moderate demand variability.
- **Category Z** products have highly irregular demand and require flexible inventory strategies.

The combined **ABC-XYZ matrix** provides a complete overview of product profitability and demand stability, enabling better inventory management decisions.

---

## Business Recommendations

Based on the ABC-XYZ segmentation, the following inventory strategies are recommended:

| Category | Recommendation |
|----------|----------------|
| **AX** | Maintain high service levels with continuous inventory monitoring and accurate demand forecasting. |
| **AY** | Monitor regularly and adjust inventory according to seasonal or moderate demand fluctuations. |
| **AZ** | Keep safety stock and review inventory frequently due to unpredictable demand. |
| **BX** | Apply standard inventory replenishment policies and periodic reviews. |
| **BY** | Monitor inventory levels and update forecasts when demand patterns change. |
| **BZ** | Use conservative purchasing strategies to reduce excess inventory risk. |
| **CX** | Maintain minimal stock levels and replenish only when necessary. |
| **CY** | Apply simplified inventory control with periodic stock reviews. |
| **CZ** | Evaluate product profitability regularly and consider inventory reduction or product discontinuation if business value remains low. |

---

## Conclusion

The **ABC-XYZ analysis** successfully segmented products according to their contribution to total sales and demand stability, providing a clear framework for inventory management and decision-making.

### Key Findings

- **AX and AY** products represent the most valuable inventory items. They generate the highest share of revenue while maintaining stable or moderately stable demand, making them the highest priority for inventory control.
- **AZ and BZ** products contribute significantly to revenue but exhibit irregular demand. These categories require demand forecasting, safety stock, and frequent inventory monitoring to reduce the risk of stockouts or excess inventory.
- **BX and BY** products have medium business importance and can be managed using standard replenishment strategies.
- **CX and CY** products have a relatively small impact on total sales and stable demand, allowing for simplified inventory management.
- **CZ** products combine low sales contribution with highly unpredictable demand. These items should be reviewed regularly to determine whether inventory levels should be reduced or the products should be discontinued.

### Business Value

The ABC-XYZ analysis demonstrates how combining product profitability with demand variability leads to more effective inventory management. This approach helps businesses prioritize high-value products, optimize stock levels, reduce storage costs, improve forecasting accuracy, and allocate resources more efficiently.

Overall, this project demonstrates the practical application of data analysis techniques for inventory optimization and supports data-driven business decisions.
