# US Immigration 

#### **Goal:** To support U.S Customs & Border Protection Department to make better decisions on Immigration Policies



## Overview

The purpose of this data engineering  project is to develop an overall solution. I took the approach in building the Data Lake on the data on immigration to the United States provided by Udacity.

## Business Scenario

A business consulting firm specialized in data warehouse services through assisting the enterprises with navigating their data needs and creating strategic operational solutions that deliver tangible business results is contacted by U.S Customs & Border Protection Department. Specifically, they want help with the modernization of department's data warehousing infrastructure by improving performance and ease of use for end users, enhancing functionality, decreasing total cost of ownership while making it possible for real-time decision making. In total, the department is asking for a full suite of services includes helping department with data profiling, data standardization, data acquisition, data transformation and integration.

The U.S. Customs and Border Protection needs help to see what is hidden behind the data flood. The consulting firm aim to model and create a brand new analytics solution on top of the state-of-the-art technolgies available to enable department to unleash insights from data then making better decisions on immigration policies for those who came and will be coming in near future to the US.

## The Architecture

The whole solution is cloud based on top of **Amazon Web Services (AWS)**. First, all the datasets were preprocessed with **Apache Spark** and stored in a staging area in **AWS S3 bucket**. Then, it is loaded into a **Amazon Redshift** cluster using an **Apache Airflow** pipeline that transfers and checks the quality of the data to finally provide the department a Data Lake for their convenient analysis.

#### The Data Model ####

![Data Model](https://raw.githubusercontent.com/amar5075kumar/Data-Lake-US_ImmigrationData/7fabde8855db65bf4b88f4e6920d98735d9fcd0d/images/star-schema.PNG)



## Structure of the Project

Following the Udacity guide for this project, the structure is as shown below:

 - Step 1: Scope the Project and Gather Data
 - Step 2: Explore and Assess the Data
 - Step 3: Define the Data Model
 - Step 4: Run ETL to Model the Data
 - Step 5: Complete Project Write Up


For the full project and code, visit the [GitHub Repository](https://github.com/amar5075kumar/Data-Lake-US_ImmigrationData/).
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
