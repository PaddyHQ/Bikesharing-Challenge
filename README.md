# Bikesharing
[Link To Dashboard](https://public.tableau.com/app/profile/patrick.holmquist/viz/BikesharingChallenge_16425228705570/CustomersvsSubscribers?publish=yes "link to dashboard")
## Analysis Overview

In this analysis, we are looking at an exemplar of a successful bike-sharing model in NYC in order to create a business proposal for investors with the goal of opening a similar bike-sharing business in Des Moines, Iowa.

### Purpose

Show the viability of a bike-sharing business and answer questions about:

* What we can expect in terms of rides - get enough bikes
* Who uses the service?
  * Look at what types of people are using Citibike in order to determine the sorts of potential customers we might expect
    * Demographic research is primarily focused on gender and age
    * Are users subscribers or infrequent users?
* Where are they using it and what for?
  * Analyze most common pickup and drop off locations
  * Analyze trip duration and peak days and hours

### Significance

Bike-sharing programs have been shown in America's large cities to be effective businesses that:

* Help decongest traffic by taking cars off the road
* Reduce carbon emissions within cities
* Promote fitness and wellbeing of users

## Results

### Customer Base

![Fig. 1](Resources/Customers%20vs%20Subscribers.png)

Figure 1 shows that Citibike users are primarily subscribers. This suggests that Citibike users favor using the bikes for regular activities, such as commuting to and from work.

### Usage and Maintenance
![Fig. 2](Resources/User%20Trips%20by%20Gender%20by%20Weekday.png)

Figure 2 shows that the bike sharing service is mostly used by males during the weekdays, and a little less so on the weekends.

![Fig. 3](Resources/Trips%20by%20Weekday%20per%20Hour.png)

Figure 3 shows that the bike sharing service is not only used mostly during weekdays, but also shows peak hours are during 6 A.M. to 10 A.M. and 5 P.M. to 8 P.M., also known as the "rush hour" period. Figure 3 also shows moderate bike share usage on the weekends, mostly during the afternoon. This would be the time most people are going out to shops, visiting the city's park, seeing sights, and more.

![Fig. 4](Resources/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

Figure 4 shows that the bulk of bike sharing usage is from males during the work week. Female usage is lower, but follows the same trends with most usage occurring during rush hour on weekdays.

![Fig. 5](Resources/Checkout%20Times%20for%20Users.png)

Figure 5 shows that for all users, short rides of about 5-8 minutes are most common. Medium rides of 10-20 minutes are the next most common, and long rides of 25 minutes or less are significantly less common. This suggests that bike share usage is best implemented in places where trips from place to place will be short.

![Fig. 6](Resources/Checkout%20Times%20by%20Gender.png)

Figure 6 shows that the bulk of bike sharing usage is from males during the work week. The frequency of female usage is lower, but follows the same trends with most preferring short rides of about 8 minutes or less. There are still many, but significantly less, rides in the medium 10-20 minute range.

![Fig. 7](Resources/Top%20Ending%20Locations.png)

Figure 7 shows that the bulk of the most popular bike drop off locations are in and around the most dense areas of New York city, including NOHO, SOHO, Manhattan, and West Village. This supports the notion that bikes are most often used for short trips around very dense urban areas.

## Summary

Provide a high-level summary of the results and

### Future Analysis

Create visualizations for:

* Checkout duration by age with new trip duration format
* Trip duration by user type
* User type by gender
* add lat/long for drop off locations for the most used bikes (show example)

## Recommendation for future data gathering

* Gather data on other bike sharing companies in other cities.
  * New York city data may correlate but almost certainly will not directly translate to a mid-western, less dense (in terms of population) city.
* Gather data on startup costs
  * Cost of bikes
  * App development and further market research
* Look into early Citibike data to learn how long they took to become widespread and profitable.
* Gather data on cost of bike repairs and revenue per customer to determine business sustainability.
* Add a short market research questions about why they're going to use the bike and attitudes.
  * When they download the app and make an account, attach a question about what they might most use the bike share for
    * i.e.- whether it's for commuting, recreation, sightseeing, etc.
* Additionally, the app could ask a simple question post drop off like "How was your trip?" every so often.
  * The question could be accompanied by a happy/sad/neutral face with options to add more detail if a customer wishes. That way we could gather more data without being too intrusive on customer experience.
