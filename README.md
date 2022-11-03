# Dublin Bus Weather Project
## Plan of action 

## Task: Analyse Dublin Bus traffic and usage patterns with reference to the Dublin weather

1: Write code to download the Dublin Bus journey time data from https://data.gov.ie/organization/dublin-city-council?tags=Transport+and+Infrastructure
2: Decompress the zip file into the zips/Bus folder  - done
3: Loop through the gz files and decompress them in to the Data/Bus folder -done
4: Download the weather stations csv file - done
5: Get the information for the Dublin weather stations -done
6: Loop through this data and download the hourly weather data into Data/Weather folder - done
7: Read the Bus data in to a Pandas dataframe - done
8: Find the min and max Date and time from the bus data - done
9: Read the weather data and load in the hourly weather data between the min and max dates - done
10: Do exploratory data analysis on the Bus Data
    a: Describe the numeric data - done
    b: Describe the categoric data - done
    c: Create Histograms for all of the data 
    d: Find missing data - decide how to handle it :( 
    e: Tidy up the data
    f: Recreate the Bus data on a hourly schedule
11: Do exploratory data analysis on the Weather Data
    a: Describe the numeric data
    b: Describe the categoric data
    c: Create histograms for all of the data
    d: Find any missing data - decide how to handle it
    e: Tidy up the data
    f: Create some extra categoric variables - based on Met Eirean defintions? 
        i: Categorse rainfall amounts into 'None', 'Drizzle', 'Soft Rain', 'Rain', 'Cats and Dogs', 'Down Pour' 
        ii: General conditions - 'Raining', 'Cloudy', 'Sunny' 
12: Attempt to geo locate the weather stations with the Bus Routes using KMeans
13: Add the geolocated weather to the Bus data
14: Examine correlations and other relationships

### Predctions 
Try to predict Bus journey times 
Try to predict Delay value 
Try to predict Congestion value


#Deadline - 11-11-2022