# E-Commerce-Car-Sales-Analysis: An Exploratory Data Analysis Project.
This project showcases an Exploratory Data Analysis (EDA) of e-commerce car sales data scraped from an online e-commerce platform. The analysis highlights key patterns, relationships, and insights into car features, prices and distributions. The dataset was preprocessed, transformed, and visualized using Python to ensure accuracy and user readability.

### Workflow and Key Features:

1. **Data Extraction and cleaning:**
   * Scraped data containing features such as Name, Model, Year, Description, Price, and Type (Foreign or Local used).
   * Removed duplicates, handled mssing values, and formatted delimeters for better readability.
   * Transformed the Price feature from an object to integers for numerical analysis.

2. **Feature Engineering:**
   * Created a Classification feature categorizing cars into:
   * Luxury,High-end,Premium, Mid-range,Budget, Economy.
   * Converted categorical variables to numerical data for analysis.

3. **Key Distributions Analyzed**:
   * Name, Model, Year, Type, and Class distributions.

4. **Data Visualization**:
   * Utilized Plotly for interactive viaulizations.
   * Created a Correlation Matrix to analyze relationships between numerical features and the target variable(Price)
  
5. **Insights Derived**:
   * Patterns in car models and manifacturing years.
   * Type distribution (Foreign vs Local used)
   * Correlation analysis revealing realtionships between car features and price.

### Tools and Libraries Used:
* Language: Python
* Libraries: Pandas, Numpy, Matplotlib, Seaborn, Plotly, Scikit-learn

### Objective:
To analyze and derive actionable insights from e-commerce car sales dats, helping stakeholders understand car rice classifications, distributions, and realtionships among features.

#### Acknowledgement:
Special thanks to Jiji.ng for providing accessible and reliable car sales data, enabling the seamless scraping and analysis presented in this project.
