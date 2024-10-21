# Marrasi Real Estate Market Analysis

## Table of Contents
* [Dataset Definition](#dataset-definition)
* [Analysis Process](#analysis-process)
* [Key Findings](#key-findings)
* [Technologies Used](#technologies-used)
* [How to Use](#how-to-use)
* [Conclusions](#conclusions)
* [Future Work](#future-work)

## Dataset Definition
This dataset contains real estate transaction data from the Marrasi development in Egypt, including:
* **Development Name**: Name of the property development
* **Type**: Property type (Townhouse, Villa, Apartment)
* **Model**: Design model of the property
* **Community/Village**: Location within Marrasi
* **Sales Rooms**: Number of rooms
* **Plot Area**: Area in square meters
* **Sellable Area**: Usable area in square meters
* **Total Area**: Total property area in square meters
* **Sold Units Prices**: Transaction price
* **Sold Month/Year**: Transaction date
* **Location**: City and country information

The dataset underwent thorough cleaning and anonymization to protect customer privacy while maintaining analytical value.

## Analysis Process
1. **Initial Data Preparation (Power Query)**:
   * Removed sensitive customer information
   * Extracted temporal components from dates
   * Standardized formats
   * Initial data structuring

2. **Advanced Data Cleaning (Python)**:
   * Handled missing values in critical metrics
   * Applied median imputation for numerical fields
   * Removed redundant columns
   * Standardized property categories

3. **Data Analysis**:
   * Property type distribution analysis
   * Price trend analysis
   * Area correlation studies
   * Sales performance metrics
   * Community preference analysis

## Key Findings
* **Portfolio Performance**:
  * Total Sales Value: EGP 4.1B+
  * Total Units Sold: 949 properties
  * Average Unit Price: EGP 4.32M
  * Price Range: EGP 1.41M - EGP 28.1M

* **Property Specifications**:
  * Average Plot Area: 436 m²
  * Average Sellable Area: 263 m²

## Technologies Used
* **Power Query**: Initial data cleaning and privacy protection
* **Python**: Advanced analysis and visualization
* **Libraries**:
  * Pandas: Data manipulation
  * NumPy: Numerical operations
  * Matplotlib: Visualization
  * Seaborn: Statistical visualization
* **Jupyter Notebook**: Development environment

## How to Use
1. Clone the repository
2. Install required Python packages:
```bash
pip install pandas numpy matplotlib seaborn
```
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```
4. Open the analysis notebook and run the cells

## Conclusions
The analysis provides valuable insights into the Marrasi real estate market:
* Property type preferences and their evolution
* Price-to-area relationships
* Community development patterns
* Market segment performance

These insights can guide development planning, pricing strategies, and investment decisions.

## Future Work
1. **AI Integration**:
   * Develop machine learning models for price prediction
   * Implement AI-powered recommendation systems for property matching
   * Create automated valuation models (AVM)

2. **Predictive Analytics**:
   * Time series forecasting for property values
   * Demand prediction by property type
   * Market trend analysis

3. **Decision Support System**:
   * AI-powered dashboard for real-time decision making
   * Risk assessment models
   * Investment opportunity scoring

4. **Advanced Analytics**:
   * Sentiment analysis of customer preferences
   * Competitive market analysis
   * Geographic information system (GIS) integration

---
*Note: This analysis was conducted on actual transaction data with strict privacy measures in place.*
