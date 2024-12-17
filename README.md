# Environmental Sensor Data Analysis

## Description of the Project

### Introduction
In an era where environmental changes are increasingly unpredictable, this project aims to construct a data pipeline to process environmental sensor data, enabling advanced analytics and predictive modeling. By analyzing this data, we can identify trends and patterns that contribute to more informed decision-making in environmental policy and management.

### Problem Statement
Analyzing environmental data to provide actionable insights into changing environmental conditions and predicting future weather based on trained machine learning models.

### Motivation
The project focuses on addressing the urgent need to adapt to and mitigate the effects of environmental changes using the growing availability of environmental data and advancements in cloud computing and machine learning.

### Objectives
The primary goal is to demonstrate a robust data handling and analysis framework capable of:
- Efficiently extracting and storing vast amounts of sensor data.
- Transforming raw data for advanced analysis and machine learning.
- Providing both basic analytics and complex predictive insights through visualizations and model deployment.

### Data Engineering Goals
- **Efficient Data Ingestion and Storage**: Extract data from sources like GitHub and APIs, storing it in Azure Data Lake.
- **Automated Data Workflow Management**: Utilize Apache Airflow to orchestrate data processing, ensuring data integrity and timeliness.
- **Robust Data Processing and Transformation**: Clean, normalize, and engineer features for analysis.
- **Scalable Data Analytics and Machine Learning Deployment**: Analyze processed data for insights and predict future trends using machine learning models.

## Technologies and Methodology
- **Google Colab**: Used for data ingestion, transformation, and ETL processes.
- **Apache Airflow**: Manages workflow, specifically for triggering API calls for weather forecasting.
- **Azure Data Lake**: Storage of transformed data, with tools like Azure Synapse Analytics and Databricks for machine learning models.
- **Databricks**: Analyzes datasets and develops machine learning models.
- **Visual Crossing Weather API**: Tests the machine learning model and predicts future weather.

## Data Source
- **Primary Data Source**: Visual Crossing Weather API and GitHub [DATA](https://github.com/sanket101-git/Local-Climatological-Data/raw/main/Sensor_Data.zip)(historical weather data from 2018 to 2024).
- **GitHub Data Link**: [Sensor Data](https://github.com/sanket101-git/Local-Climatological-Data/raw/main/Sensor_Data.zip)

## Workflow and Architecture
The workflow consists of four main stages:
1. **Extract**: Fetch data from Visual Crossing Weather API and GitHub.
2. **Load**: Ingest data into Google Colab, transform it, and load it into Azure Data Lake.
3. **Transform**: Apply data cleaning, feature engineering, and normalization processes.
4. **Serve**: Utilize processed data to generate analytics and drive machine learning models.

## Project Visualization
Graphs and visualizations were created to illustrate each component of the lifecycle and to demonstrate how data pipelines were organized from source systems to destination systems.

## Project Retrospective Part I
### Key Insights
- Intended pipeline vs. actual implementation differed slightly in technology choices and data handling processes.
- Knowledge of Azure cloud services like Synapse Analytics and Databricks would have improved project planning and execution.
- Significant hurdles included handling datasets with many null values and managing API limitations.

### Lessons Learned
- Prior knowledge of Azure services would have streamlined the project.
- A streaming solution might have been more effective for real-time data analysis.

## Project Retrospective Part II
### Future Improvements
- Gaining hands-on experience with cloud platforms and advanced machine learning algorithms would be beneficial.
- Key takeaways included understanding the importance of cloud platforms and ETL tools in managing data efficiently.

### Additional Resources
- Requesting additional funding for specialized team members and technical tools (like DOMO and Alteryx) to improve ETL processes and data management.

## Conclusion
The project demonstrated that our machine learning model’s weather predictions align with predictions from reliable weather forecasting platforms, showcasing the potential of our data analysis and machine learning approach.
