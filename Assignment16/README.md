# PySpark Employee Data Processing Assignment

## Project Overview

This project demonstrates employee data processing using PySpark. Employee data is read from a CSV file and analyzed using Spark DataFrame operations.

## Objectives

* Read employee data from a CSV file
* Sort employees by salary in descending order
* Calculate department-wise total salary
* Find the top 3 highest-paid employees
* Save the processed results into an output file

## Dataset

File Name: employees.csv

Columns:

* id
* name
* department
* salary

## Technologies Used

* Python
* PySpark
* Apache Spark
* Jupyter Notebook
* Docker
* GitHub

## Project Files

* assigment16.ipynb
* employees.csv
* output.txt
* Dockerfile
* README.md
* requirements.txt

## Execution Steps

### Run Jupyter Notebook

Open and execute all cells in assigment16.ipynb.

### Build Docker Image

docker build -t employee-app .

### Run Docker Container

docker run --rm employee-app

## Output Generated

* Employees Sorted by Salary (Descending)
* Department-wise Total Salary
* Top 3 Highest Paid Employees

## Author

Pokhar Mal

B.Tech CSE (AI)

Swami Keshvanand Institute of Technology, Jaipur
