# 📊 House Market Case Study: B15 Postcode, Edgbaston

This project aims to analyze the second-hand housing market in the B15 postcode area of Edgbaston, Birmingham. It explores the relationships between various factors such as property prices, number of bedrooms, and property types, providing insights to real estate agencies and potential buyers/sellers.

## 📚 Table of Contents

- [📥 Data Collection](#data-collection)
- [🔄 Data Preparation](#data-preparation)
- [🎲 Sampling](#sampling)
- [📈 Analysis and Visualization](#analysis-and-visualization)
- [🔍 Key Findings](#key-findings)
- [🚀 Usage](#usage)

## 📥 Data Collection

The data for this project was web-scraped from the popular real estate website, Rightmove, using Python's BeautifulSoup library. The scraped data included information such as property titles, addresses, prices, and posting dates.

## 🔄 Data Preparation

The raw scraped data underwent cleaning and manipulation using Microsoft Excel. New columns were created to extract information about the number of bedrooms and property types from the title description. The property types in the locality included detached, semi-detached, terraced houses, bungalows, flats, apartments, and others.

## 🎲 Sampling

A simple random sampling method was employed to obtain a representative sample from the population. The sample size of 80 properties was chosen, as the sample mean was close to the population mean, ensuring a better representation of the entire population.

## 📈 Analysis and Visualization

The analysis and visualization aspects of the project include:

1. **📊 Descriptive Statistics**: Calculation of descriptive statistics, such as mean, median, mode, and standard deviation, for the population and sample data.

2. **📈 Visualizations**:
   - 📊 Bar chart displaying the average prices of different property types
     
     ![image](https://github.com/ramgirish10/House_Market_Case_Study/assets/165402421/9dee7124-3705-4343-9e12-22d419008f0a)


   - 📈 Pie chart representing the percentage distribution of property types
     
     ![image](https://github.com/ramgirish10/House_Market_Case_Study/assets/165402421/ff256afd-0372-424c-b40d-baf16f9d90a4)


   - 📊 Scatter plot illustrating the relationship between the number of bedrooms and the number of properties
     
     ![image](https://github.com/ramgirish10/House_Market_Case_Study/assets/165402421/65e87ec7-c350-4243-9264-feccaf3c04e3)


3. **🧪 Hypothesis Testing**: One-sample t-tests were conducted to compare the average property prices in the sample with the average prices in the UK.

4. **📐 Correlation Analysis**: Pearson's correlation coefficients were calculated to assess the relationships between variables.

5. **📈 Regression Analysis**: A multiple linear regression model was built to predict property prices based on the number of bedrooms and property types.

6. **📉 Residual Analysis**: Residual plots were examined to evaluate the assumptions and goodness of fit of the regression model.
   
   ![image](https://github.com/ramgirish10/House_Market_Case_Study/assets/165402421/32726208-9cc8-4777-a1ef-43d64eb75208)


## 🔍 Key Findings

- 📈 The average property prices in the sample population deviated significantly from the UK averages, potentially due to changes over time.
- 🏡 Detached houses were the most expensive property type, while bungalows were the least common.
- 🔑 The number of bedrooms and property type were found to be significant predictors of property prices, with the number of bedrooms having a stronger positive correlation with prices.
- 📊 The regression model, while not highly accurate, provided insights into the relationships between predictor variables and property prices.

## 🚀 Usage

To explore the project further, you can access the Jupyter Notebook file containing the code and analysis. The notebook provides detailed explanations, visualizations, and statistical outputs.
