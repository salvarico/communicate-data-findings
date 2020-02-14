# (Dataset Exploration Title)
## by (your name here)


## Dataset

### What is the structure of your dataset?

The Ford GoBike System Data contains all observations of bike sharing rides in the greater San Francisco Bay Area. Looking at the data, it seems to make all sense. There doesn't seem to be something strange or some sample wrongly registered. The data contains all rides from years 2018 and 2019.

The raw data contains the following columns:
- Trip Duration (seconds)
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
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Bike Share for all Trip

And the tidy data has these additional variables:
- Start Time Month
- Start Time Day of the Week
- Start Time Hour
- End Time Hour
- Distance(km)


## Summary of Findings

- No transformation was needed and all variables seemed to make sense.

- The distribution of rides by month is not very uneven but it's clearly less frequent during the winter months since it's cold and makes sense that people use it less often. The months were we have more frequent rides are the most warm months like July.

- On average each ride takes about 13.3 minutes and the median is of 9 minutes.

- On average in each ride bikers travel an average distance of 1.92 kilometers and a median of 1.41 kilometers. Almost all rides traveled less than 4 kms.

- Most of the users are subscribers. It makes sense since we saw that many rides could be from people commuting to work or school and these users will probably save money if they subscribe. In general makes sense that people that use the service frequently will prefer subscribing.

- There are huge differences in the patterns of use between customers and subscribers. The number of rides vary a lot depending on the type of user either analyzed by weekday or month.

- On average customers travel a larger distance for each ride. A possible explaination is that many customers might be tourists that are using it for recreational purposes and they have time to ride the bike in longer distances whereas subscribers more frequently just want to get to their work or school.

## Key Insights for Presentation

- There is a big difference between the rides during the workweek and the rides during the weekend. This makes sense since during the weekends less people have to go to work or study as they do during the workweek. Something else to notice is that the frequency of rides during Monday and Friday is less than during Tuesday-Thursday. My guess is that this has to do with the fact that people try to take their vacation days in these days in order to connect those days with the weekend.

- There is clearly a high usage during the peak hours when people go to school or work or they commute from it to home.

- The distributions of rides per month conditioned by type or user are quite different. The most noticeable thing is that December is the month of less frequent rides among subscribers but the month of most frequent rides among customers. This might possibly be explained by the profile of the users. Maybe customers are tourist or people that are just enjoying the holidays but don't usually ride the bikes and on the other side subscribers could just be on holidays and not at school or work and maybe that's why they use it less often.

- Again the distributions of rides by weekday are very different between customers and subscribers. This seems to reinforce the hypothesis that subscribers are mainly people that use the service for work or school. During the workweek subscribers use the service much more often than during the weekends whereas in the case of customers they use it more or less equal and even a bit more during Friday-Sunday. This could be due to the fact that there are more turists during weekends.

- The distributions by month and weekday vary a lot depending of the user type. This conclusion reinforces even more the hypothesis that many customers are tourists (either locals in holidays or people from other city/country). We can see that because the distribution of bike rides thorugh the weekdays varies a lot depending on the month in the case of customers. You can see that in the months of holidays (July and December) there is a lot of usage during the workweek which suggests that people that probably don't use the service often are using it a lot more in those months.

- Customers tend to use the service a lot during peak hours in the workweek and in the hours around the afternoon during the weekends. A possible explaination is that during the peak hours of the weekwork we just need that some of the employees and students that don't use the service regularly take the rides to have this pattern. During the weekends it can simply be explained by recreational users that will use the service mainly during the hours where people typically enjoy their free time. In the case of subscribers by far their main use is during the peak hours of the weekwork which is when people that regularly use the service will probably need it for going to their jobs or school.