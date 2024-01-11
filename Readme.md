# Airlines Classification using PySpark ML

## Spark ML

- Dealing with large datasets and diverse data sources can be challenging when applying traditional machine learning techniques.
- Spark, a distributed processing engine utilizing the MapReduce framework, addresses these challenges in big data processing.

---

## Objective

This project focuses on Classification and Clustering in Spark MLlib using Airlines Data.

- Implementation includes Decision tree classifier, Random forest classifier, and K-Means clustering algorithms.

---

## Business Overview of Airlines Industry

- [OpenFlights](https://openflights.org/)
- [IBM Developer Exchange - Airline Data](https://developer.ibm.com/exchanges/data/all/airline/)
- [BTS - Popular Air Carrier Statistics](https://www.bts.dot.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics)

---

## S3 Link for Dataset

- `s3://airlines123/airline/data.zip`

---

## Tech Stack
- **Language:** `Python`
- **Package:** `Pyspark`
- **Services:** `Spark`

---

## Code Overview

- File Names: 
  - `DecisionTree.ipynb`
  - `RandomForest.ipynb`
  - `K_means.ipynb`

- Datasets: 
  - `data.zip`
  - `Social_Network_Ads.csv`

---

## Steps to Run

### Command Prompt

1. Execute using Python script:
   ```
   <spark_path> spark-submit <file_path>
   ```
   - `<spark_path>`: Path to Spark installation
   - `<file_path>`: Path to the script file

   Example:
   ```
   <C:\Users\admin\Desktop\spark\bin>spark-submit C:\Users\admin\Desktop\sparkml\DecisionTree.py>
   ```

### IPython

1. Modular Code
   - Create a virtual environment
   - Install requirements: `pip install -r requirements.txt`
   - Run code: `python DecisionTree.py`
   - Check output for all visualizations

   
 ---

