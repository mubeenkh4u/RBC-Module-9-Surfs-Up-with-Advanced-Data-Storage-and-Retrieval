# RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval

## Overview:

While visiting hawaii I developed an interest in starting my own surfing shop "Surf n' Shake" on the beach of Oahu in Hawaii. I later had an opportunity to meet an investor who was willing to help me start up my business though he had one concern about the business which was based off weather conditions of the island. After looking at the weather and precipitation data provided by W. Avy (our friendly investor). I started to perform an analysis using advanced data storage and retrieval techniques.

## Purpose:

The purpose of this project is to analyse the Weather and Precipitation data for the island of Oahu in Hawaii. We used the following for our analysis:
* `SQLite` file (for the Database stored locally).
* `SQLAlchemy` (for writing SQL queries and ORM mapping of database into tables in Python to reflect our Database).
* `Numpy` (for unraveling the data retrieved by the SQL queries and converting it into readable lists).
* `Pandas` (for converting the lists in numpy to Dataframes).
* `Datetime` (for entering our desired dates for SQL queries wrapped in SQLAlchemy).

## Files Used:

* [hawaii.sqlite](https://github.com/mubeenkh4u/RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval/blob/main/hawaii.sqlite)

## Results:

After pulling the weather and precipitation data from our database for a one year time frame. We focused our efforts on the weather activity from August 23, 2016 to August 23, 2017. Based of our queries we can see that we had a total count of 2021 entries for the given timeframe.

<img src="https://github.com/mubeenkh4u/RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval/blob/main/Resources/prev_year.png">

<img src="https://github.com/mubeenkh4u/RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval/blob/main/Resources/monthly_temp_data.png">

<img src="https://github.com/mubeenkh4u/RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval/blob/main/Resources/Prev_Year_Precipitation.png">

Finally we ended up looking at the June and Decemeber dataset as shown below:

<img src="https://github.com/mubeenkh4u/RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval/blob/main/Resources/June_Temps.png">
<img src="https://github.com/mubeenkh4u/RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval/blob/main/Resources/December_Temps.png">

<img src="https://github.com/mubeenkh4u/RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval/blob/main/Resources/June_Temps_Describe.png">
<img src="https://github.com/mubeenkh4u/RBC-Module-9-Surfs-Up-with-Advanced-Data-Storage-and-Retrieval/blob/main/Resources/December_Temps_Describe.png">

We notice that both of them have very similar values with differences mostly in the total number of observation `counts` (1700 vs 1517) and `minimum` (64 vs 56) temperature values.

## Summary:

Based on our analysis we can see that regardless of the season "Surf n' Shake" would flourish as the average temperatures of hawaii are fairly equal all year round. If we wish to increase our accurary we could easily run queries on each out of the year and convert the data into a histogram to be presented to Mr. W. Avy. The positive findings made in our analysis would definitely help the investors in making the much needed investments in the shop and generate great revenue.

* We could run our queries on the Precipitation Dataset provided in the database to further enhance our findings.
* Using the observation dataset provided we could look at which one of the islands is better fit for our business by looking at both the temperature and precipitation differences (or for a possiblity to expand our business into a chain).

