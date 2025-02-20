# Temperature-trend-analysis
Temperature Trend Analysis is a project that processes historical temperature data (2005-2014) to identify and visualize record high and low temperatures. The script loads the dataset, cleans the data, determines record-breaking temperatures, and generates a visualization of temperature trends over the years.
Temperature Records Analysis



## 📜 Project Overview

Temperature Trend Analysis is a project that processes historical temperature data (2005-2014) to identify and visualize record high and low temperatures. The script loads the dataset, cleans the data, determines record-breaking temperatures, and generates a visualization of temperature trends over the years.


## 📂 Dataset

### Data Format

The dataset  CSV file containing the following columns:

- **ID** - Weather station identifier  
- **Date** - The date of the recorded temperature (YYYY-MM-DD)  
- **Element** - Type of temperature record (TMAX or TMIN)  
- **Data_Value** - The recorded temperature value (in degrees Celsius)  
- **Year** - The year of the recorded temperature  
- **Month** - The month of the recorded temperature  
- **Day** - The day of the recorded temperature  


## 🔍 Things Done

### 1. Load and Preprocess Data
- Read the temperature dataset using pandas.  
- Convert temperature values to a usable format (tenths of degrees Celsius to degrees).  
- Remove leap year records (February 29) to ensure consistent yearly comparisons.  

### 2. Identify Record Highs and Lows (2005-2014)
- Group data from 2005-2014 by (Month, Day).  
- Determine the maximum (**TMAX**) and minimum (**TMIN**) temperature for each day across these years.  
  

### 3. Data Visualization Using Matplotlib
- Plot the record high and low temperatures from 2005-2014.  
- Fill the area between record highs and lows with a shaded region for better visualization.  
