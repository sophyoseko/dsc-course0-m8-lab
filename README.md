Aviation Accidents Data Analysis Project
Project Overview

This project analyzes aviation accident data to identify patterns in accident severity, weather conditions, and phases of flight.

The goal is to understand how operational and environmental factors influence fatal/serious injuries and aircraft destruction rates using data-driven insights.

Project Structure
dsc-course0-m8-lab/
│
├── Aviation_Accidents_Cleaning.ipynb
│   └── Data preprocessing, cleaning, and feature engineering
│
├── Aviation_Accidents_Data_Analysis.ipynb
│   └── Exploratory data analysis and visual insights
│
└── README.md
Data Cleaning Process

Notebook: Aviation_Accidents_Cleaning.ipynb

Key Tasks:
Handling missing values and inconsistent records
Standardizing categorical variables
Creating derived metrics (e.g., injury fractions, destruction indicators)
Preparing dataset for analysis
Output:

A clean, structured dataset suitable for statistical analysis and visualization

Data Analysis Process
Notebook: Aviation_Accidents_Data_Analysis.ipynb
Key Areas of Analysis:

Weather Conditions (VMC vs IMC)
Comparison of accident severity under visual vs instrument conditions
IMC conditions show higher injury severity and destruction rates

Phase of Flight Analysis
Evaluation of risk across different flight phases
Takeoff and landing phases show the highest severity
Cruise phase is comparatively safe

Injury & Destruction Metrics
Fatal/serious injury fraction analysis
Aircraft destruction probability by category

Visualizations Used
Bar plots (mean comparisons)
Violin plots (distribution analysis)
Grouped statistical summaries

These visualizations help reveal patterns in risk distribution across conditions.

Key Insights
IMC (poor visibility) conditions significantly increase accident severity
Critical flight phases (takeoff & landing) are the most dangerous
Cruise phase is the safest due to stable flight conditions
Accident severity is strongly influenced by operational context

Conclusion

The analysis shows that aviation risk is not uniform. Instead, it is heavily influenced by weather conditions and phase of flight.

Improving safety during critical flight phases and enhancing instrument-based navigation in poor visibility conditions can significantly reduce accident severity.

Tools & Technologies
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

How to Run the Project
# Step 1: Open folder
cd dsc-course0-m8-lab

# Step 2: Launch Jupyter
jupyter notebook

Then open:

Aviation_Accidents_Cleaning.ipynb
Aviation_Accidents_Data_Analysis.ipynb

Author

Data Science Student Project – Aviation Accident Analysis
