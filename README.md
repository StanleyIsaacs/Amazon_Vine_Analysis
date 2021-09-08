# Amazon Vine Analysis

## Overview:
We have been tasked with analyzing the Amazon Vine program to determine if it is biased towards favorable reviews from Vine members. The goal is to use PySpark to perform ETL process to extract and transform data and using AWS RDS, load the data to look at different metrics.

## Resources:
Google Colab Notebook, PostgreSQL, pgAdmin, AWS, Amazon review datasets and Videogame review datasets.

## Results:
* Number of Vine and non-Vine reviews
<img width="424" alt="Vine" src="https://user-images.githubusercontent.com/82114481/132559932-3cdafe02-debb-44ed-a1a0-0ae6c693985d.png">
<img width="442" alt="NonVine" src="https://user-images.githubusercontent.com/82114481/132559976-de6d526f-46fb-4353-b60f-ed17056b199e.png">

* Number of 5 star Vine and non-Vine reviews
<img width="704" alt="vine5" src="https://user-images.githubusercontent.com/82114481/132560332-d7d50755-c7b3-4a38-8b60-ae7e03b8f309.png">
<img width="756" alt="nonVine5" src="https://user-images.githubusercontent.com/82114481/132560346-dc0501e6-4312-4bf3-88e5-f11d474e452e.png">

* Percentage of Vine and non-Vine 5 star reviews
<img width="731" alt="VinePercentage" src="https://user-images.githubusercontent.com/82114481/132560643-c5f67cb0-292f-4ca0-908b-8235fa40fa0e.png">
<img width="766" alt="NonVinePercentage" src="https://user-images.githubusercontent.com/82114481/132560664-4d74a075-804e-49b3-856b-4d2ec0c29a7a.png">

## Summery:
When it comes to 5 star reviews, there is a difference between Vine and non-Vine reviews. Vine reviews had a five star review rate of 51% while non-Vine reviews had a five star precentage of 39%. We can conclude that yes, there is a positivity bias for reviews coming from the Vine program. We could look at the statistical distribution of star ratings between the two sets for further information.
