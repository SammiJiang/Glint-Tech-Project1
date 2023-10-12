# Glint Tech - Project 1: Implementing SCD Type 2 in Data Pipelines

## Project Overview

This repository contains the implementation of Slowly Changing Dimension (SCD) Type 2 in data pipelines, showcasing the transformation of raw data to refined datasets. The process ensures data integrity and versioning to track historical changes. The project is deployed on Databricks, utilizing its collaborative environment and powerful computing resources.

### Key Components:

1. **Raw Data Handling**
    - `Split_raw_data`: A utility to manage large datasets that exceed the upload limits of Databricks HDFS. It processes and splits data efficiently for easy uploads.

2. **Data Transformation Workflow**
    - The transformation process is well-documented, containing intermediate results and analytical insights. It provides transparency and traceability in data processing steps.

3. **SCD Type 2 Implementation**
    - `Project 1`: The core pipeline that implements SCD Type 2, ensuring that historical data is preserved while accommodating new and updated records.

- ** both project 1 and project work flow data could be viewed in HTML** 

## Getting Started

### Prerequisites

- Databricks account and appropriate access permissions.
- Knowledge in PySpark and SQL for understanding and modifying the pipeline as per specific use cases.

### Installation & Usage

1. **Clone the Repository**
    - Clone this repository to have a local copy on your system.

2. **Upload Data to Databricks**
    - Use the `Split_raw_data` utility to handle large datasets, split them if required, and upload them to Databricks HDFS.

3. **Execute the Pipeline**
    - Open `Project 1` on Databricks, configure the cluster and run the notebook to execute the data transformation pipeline.

## Data Flow

### Raw to Bronze

- The raw data, primarily in JSON format, is initially processed to clean and transform it into a structured format.
- It is then stored in the Bronze layer, ensuring that raw data is untouched and available for reference.

### Bronze to Silver

- SCD Type 2 is implemented at this stage. Historical data changes are tracked, and the dataset is versioned.
- Data refinement, including filtering, cleaning, and validation, is performed to ensure data quality and consistency.

## Documentation

- **Project Workflow Document**: A comprehensive guide containing visualizations, intermediary results, and explanations of each step in the data transformation process.




