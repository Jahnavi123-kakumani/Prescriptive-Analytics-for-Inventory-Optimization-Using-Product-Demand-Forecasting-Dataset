# Prescriptive Analytics for Inventory Optimization  

## Overview  

This project demonstrates the use of **prescriptive analytics** techniques to optimize inventory management using the **Product Demand Forecasting Dataset** from Kaggle. Optimization algorithms like **linear programming**, **integer programming**, and **mixed-integer programming** were applied to find cost-effective and profit-maximizing solutions for inventory management.  

---

## Dataset  

**Source**: [Product Demand Forecasting Dataset on Kaggle](https://www.kaggle.com/felixzhao/productdemandforecasting)  

The dataset provides historical product demand data, including features such as:  
- **Product ID**: Unique identifier for each product.  
- **Warehouse ID**: Location of the product stock.  
- **Date**: Date of demand recorded.  
- **Order Demand**: Quantity of the product demanded.  

---

## Objectives  

1. Analyze the dataset to uncover demand trends and patterns.  
2. Apply prescriptive analytics techniques to optimize:  
   - Inventory holding costs.  
   - Ordering costs.  
   - Stockout costs.  
3. Use optimization algorithms:  
   - **Linear Programming (LP)**.  
   - **Integer Programming (IP)**.  
   - **Mixed-Integer Programming (MIP)**.  
4. Perform **sensitivity analysis** to measure the impact of changes in parameters such as demand, lead time, and holding costs.  
5. Evaluate the solution using metrics like:  
   - Total cost.  
   - Revenue.  
   - Profit.  

---

## Methodology  

1. **Data Preparation**:  
   - Loaded and cleaned the dataset.  
   - Conducted exploratory data analysis (EDA) to understand demand patterns.  

2. **Optimization Models**:  
   - Developed models using **Python libraries** like `pulp` and `scipy.optimize`.  
   - Optimized inventory management processes while adhering to business constraints.  

3. **Evaluation Metrics**:  
   - Compared costs, revenues, and profits before and after applying optimization techniques.  

4. **Sensitivity Analysis**:  
   - Measured how variations in key parameters impact the optimal solution.  

---

## Results  

- **Cost Savings**: Significant reduction in holding and ordering costs.  
- **Profit Maximization**: Improved inventory strategy led to increased profitability.  
- **Scalability**: Solutions are scalable to other products or warehouses.  

---

## Tools & Technologies  

- **Programming Language**: Python  
- **Libraries**:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `pulp`  
  - `scipy`  

---

## Instructions  

### Prerequisites  

1. Install the required libraries:  

   ```bash  
   pip install pandas numpy matplotlib seaborn pulp scipy  
   ```  

2. Download the dataset from [Kaggle](https://www.kaggle.com/felixzhao/productdemandforecasting).  


## Deliverables  

1. **Jupyter Notebook**:  
   - Full implementation of optimization techniques.  
   - Visualizations of results.  
