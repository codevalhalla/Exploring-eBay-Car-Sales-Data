# Analyzing Used Car Listings on eBay Kleinanzeigen

## Overview

This project involves the analysis of a dataset containing used car listings from *eBay Kleinanzeigen*, a classifieds section of the German eBay website. The dataset consists of various attributes related to the listed cars, such as their price, mileage, brand, and more. The goal of the project is to clean the data and perform an exploratory analysis to gain insights into the used car market.

## Dataset Source

The original dataset was scraped and uploaded to [Kaggle](https://www.kaggle.com/orgesleka/used-cars-database/data). For this project, we are using a sample of 50,000 data points prepared by [Dataquest](https://www.dataquest.io), which includes a less-cleaned version of the data. The data dictionary provides details about each attribute's meaning and values.

## Project Steps

1. **Data Cleaning**: The project starts with loading the dataset using Python's Pandas library and exploring its contents. Columns are cleaned, renamed, and unnecessary columns are removed. Numeric values stored as text (e.g., prices and odometer readings) are cleaned and converted to numeric data types.

2. **Exploratory Data Analysis**: Various aspects of the data are explored, including the distribution of listings by date, vehicle type, and brand. Outliers and unrealistic values are addressed, such as extreme price values.

3. **Date Analysis**: Date columns are examined to understand trends in listings' creation and last seen dates. Invalid registration years are handled, and the distribution of registration years is analyzed.

4. **Brand and Price Analysis**: The distribution of car brands is investigated, with a focus on the top brands. The relationship between brand, price, and mileage is explored, shedding light on market trends.

5. **Conclusion**: The project concludes with insights drawn from the data analysis, highlighting significant findings and trends in the used car listings.

## Technologies Used

- Python
- Pandas
- Data Cleaning
- Exploratory Data Analysis

## Project Benefits

This project offers the following benefits:
- Real-world data analysis experience.
- Proficiency in data cleaning and preparation.
- Understanding data distributions and trends.
- Visualizing insights using Python libraries.
- Gaining familiarity with working on messy datasets.

Feel free to explore the project's [Jupyter Notebook](https://github.com/vajrastra/Exploring-eBay-Car-Sales-Data/blob/main/Exploring%20eBay%20Car%20Sales%20Data.ipynb) for a detailed walkthrough of the analysis.

## Contact

For any questions or collaborations, feel free to contact me:

- GitHub: [vajrastra](https://github.com/vajrastra)
- Email: prsk3496@gmail.com