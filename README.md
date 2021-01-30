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

## Summmary

- From this analysis, a much smaller than expected number of DVD reviews were from paid reviewers and the percent of 5 star reviews was only 18%.
- A much more robust cohort of 151,400 reviews were from unpaid reviewers and more than half of them gave 5 star reviews.
- The difference in number of Vine to non-Vine reviewers was jarring. 
    - One of the reasons you would expect more paid reviewers is when you consider the marketing machine behind the studios that release movies on DVD would try to increase sales by using their massive budget to prop up their movies and to move units. A futher examination into how studios allocate their marketing budget to this would be very helpful to help explain this idea. 
    - Going off the point mentioned above, it could also point that popular releases such as Jurassic World or the Avengers franchise, there actually isn't a need for the production companies to spend money to pay reviewers since they already know that because of the popularity of the films, they wouldn't need to pay for positive reviews of their products. 
    - Another reason is that there are a lot of non-movie categories of DVDs such as self-help and exercise videos that also tend to be popular. Since those are generally low budget, there probably isn't much financial gain by spending money to pay for reviewers. 
  
