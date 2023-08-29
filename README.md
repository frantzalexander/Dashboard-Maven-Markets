# Dashboard-Maven-Markets
Dashboard Created from the Maven Udemy Course: Microsoft Power BI for Business Intelligence

## Project Overview
A dashboard of a sample company used to learn Business Intelligence with Power BI.

## Results
![image](https://github.com/frantzalexander/Dashboard-Maven-Markets/assets/128331579/fb941175-7591-4d26-83eb-62602ae67b4e)

## Process
```mermaid
flowchart TD
start(((START)))
import[Import: Data and Lookup Tables]
check[Check Data Formatting]
clean[Clean Data]
calendar[Create Rolling Calendar]
data_model[Create Data Model]
schema[Create Snowflake Schema]
measures[Create Calculated Measures]
visuals[Create Visualizations]
finish(((END)))
start --> import
import --> check
check --> clean
clean --> calendar
calendar --> data_model
data_model --> schema
schema --> measures
measures --> visuals
visuals --> finish
