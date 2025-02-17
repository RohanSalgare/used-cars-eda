# Used Cars EDA

## Overview

This repository contains an exploratory data analysis (EDA) of a dataset consisting of used car listings. The analysis aims to uncover patterns, trends, and insights from the given dataset.

This is a **guided project**, designed to help users learn and practice EDA techniques with real-world data.

## Dataset Information

The dataset comprises **7,253** entries and **14** columns, including details such as car name, location, year of manufacture, kilometers driven, fuel type, transmission type, owner type, mileage, engine specifications, power, seating capacity, new price (if available), and selling price.

- The dataset contains missing values in multiple columns, including **Mileage, Engine, Power, Seats, New\_Price, and Price**.
- The **New\_Price** column has significantly fewer entries compared to other features.
- The **Price** column is the target variable representing the selling price of used cars.

## Objectives of EDA

- Handling missing values in the dataset.
- Understanding the distribution of numerical and categorical features.
- Identifying correlations between different features.
- Detecting outliers and anomalies in car prices.
- Visualizing trends in price, mileage, and engine power.
- Gaining insights into factors affecting the price of used cars.

## Key Insights

- **Location Trends**: Mumbai has the highest number of used cars available for purchase, followed by Hyderabad and Kochi.
- **Fuel Preference**: Most cars available are **Diesel** since diesel cars provide better performance and are more cost-effective than petrol cars.
- **Transmission Type**: **71%** of the available cars have **Manual** transmission.
- **Seating Capacity**: The majority of available cars are **5-seaters (84%)**, followed by **7-seaters (11%)**.
- **Brand Popularity**: **Maruti** ranks first among all car brands in the used car market.

## Tools & Libraries Used

- **Python** for data analysis and visualization.
- **Pandas** for data manipulation.
- **Matplotlib & Seaborn** for visualization.
- **NumPy** for numerical operations.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/used-cars-eda.git
   ```
2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook used_cars_eda.ipynb
   ```

## Contact

For any queries, feel free to reach out via GitHub issues.

---

Happy analyzing! 🚗📊

