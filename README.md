# Retail-Optimization
A comprehensive demand forecasting system built with Facebook Prophet to solve the $1.1 trillion inventory distortion problem in retail. This project demonstrates how machine learning can optimize inventory levels, reduce carrying costs, and prevent stockouts while maintaining high service levels.

Key Results
- 34.7% improvement in forecast accuracy over naive benchmarks (MAE reduction: 120.19 → 78.43 units)

- Near-zero forecast bias (-1.94 units, ≈1.4% of average daily sales)

- Identified 20-30% potential reduction in safety stock requirements

- Maintained 0% stockout rate while optimizing inventory investment (possible due to using sythetic data)


Project Structure
Retail-Optimization/
├── data/
│   └── retail_store_inventory.csv      # Dataset used for analysis
├── notebooks/
│   └── Retail Optimization Project.ipynb  # Complete analysis & modeling
├── requirements.txt                    # Package dependencies
└── README.md                          # This file

Technical Implementation
Technologies Used
- Python: Pandas, NumPy, Matplotlib, Seaborn

- Forecasting: Facebook Prophet with custom regressors

- Validation: Time-series cross-validation

- Analysis: Comprehensive EDA and business intelligence

Key Features
- Multivariate forecasting with external regressors (price, promotions, weather, competitor pricing)

- Product-store level granularity for precise inventory management

- Robust evaluation framework with multiple error metrics

- Business-friendly visualizations and interpretations

Instalation instructions
# 1. Clone the repository
git clone https://github.com/jordanshamu/Retail-Optimization.git

# 2. Navigate to project directory
cd Retail-Optimization

# 3. Install required dependencies
pip install -r requirements.txt

# 4. Launch Jupyter notebook
jupyter notebook notebooks/Retail\ Optimization\ Project.ipynb

Key Insights
Technical Learnings
- Future regressor estimation is the primary forecasting challenge

- Error metrics require business context to be actionable

- Incremental improvements (34.7%) deliver significant business value

Business Implications
- Cross-functional collaboration is essential for accurate forecasting

- Inventory optimization requires explicit trade-off decisions

- Interpretable models build trust and enable business adoption


Author
Jordan Shamukiga - www.linkedin.com/in/jordan-shamukiga-6464502b0 | datascienceportfol.io/jordanshamu

📄 License
This project is licensed under the MIT License.
