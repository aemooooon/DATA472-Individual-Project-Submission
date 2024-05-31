# DATA472 Individual Project Submission - Hua Wang

> [!INFORMATION]
> - **Student Name**: Hua Wang
> - **Student ID**: 29375234
> - **Lecturer**: Giulio Valentino Dalla Riva
> - **Date**: 2024-05-31

> [!NOTE]
> As a volunteer of the Central Collect Team, I have contributed to this course by providing both Individual Project and Central Collect Team work following:

## Individual Project Contribution

1. **Flask WEB API Example**
    - [GitHub Repository](https://github.com/Data472-Individual-Project-Pipeline/flask-web-api-example)
    - **Description**: This project is a simple example of a Flask web API that runs as an Operation System level service and returns an HTTP JSON response. The initial thought was to inspire other classmates because some of them were struggling with how to run up a Web API and how to run a service on an AWS EC2 instance.

2. **DATA472 Individual Project Data Collection Example**
    - [GitHub Repository](https://github.com/Data472-Individual-Project-Pipeline/DATA472-Individual-Project-Example)
    - [Online Live Demo](http://3.25.85.38:4000/graphql)
    - **Description**: This project is a Hua Wang individual project example for the DATA472 course. The initial thought was to implement the first individual project for the Central Collection Team to get started with collecting work. I have collected the Canterbury area Air Quality Index data from the ECAN website and generated a GraphiQl API to provide the data to the Central Collection Team used to visualise.
  
3. **Data472 Individual Project Data Visualisation example**
    - [GitHub Repository](https://github.com/aemooooon/Data472-individual-project-visualisation-example/tree/main)
    - [Online Live Demo](http://visual.hua.nz/)
    - **Description**: This project serves as a data visualization for the Central Collection Team pre-research. The initial thought was to plot the specific insights of the data from the Canterbury area Air Quality Index data from the ECAN website.

## Central Collect Team Working

1. **Central Data Collection Service**
    - [GitHub Repository](https://github.com/Data472-Individual-Project-Pipeline/Data-collection-service)
    - [Online Live Demo](http://af.hua.nz/)
    - **Description**: The Data Collection Service is a part of the Micro-service that the DATA472 Central Collection Team used to collect other students' individual project data, based on Apache Airflow, designed to automate the collection and processing of student data scheduled as CRON Jobs . The project includes multiple DAGs (Directed Acyclic Graphs) and processors that collect data from different Web APIs and store it in a PostgreSQL database run on AWS RDS.

2. **Central Data (Web API) Provider Service**
    - [GitHub Repository](https://github.com/Data472-Individual-Project-Pipeline/Web-API-Service)
    - [Online Live Demo](http://api.hua.nz/api-docs/)
    - **Description**: The Web API Service is built using Node.js and Express to provide API endpoints for visualizing data collected by Data472 student individual projects. The project includes multiple routes that correspond to different datasets and uses Swagger for API documentation.
