#Comprehensive DPLYR Practice


```r
install.packages("nycflights13")
```

## `nycflights13` Excercises

Using the `nycflights13` package and the `flights` dataset use the `dplyr` package to answer these questions.  Some answers are given in square brackets for you to check your answers.

1.	How many flights in Sept were late departing flights? [7815]
2.	How many flights in Sept were late departing flights that originated at JFK airport? [2649]
3.	How many flights in Sept were late departing flights with an origin of JFK airport and had an destination of anywhere except MIA? [2572]
4.	Which carrier had the most flights in this data set?  [UA with 58665]
5.	Which destination had the most flights in this data set? [ORD with 17283]
6.	Which destination had the most flights with departure delays of greater than 60 minutes in this data set? [ORD with 1480]
7.	What was the longest arrival delay in this dataset? [1272]
8.	Which carrier in September had the most late departing flights? [UA with 1559]
9.	Create a variable called total.annoyance which arrival delay plus the departure delay for each flight.
10.	Which carrier with more than 10 flights in September had greatest % late departing flights?

## `storms`  Excercises 

Open the `storms` data from the `dplyr` package.  Use ?storms to understand the data.  Then answer:

1. How many observations have both wind speeds of greater than 20 knots and air pressure of more 1010 millibars? 
2. How many observations have the storm name of Ana, Ernesto, Ophelia or Isidore? 
3. What is the average wind speed for each category of storm? 
4. For category 4 and 5 storms (combined) what is the average pressure? 
5. Create a variable called strength which is pressure divided by wind speed.  What is the maximum strength in this data set? 
6. Which storm has the most observations?
7. Which category 5 storm(s) have the greatest average wind speed? 

## `starwars` Excercises

Please use the `starwars` dataset from the `dplyr` package to answer the following questions:

1. Which species has the most individuals included in this data set?
2. Which species has the tallest individuals on average?
3. What is the tallest individual for each species?
4. Calculate the BMI for each individual and determine which individual has the highest BMI.  Use the formula `bmi = mass/((height/100)^2)` to calculate bmi.
5. Which homeworld has the most individuals included in this data set?
6. Which homeworld has the tallest individuals on average?
7. What is the tallest individual for each eye color?
