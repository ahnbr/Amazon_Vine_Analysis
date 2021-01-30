# Amazon_Vine_Analysis

## Overview of the Analysis

- In this project, we looked into analyzing data from a specific category of items - in thise instance, DVDs - sold on Amazon. From this data we wanted to analyze buyer reviews of DVDs based on whether or not they were paid or not to write a review. The tools we used were PySpark to extract, process and load (ETL) the data. As part of this process we had to connect to the AWS RDS and load the data that we transformed to pgAdmin.

## Results

**How many Vine reviews and non-Vine reviews were there?

- After filling reviews to helpful reviews, there were only 49 Vine reviews yet 151,400 non-Vine reviews.

**How many Vine reviews were 5 stars? How many non-vine reviews were 5 stars?

- Of the 49 Vine reviews, only 9 were 5 stars. Of the 151,400 non-Vine reviews, 78,061 were 5 stars. 

**What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- The percent of Vine reviews that were 5 stars was 18.3%. The percent of non-Vine reviews that were 5 stars was 51.6%

<img width="831" alt="Screen Shot 2021-01-30 at 4 46 46 PM" src="https://user-images.githubusercontent.com/68168883/106368867-08edc880-631b-11eb-82ec-eb7f811aaab5.png">


