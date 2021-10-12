# Amazon_Vine_Analysis

## Overview of the analysis: 
Analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results: 
* How many Vine reviews and non-Vine reviews were there?
    ### 94 Vine reviews and 40,471 non-vine reviews in the new dataset.
<img width="449" alt="Screen Shot 2021-10-11 at 9 27 39 PM" src="https://user-images.githubusercontent.com/85847344/136891479-1b17b5d1-4504-4864-a693-6b98c0f22f3d.png">

* How many Vine reviews were 5 stars? 
    ### 15,711
 <img width="1280" alt="Screen Shot 2021-10-11 at 9 16 10 PM" src="https://user-images.githubusercontent.com/85847344/136890482-c52fa092-86fe-468e-bcc1-2b6510ad8ea4.png">
 
* How many non-Vine reviews were 5 stars?
    ### 15,663
 <img width="501" alt="Screen Shot 2021-10-11 at 9 19 43 PM" src="https://user-images.githubusercontent.com/85847344/136890786-f0c1a673-95be-408f-b092-15efeb90e325.png">

* What percentage of Vine reviews were 5 stars? 
    ### 38.2% 

* What percentage of non-Vine reviews were 5 stars?
    ### 38.9% 
<img width="1148" alt="Screen Shot 2021-10-11 at 9 21 30 PM" src="https://user-images.githubusercontent.com/85847344/136890936-1f847a6c-1417-4388-93be-9fb35891bd50.png">

## Summary: 
It seems that there is not any sort of positivity bias due to the percentages of the Vine vs non-Vine reviews being so similar (38%). This therefor shows that the vine program does not seem to show any bias.
