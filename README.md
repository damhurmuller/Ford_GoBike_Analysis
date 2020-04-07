
# Analyzing the Ford GoBike System Data
## by Mário Damhur


## Dataset

This data set includes information about individual trips made in a bike-sharing system covering the greater San Francisco Bay area. Here are the informations about the dataset:

 - Trip Duration (in seconds)
 - Start Time and Date
 - End Time and Date
 - Start Station ID
 - Start Station Name
 - Start Station Latitude
 - Start Station Longitude
 - End Station ID
 - End Station Name
 - End Station Latitude
 - End Station Longitude
 - Bike ID
 - User Type (Subscriber or Customer - "Subscriber" = Member or "Customer" = Casual)
 - Member Year of Birth
 - Member Gender


## Summary of Findings

We will analyzing some features in order to check especially the types of users that have more trips duration.

- What is the gender that most uses this service?
- What are the months with the most movement in the service? And less movement?
- What are the top successful stations?

## Key Insights for Presentation

- People are likely to use bikes for short-distance trips.
- Male gender use with more frequency, but the other and female gender has a higher duration than the male.
- There are a higher movimentation of the trips with higher duration in the months June, July (Highest), August and September. And a lower movimentation of the trips with lower duration in the months November, December, January and Frebruary (Lowest).
- The top 3 stations to start a trip with higher duration in order are:
    - San Francisco Ferry Building (Harry Bridges Plaza)
    - San Francisco Caltrain Station 2 (Townsend St at 4th St)
    - Market St at 10th St.
- Subscriber user type use with more frequency, but the customer user type has a higher duration than the subscribers in all months.

## Files

- **ford-gobike-dataset**: This folder was create to save all the dataset downloaded and combined.
- **exploration_template.ipynb**: The jupyter notebook with wrangling process and the exploration of the data.
- **exploration_template.html**: The HTML version of the jupyter above.
- **output_toggle.tpl**: Provided by Udacity to hide the code in the slide deck.
- **README<span>.md</span>**: This file.
- **slide_deck_template.ipynb**: The jupyter notebook with the explanatory analysis of the final dataset generated in the exploration process.
- **slide_deck_template.html**: The HTML version of the jupyter above.
- **slide_deck_template.slides.html**: The slide deck apresentation.

## Python Libraries Used
- **numpy**
- **pandas**
- **matplotlib**
- **requests**
- **seaborn**
- **io**
- **zipfile**
- **os**
