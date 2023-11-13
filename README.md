# Data Analysis Project

## Overview

This repository contains code and documentation for a data analysis project. The project aims to explore different methods of data analysis using a sufficiently large dataset, perform EDA to get insights on the data, and use them for predictive analysis.

## Project Structure

- `/data`: This folder contains the raw and processed data used in the analysis.
- `/notebooks`: Jupyter notebooks for data exploration, analysis, and visualization.
- `/scripts`: Python scripts used in the data processing pipeline.
- `/results`: Output files and visualizations generated from the analysis.

## Dataset Information
- The Dataset terminology can be referred here: https://unstats.un.org/unsd/classifications/Econ/Download/In%20Text/ISIC_Rev_3_English.pdf
- The column description is as follows:
    1. CountryID: An identifier or code for each country.
    2. Country: The name of the country.
    3. Year: The year to which the data corresponds.
    4. AMA Exchange Rate: Exchange rate determined by the Austrian National Bank (AMA).
    5. IMF Based Exchange Rate: Exchange rate based on International Monetary Fund (IMF) data.
    6. Population: The total population of the country.
    7. Currency: The official currency of the country.
    8. Per Capita GNI: Gross National Income (GNI) per capita, a measure of the average income of a country's residents.
    9. Agriculture, Hunting, Forestry, Fishing (ISIC A-B): Economic activity related to agriculture and related sectors according to the International Standard Industrial Classification (ISIC) system.
    10. Changes in Inventories: The change in a company's inventory over a specific time period.
    11. Construction (ISIC F): Economic activity related to construction according to ISIC.
    12. Exports of Goods and Services: The total value of goods and services a country exports.
    13. Final Consumption Expenditure: Total expenditure by households and government on goods and services for final consumption.
    14. General Government Final Consumption Expenditure: Government expenditure on goods and services for final consumption.
    15. Gross Capital Formation: Total investment in a country, including changes in inventories.
    16. Gross Fixed Capital Formation (Including Acquisitions Less Disposals of Valuables): Total investment in fixed assets, excluding changes in inventories.
    17. Household Consumption Expenditure (Including Non-profit Institutions Serving Households): Household spending on goods and services for final consumption, including spending by non-profit institutions serving households.
    18. Imports of Goods and Services: The total value of goods and services a country imports.
    19. Manufacturing (ISIC D): Economic activity related to manufacturing according to ISIC.
    20. Mining, Manufacturing, Utilities (ISIC C-E): Economic activities related to mining, manufacturing, and utilities according to ISIC.
    21. Other Activities (ISIC J-P): Economic activities not covered by other specific categories, according to ISIC.
    22. Total Value Added: The total value added to a country's economy through various economic activities.
    23. Transport, Storage, and Communication (ISIC I): Economic activities related to transportation, storage, and communication according to ISIC.
    24. Wholesale, Retail Trade, Restaurants, and Hotels (ISIC G-H): Economic activities related to wholesale and retail trade, restaurants, and hotels according to ISIC.
    25. Gross National Income (GNI) in USD: The total GNI of the country expressed in U.S. dollars.
    26. Gross Domestic Product (GDP): The total economic output of a country, often used as an indicator of a country's economic health and performance.

## Requirements

- Python 3.x
- Jupyter Notebook
- Additional Python libraries (specified in `requirements.txt`)

## Installation

1. Clone the repository:
   git clone https://github.com/your-username/data-analysis-project.git
2. Install dependencies:
    pip install -r requirements.txt
3. Explore the analysis notebooks in the notebooks/ directory.

## Usage
- Run the Jupyter notebooks in the notebooks/ directory for detailed analysis steps.
- Execute scripts in the scripts/ directory for specific data processing tasks.

## Results
- The results are stored in results/ folder.