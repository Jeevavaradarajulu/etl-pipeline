# ETL Pipline v1
by Jeeva Varadarajulu

## Introduction
This code contains the steps to build an ETL pipline that carries out the following tasks:

-Extracts 400k transaction data from Redshift
-Identifies and removes duplicates
-loads the transformed data to a s3 bucket

## Requirements
The minimum requirements:
 -Python 3+

## Instructions on how to execute the code

1.Clone the repository
````
git clone https://github.com/shaq31415926/waia-academy.git
````

2.Install the Libraries that they need to run 'main.py'
````
pip install -r requirements.txt
````

3.Copy the 'env.example' file to '.env' and fill out the environment

4.Run the 'main.py' script
````
Mac users:
python3 main.py

````
````
Windows users:
python main.py
````