Real-Time-weather-Data-Etl-Pipeline-Automation-with-Apache-Airflow
🌐 Project Overview: I developed a weather data pipeline using Apache Airflow to monitor, extract, and analyze real-time weather data from Houston, Texas. This automated pipeline connects to an external API, retrieves daily weather metrics, processes and transforms them, and stores the data for further analysis.

🔍 Explorations: My main goal was to streamline data extraction and transformation using Airflow’s powerful scheduling capabilities. I aimed to convert raw weather data (retrieved in Kelvin) into more interpretable metrics, like Fahrenheit, and generate insights on weather conditions.

🚀 Key Steps:

API Readiness Check: Used an HttpSensor to verify API availability before initiating data extraction.
Data Extraction: Leveraged SimpleHttpOperator to fetch weather data from OpenWeatherMap’s API in JSON format.
Data Transformation & Loading: Transformed weather data using PythonOperator, calculated Fahrenheit temperatures, and extracted relevant information (e.g., temperature, wind speed, pressure) before loading it to an AWS S3 bucket.
🔧 Modules Used:

Apache Airflow for orchestration and scheduling.
Pandas for data transformation and storage.
AWS S3 to store the final CSVs for analysis.
📊 Results and Analysis: This project provided an end-to-end solution for automated weather data ingestion. It enabled real-time monitoring and structured storage of weather insights, with minimal manual intervention.

💡 What I Learned: This experience enhanced my skills in data engineering workflows, integrating APIs, and automating data pipelines. It was a hands-on journey into Airflow's capabilities and gave me valuable insights into managing data extraction and transformation processes with AWS S3.
