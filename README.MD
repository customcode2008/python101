# python101

## Interview Question: ETL with Python

### Objective:
Test the applicant's knowledge of ETL (Extract, Transform, Load) concepts along with Python programming skills.

### Task:
Create a python application that can perform the ETL steps detailed below. Make sure to add documentation that instructs the user how to use the application. You can assume the user is comfortable in the terminal/command line. 

Create a new public repository for your assignment submission.

You are welcome to use ChatGPT's free version during the interview, but we will adjust our questions to make sure you understand the code provided by ChatGPT. 

❔ **Discussion Points**

    -  Which library would be suitable for the ETL process below?
    -  Can you comment on the quality of the data Transformation?

The application should perform the following: 

#### 1. Extract:
- Load a JSON file from the following URL: [https://raw.githubusercontent.com/customcode2008/python101/refs/heads/main/y77d-th95.json](https://raw.githubusercontent.com/customcode2008/python101/refs/heads/main/y77d-th95.json) *(source: NASA)*

#### 2. Transform:
- Calculate the average mass of the landed meteorites per century.

#### 3. Load:
- Using an http Post request, send the transformed data to the following endpoint: "https://webhook-test.com/c4319e2456190a0aa5cbbf326f959a77"

### Additional Question if time permits:
- Use a list comprehension to filter out records where `"recclass": "Unknown"`.
