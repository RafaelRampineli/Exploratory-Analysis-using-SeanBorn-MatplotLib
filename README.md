# Exploratory-Analysis-using-SeanBorn-MatplotLib
This project was created as mini-project-2 in ninth module of course Python Fundamentals for Data Analysis(Data Science Academy).

The purpose of this project was to explore and understand how data is distributed.
Exploratory analysis is the starting point for creating and constructing machine learning algorithms.

Here is the Link to find Dataset: https://www.kaggle.com/orgesleka/used-cars-database

Summary:
Over 370000 used cars scraped with Scrapy from Ebay-Kleinanzeigen. The content of the data is in german, so one has to translate it first if one can not speak german. 
Those fields are included: autos.csv:

dateCrawled : when this ad was first crawled, all field-values are taken from this date
name : "name" of the car
seller : private or dealer
offerType
price : the price on the ad to sell the car
abtest
vehicleType
yearOfRegistration : at which year the car was first registered
gearbox
powerPS : power of the car in PS
model
kilometer : how many kilometers the car has driven
monthOfRegistration : at which month the car was first registered
fuelType
brand
notRepairedDamage : if the car has a damage which is not repaired yet
dateCreated : the date for which the ad at ebay was created
nrOfPictures : number of pictures in the ad (unfortunately this field contains everywhere a 0 and is thus useless (bug in crawler!) )
postalCode
lastSeenOnline : when the crawler saw this ad last online
The fields lastSeen and dateCreated could be used to estimate how long a car will be at least online before it is sold.
