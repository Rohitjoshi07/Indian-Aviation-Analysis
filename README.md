# IndianAviation Analysis Project

This project is an end-to-end analysis of the Indian aviation industry over the past 5-7 years. Our goal is to gain insights into the growth and trends of the industry by extracting data from the Directorate General of Civil Aviation (DGCA) official website, processing and transforming it, and loading it into a data warehouse for further analysis.


## NOTE: This project is currently in progress.

## Table of Contents
- [Project Description](#project-description)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Project Description
The Indian aviation industry has experienced significant growth over the past decade, and with increasing competition and changing regulations, it is important to analyze the data to gain insights into the industry. Our project covers the entire lifecycle of data analysis, including data extraction, transformation, and loading into a data warehouse. We have used ETL pipelines to automate the process, ensuring accuracy and reliability.

The data extracted from the DGCA official website is processed and transformed into meaningful data using Python and SQL. We have used Airflow for workflow orchestration and Google Cloud for hosting the data warehouse.

Our analysis includes various metrics such as passenger traffic, aircraft movements, and market share of airlines. We have also analyzed the performance of airlines in terms of punctuality, cancellations, and delays.

## Project Structure
- `data_extraction.py`: Python script to extract data from DGCA website
- `data_transformation.py`: Python script to transform data
- `data_load.py`: Python script to load data into data warehouse
- `airflow_dag.py`: Airflow DAG for orchestration of ETL pipelines

## Technologies Used
- Python
- SQL
- Airflow
- Google Cloud

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

