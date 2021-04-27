# Project Overview
  This is the final project for SI507 at University of Michigan for Winter2021. It is a project related to python, SQL, web crawling, and user interactive program. According to the users’ input of any type of food or name of restaurants or location of restaurants, this program will search results along with different features, such as ratings, reviews, address…etc. The results will be represented in the following form:
                  1.Command line prompt
                  2.YouTube videos
                  3.Figures (scatter charts, bar charts, and radar charts)
                  4.Google map (static/dynamic map)

In addition, simultaneously, users are allowed to construct and expand their own SQL database, which allows them to either find or compare their desired restaurants and food at their ease.

# Required API
  This program require four kinds of API keys
   1. Yelp fusion API
      1. Sign up at shorturl.at/jHM24  
      2. Create new App, obtain personal private API Key and autenticate API calls with the API key
   2. YouTube API
      1. sing up at shorturl.at/oxBOS
      2. Create new Credentials for API keys and Enable APIs and services for YouTube Data API v3
   3. Google static map API and Google map API
      1. sing up at shorturl.at/oxBOS
      2. Enabling Billing payment (In free trial for three months)
      3. Create new Credentials for API keys and Enable APIs and services for Maps Static API and 
         Directions API

# High Level Description
  There are two following ways to interact with this program:
  1. Instant search on Yelp for specific type of food or restaurant
      1. Users are required to type in the FoodName/RestaurantName (optional) and Location(required).
      2. Users would see the search results (name/phone/address/rating/totalreview/pricerange/...) in command line prompt/scattering plot.
      3. Users could decide to whether to open the relative videos on YouTube, mark the relative location of each restaurant
         on static google map and navigate themselves to chosen restaurant on google map.
  2. Search the Restaurants existing in the database based on Reviews/Rating/Price
      1. Users are required enter the state of USA in abbreviation.
      2. Users are required to decide the filtering condition, such as rating/reivew/price/numbers/order...etc
      3. Users could see the result in command line prompt, bar plots and radar charts.

# Optional DB Browser for SQLite
  It is additional tools for user to check the data in SQL database.
    1. Downlink:shorturl.at/xLRU1
    2. Documentation link for tutoial:shorturl.at/dlqtQ




