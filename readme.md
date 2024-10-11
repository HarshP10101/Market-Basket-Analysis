# 🛒 Market Basket Analysis with Dynamic Pricing and Customer Segmentation

### 📋 Project Overview
This project uses **Market Basket Analysis** to uncover purchasing patterns and optimize product placement, cross-selling, and dynamic pricing strategies in a grocery store setting. By understanding which products are frequently bought together, we can enhance the customer shopping experience, improve inventory management, and maximize profitability. 

### 🎯 Objectives
1. **Identify Product Associations**: Leverage association rule mining to uncover frequently bought-together items.
2. **Implement Dynamic Pricing**: Create pricing models to optimize revenue based on real-time demand for specific product bundles.
3. **Customer Segmentation**: Use clustering algorithms to segment customers based on their shopping behavior, enabling personalized promotions and targeted marketing.

### 🔍 Key Features
- **Association Rule Mining**: Identifies product pairs and groups that are commonly purchased together, using the Apriori algorithm.
- **Dynamic Pricing Analysis**: Simulates different pricing strategies, such as bundle discounts and high-demand price increases, to determine the best approach for enhancing profitability.
- **Customer Segmentation**: Groups customers into segments based on their purchase history using K-Means clustering, allowing for customized promotional strategies.
  
### 🛠️ Technologies Used
- **Python**: Core language for data processing and analysis.
- **Pandas & NumPy**: Data manipulation and mathematical operations.
- **MLxtend**: Implements the Apriori algorithm for association rule mining.
- **Matplotlib**: Data visualization for interpreting results and insights.

### 🚀 Project Structure

```plaintext
📁 Market Basket Analysis
├── 📄 Market_Basket_Analysis.ipynb        # Jupyter Notebook containing the project code
├── 📄 README.md                           # Project overview and instructions
├── 📄 requirements.txt                    # List of dependencies
└── 📂 data                                # Folder for datasets
```

### 📈 Analysis Highlights
1. **Product Placement Insights**: Based on identified product associations, recommended store layout optimizations to encourage additional purchases by placing high-association products nearby. Products like whole milk, yogurt, and rolls/buns showed strong associations, indicating potential for bundle promotions and strategic placement.
   
2. **Revenue Impact**: Tested various pricing strategies to compare the effects of bundle discounts vs. high-demand price increases. This analysis informed decisions on the most profitable dynamic pricing strategy for each product combination. Both bundle discounts and high-demand pricing improved revenue. Bundle discounts encouraged larger basket sizes, while demand-based pricing maximized profitability during peak times.