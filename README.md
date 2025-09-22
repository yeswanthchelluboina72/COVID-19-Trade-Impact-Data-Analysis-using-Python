# **COVID-19 Trade Impact Data Analysis Using Python**

This project analyzes the impact of the COVID-19 pandemic on global trade using Python, Pandas, and Matplotlib. The analysis focuses on trade trends, import/export comparisons, and identifying the most affected commodities, transport modes, and countries between the years 2019 and 2021\.

## **Project Goal**

The primary objective is to create a series of data visualizations to provide insights into how global trade was affected during the early years of the pandemic. The visualizations are designed to be clear, professional, and easy to interpret, suitable for a data analysis dashboard.

## **Data**

The analysis uses a CSV dataset named dataset-covid19-trade-impact.csv, which is expected to be located in a specific folder within your Google Drive. The script is configured to access this file at /content/drive/My Drive/COVID-19-Trade-Impact-Data-Analysis/.

## **Key Features**

The Python script performs the following analyses and generates the corresponding visualizations:

* **Overall Trade Trend:** A line plot showing the cumulative trade value over time for the years 2019, 2020, and 2021\.  
* **Exports vs. Imports:** A line plot comparing cumulative export and import values over the same three-year period.  
* **Top Commodities Growth:** Horizontal bar charts identifying the top 10 commodities with the highest percentage growth in trade value for the 2019-2020 and 2020-2021 periods.  
* **Transport Mode Analysis:** Horizontal bar charts showing the change in trade value by different transport modes for the two periods.  
* **Country Growth:** Horizontal bar charts highlighting the top 10 countries with the highest percentage growth in trade value for the two periods.

## **How to Run**

This project is designed to be run in a Google Colab environment due to its direct integration with Google Drive.

1. **Prepare your environment:**  
   * Upload the dataset-covid19-trade-impact.csv file to your Google Drive. It must be placed in a folder named COVID-19-Trade-Impact-Data-Analysis directly under My Drive.  
2. **Run the script:**  
   * Open a new Google Colab notebook.  
   * Copy and paste the entire Python script into a code cell.  
   * Run the cell. Google Colab will prompt you to grant access to your Google Drive.  
3. **View the output:**  
   * The script will display all the generated plots directly in the notebook output.  
   * Additionally, it will create a new folder named images within the COVID-19-Trade-Impact-Data-Analysis directory in your Google Drive.  
   * Each of the five visualizations will be saved as a PNG file in this new images folder, overwriting any previous versions with the same name.

## **Libraries Used**

* **pandas:** For data loading, manipulation, and analysis.  
* **matplotlib:** For creating the data visualizations.  
* **google.colab:** For mounting Google Drive to access the dataset.

## **Output**

![Alt text](https://github.com/yeswanthchelluboina72/COVID-19-Trade-Impact-Data-Analysis-using-Python/blob/main/images/overall_trade_trend.png?raw=true)
![Alt text](https://github.com/yeswanthchelluboina72/COVID-19-Trade-Impact-Data-Analysis-using-Python/blob/main/images/exports_vs_imports.png?raw=true)
![Alt text](https://github.com/yeswanthchelluboina72/COVID-19-Trade-Impact-Data-Analysis-using-Python/blob/main/images/top_commodities_affected.png?raw=true)
![Alt text](https://github.com/yeswanthchelluboina72/COVID-19-Trade-Impact-Data-Analysis-using-Python/blob/main/images/transport_mode_analysis.png?raw=true)
![Alt text](https://github.com/yeswanthchelluboina72/COVID-19-Trade-Impact-Data-Analysis-using-Python/blob/main/images/country_analysis.png?raw=true)
