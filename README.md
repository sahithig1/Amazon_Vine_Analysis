# Amazon_Vine_Analysis
Overview of the analysis:
In this project I have picked a data set from amazon reviews regarding video games and used Pyspark to perform the ETL process by extracting the data, transforming the data and connecting to the database that was generated for me through the AWS webserver. With the reviews my goal is to try and determine if there is favorable review bias from the Vine members of our data set.
Results:
How many Vine reviews and non-Vine reviews were there?
There were a total of of 4,291 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset.
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
In the data set their was a total of 15,711 5-star reviews
15,663 of the 5-star reviews were non-vine
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
38.2% of the five_star reviews were vine
38.9% of the five_star reviews were non-vine

Summary:
-After I had come up with my analysis there does not appear to be any sort of positivity bias because the percentages shown above are very similar at 38%. To conclude the analysis the vine program does not show any bias.![Screen Shot 2022-11-30 at 11 59 01 PM](https://user-images.githubusercontent.com/55648656/204977199-efd52303-021e-4dc4-bce1-9790f43568e9.png)
![Screen Shot 2022-11-30 at 11 59 55 PM](https://user-images.githubusercontent.com/55648656/204977316-9c9036cf-12e1-4ac7-809b-0b851345054d.png)
