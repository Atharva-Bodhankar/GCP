**End-to-End Data Pipeline in Google Cloud Platform**


This project demonstrates the creation of an end-to-end data pipeline in Google Cloud Platform (GCP). The pipeline involves uploading a CSV file to Cloud Storage, performing transformations using Dataflow, and loading the transformed data into BigQuery. Finally, we validate the data by executing queries in BigQuery.

![image](https://github.com/Atharva-Bodhankar/GCP/assets/92572655/ff141843-245b-4377-91ee-30bd5b3fc488)


**Overview**: 
The goal of this project is to showcase the seamless integration of various GCP services in building a robust data pipeline. It covers steps from data ingestion to transformation, and ultimately, data validation.

**Project Setup**

Cloud Services Configuration - Use Cloud Shell to configure essential services like Cloud Storage, Virtual Environment, Apache Beam, and BigQuery.

Enable Cloud Components - Execute the necessary commands to enable all the required cloud components for the project**.

Usage**

Data Ingestion - Upload the source CSV file to Google Cloud Storage bucket.

Data Transformation - Execute the provided Python script to transform the data using Apache Beam/Dataflow.


Data Loading - Load the transformed data into BigQuery.


**Components**:

The project leverages the following GCP components:

Google Cloud Storage
Apache Beam (Dataflow)
BigQuery
Sample Code
Find the Python script for data transformation in the data_transformation/ directory. The script utilizes Apache Beam to perform the necessary transformations.

Validation
To validate the data loading, execute SQL queries in BigQuery to ensure that the transformed data is accurately loaded.

**Additional Resources**

For further information and in-depth tutorials on GCP components, refer to the following resources:

[Google Cloud Documentation](https://cloud.google.com/docs)

[Google Cloud Blog](https://cloud.google.com/blog)

[Google Cloud YouTube Channel](https://www.youtube.com/user/googlecloudplatform)
