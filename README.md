# Object Detection Analysis on Polish Roads

## Project Description
This project conducts a comprehensive data analysis using Python, Spark, Excel, and SQL to explore and analyze a dataset related to object detection on Polish roads. The main objective of the project is to gain a better understanding of the distributions of detected objects and the relationships between different variables through data analysis and visualization techniques.

## Project Structure
**1. Data Loading**
  - **CSV File:** The data file is loaded using the google.colab.files.upload() function in Google Colab.

**2. Initial Data Exploration**
- **DataFrame Review:** The first few rows of the DataFrame are examined.
- **Data Description:** Basic information and a statistical description of the variables are presented.
  
**3. Data Cleaning and Preprocessing**
- **Data Cleaning:** Rows with null values and duplicates are removed.
- **Value Verification:** Unique values in the object_type column are checked.
- **Type Conversion:** Columns are converted to appropriate data types.

**4. Exploratory Data Analysis (EDA)**

- **Visualization:** Seaborn is used to visualize the distribution of detected object types.
- **Correlations:** A heatmap is generated to visualize correlations between numerical variables.

**5. Data Storage and Querying with SQL**

- **Database:** The resulting DataFrame is saved into an SQLite database.
- **SQL Queries:** Queries are executed to group and count the detected object types.

**6. Preprocessing with Spark**
- **Distributed Processing:** The pandas DataFrame is converted to a Spark DataFrame to handle large volumes of data.

**7. Visualization and Presentation of Results**
- **Charts:** Charts are generated to show the distribution of object types and correlations.
- **Export:** The results are exported to an Excel file.

## Requirements
1. Python 3.7+
2. Jupyter Notebook (optional if using Google Colab)
3. Python Libraries: pandas, numpy, matplotlib, seaborn, sqlite3, pyspark
4. Google Colab (optional)
5. CSV file of the dataset
   
## Usage Instructions
**1. Data Loading:**
- Run the notebook in Google Colab.
- Upload the CSV file when prompted.

**2. Data Exploration:**
- Review the first few rows and basic information of the DataFrame.
- Ensure the data is clean and in the correct format.

**3. Exploratory Analysis:**
- Run the visualization cells to analyze distributions and correlations.

**4. Querying and Storage:**
- Use SQL queries to delve deeper into the data and extract relevant information.

**5. Results Export:**
- Export the final results to an Excel file for presentation or further analysis.
