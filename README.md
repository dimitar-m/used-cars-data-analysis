# Accelerating Deals: Data-Driven Analysis of eBay Kleinanzeigen Used Cars

## Introduction

Welcome to my data analysis project on eBay Kleinanzeigen used cars. This project aims to understand the factors influencing used car prices and identify significant trends within the dataset. By analyzing various attributes such as brand, model, mileage, and damage status, this project provides valuable insights that can help buyers and sellers make more informed decisions.

## Project Goals

- Explore the dataset to uncover insights about used car prices.
- Identify key factors affecting vehicle pricing.
- Analyze common brand and model combinations.
- Determine the impact of mileage and damage status on car prices.

## Dataset Overview

The dataset used for this analysis contains the following key features:
- **Total Rows**: 50,000+
- **Columns**: date_crawled, name, seller, offer_type, price, abtest, vehicle_type, registration_year, gearbox, power_ps, model, odometer_km, registration_month, fuel_type, brand, unrepaired_damage, ad_created, num_of_pictures, postal_code, last_seen

## Key Questions Addressed

1. What are the most common brand/model combinations?
2. How do various factors like mileage and damage status affect car prices?
3. What are the price trends for different car brands?
4. How significant is the price difference between damaged and non-damaged cars?

## Summary of Findings

- **Price Differences**: Cars with unrepaired damage are significantly cheaper than their non-damaged counterparts, with an average price difference of $4922.89.
- **Brand Analysis**: Common brand and model combinations were identified, providing insights into popular choices among used car buyers.
- **Mileage Impact**: The analysis of mileage showed its correlation with car prices, helping understand depreciation patterns.
- **Market Trends**: Aggregated data revealed trends in pricing for different car brands and models, offering a snapshot of the used car market.

## Detailed Analysis

For a detailed step-by-step analysis, including data cleaning, transformation, and visualizations, please refer to the project notebook. This comprehensive analysis includes:

1. Data Cleaning: Handling missing values, translating German categorical data, and standardizing date formats.
2. Data Transformation: Converting dates to numeric formats, extracting keywords from names, and creating new columns.
3. Statistical Analysis: Calculating mean prices and mileage, identifying trends, and comparing damaged vs. non-damaged cars.

## Getting Started

To explore the analysis:

1. Clone the repository: `git clone https://github.com/dimitar-m/used-cars-data-analysis.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter notebook to see the detailed analysis.

## Conclusion

This project provides a thorough analysis of the eBay Kleinanzeigen used car market, uncovering key insights into factors affecting car prices. These findings can help both buyers and sellers make more informed decisions in the used car market.

## Feedback and Contributions

I welcome any feedback or discussions on these findings. Feel free to open issues or submit pull requests if you have suggestions for improvements or additional analyses.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Thank you for your interest in this project!

Best regards,  
[Dimitar Mikov]
