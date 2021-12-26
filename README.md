# Amazon_Vine_Analysis

## Overview
For this challenge we are analyzing Amazon reviews of baby products written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We are taking a dataset of baby product reviews and using Pyspark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Finally we will use pyspark to determine if there is any bias towards favorable reviews from Vine members in the dataset.

## Results

### Paid Dataframe and results
<img width="663" alt="Screen Shot 2021-12-26 at 9 15 57 AM" src="https://user-images.githubusercontent.com/89098766/147410843-e3920ddb-3a74-4756-873a-15a683f579ac.png">

<img width="554" alt="Screen Shot 2021-12-26 at 9 11 27 AM" src="https://user-images.githubusercontent.com/89098766/147410855-73711798-6bde-4c6a-bd1e-3067823687c7.png">

### Unpaid Dataframe and results
<img width="651" alt="Screen Shot 2021-12-26 at 9 16 08 AM" src="https://user-images.githubusercontent.com/89098766/147410873-f3f428d1-bffe-4af3-bb69-efb89397f2a3.png">

<img width="539" alt="Screen Shot 2021-12-26 at 9 12 04 AM" src="https://user-images.githubusercontent.com/89098766/147410878-06f71d16-9e07-405c-831c-33d4496d514c.png">
