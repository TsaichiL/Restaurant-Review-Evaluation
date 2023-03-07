# Restaurant-Review-Evaluation
The main objective of this project is to evaluate the performance of a restaurant by analyzing customer reviews and sentiments. Such analysis can provide insights into what customers like and dislike about the restaurant with the most commonly used positive and negative words in the reviews, which can help the restaurant improve its services, enhance its overall customer experience, and obtain new customers. 

Here we focus on a specific restaurant "J KARAOKE BAR", which is one of the 119 restaurants with an overall 5-star rating in Las Vegas, and its online Yelp reviews to showcase how data analysis techniques can be used to evaluate businesses and improve customer satisfaction.

## Dataset
The dataset used in this project was sourced from a reliable online repository available at "https://github.com/zarkem/emiba-ai/blob/main/las_vegas_restaurants_2017.csv?raw=true". The dataset comprised a total of 2730 rows and 12 columns, consisting of various attributes such as business_id, name, neighborhood, city, state, overall_rating, review_count, categories, review_id, review_rating, date, and text. Specifically, the dataset was limited to only overall 5-star rating reviews of restaurants located in Las Vegas during the year 2017.

#### Sample of the first reviews:
![image](https://user-images.githubusercontent.com/123428884/223582315-56e30eca-ff90-432c-b565-0330dbac1112.png)


## Result
### Summary of the Reviews
People like most about J KARAOKE BAR are
- Delicious food and drinks
- Reasonable price
- Roomy private rooms

People complain most about J KARAOKE BAR are
- Limited song selection
- Karaoke devices (microphone, sound system, etc.)
- Reservation process

### Sentiment information for restaurant: "J KARAOKE BAR"
- Mean sentiment is 11.657142857142857<br />
- Mean positive sentiment is 12.257425742574258<br />
- Mean negative sentiment is -3.5<br />
- Number of positive sentiment is 101<br />
- Number of negative sentiment is 4<br />

Type | Number/Score
--- | ---
count | 105.000000
mean | 11.657143
std | 8.214467
min | -5.000000
25% | 6.000000
50% | 11.000000
75% | 16.000000
max | 38.000000

### Wordcloud of the Reviews
#### Positive words:
- [Room, Place, Private, Area] → Able to have private & spacious room”
- [Chicken, Food, Wing, Delicious, Soju] → Food and drinks are delicious and with much variety
- [Celebration, Friend, Group, Sister, Party] → Suitable for family and group of friends to celebrate
- [English, Korean, Selection, Music] → Have a wide range of music selection
#### Negative words:
- [Wait, List, Minute, Hour, Long, Notification] →Have to wait for a long time without notification
- [Service, Call, Employee, Slow, Tell, Bartenders] →Services are reacting too slow
- [Sound, Mess, Condition, System] → Poor stereo equipment and messy/smelly room<br />
<br />

![image](https://user-images.githubusercontent.com/123428884/223581118-8d29a324-f635-4659-9302-3f72b27ba51f.png)<br />

## Advice to J KARAOKE BAR
Fix and improve Sound System and Equipments <br />
Update the music library constantly

Redistribute the bar room<br />
Optimize reservation and notification system<br />
Express lines for pre-booked rooms<br />
Coupons and discounts for long wait times<br />
Free snacks and extra service in waiting area

Hire enough staff<br />
Train service staff<br />
Set standards for service and cleanliness
