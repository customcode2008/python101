# python101

## Interview Question: ETL with Python

### Objective:
Test the applicant's knowledge of ETL (Extract, Transform, Load) concepts along with Python programming skills.

### Task:

#### 0. Clone this repository and create a feature branch to complete the following tasks. Make regular commits and push your changes back to the remote repository. 

#### 1. Extract:
- Load a JSON file from the following URL: [data.nasa.gov/resource/y77d-th95.json](https://data.nasa.gov/resource/y77d-th95.json) 
- Data Source GitHub repository: [Awesome JSON Datasets](https://github.com/jdorfman/awesome-json-datasets)

#### 2. Transform:
- Remove entries with missing values for mass and year columns. 
- Calculate the average mass of the landed meteorites per century.

#### 3. Load:
- Post the transformed data to an open test API endpoint. You can use the [Webhook Tester](https://webhook.site) to create a new endpoint for testing purposes.

### Additional Question:
- Use a list comprehension to filter out records where `"recclass": "Unknown"`.
