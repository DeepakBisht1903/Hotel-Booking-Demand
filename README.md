
# Hotel Booking Demand

In recent years, City Hotel and Resort Hotel have seen high cancellation rates. Each hotel is now dealing with a number of issues as a resutl, including fewer revenues and less than ideal hotel room use. Consequently, lowering cancellation rates is both hotels' primary goal in order to increase their efficiency in generating revenue, and for us to offer thorough business advice to address this problem.

The analysis of hotel booking cancellations as well as other factors that have no bearing on their business and yearly revenue generation are the main topics of this resort.

![image.png](https://nolimits-tours.com/wp-content/uploads/2017/06/hotel-ambasador-exterior-002.jpg)

### We will perform Exploratory Data Analysis and answer these questions
<br>

* Where do the guests come from?
* How much do guests pay for a room per night?
* How does the price per night vary over the year?
* Which are the busiest month?
* How long do people stay at the hotels?
* Bookings by market segment
* How many bookings were canceled?
* Which month has the highest number of cancelations?
* Repeated guest effect on cancellations.
* The number of nights spent at hotels.
* Hotel type with more time spent.
* Effects of deposit on cancellations by segments.
* Relationship of lead time with cancellation.
* Monthly customers and cancellations.

## Tools and Libraries Used
We have used Python 3 to its following packages:
- Numpy
- Pandas
- Matplotlib
- Seaborn


## Files
This repository contains two files other than readme file

**Hotel Booking.ipynb:** Jupyter Notebook file contains all the python code, documentation and visualization  
**hotel_bookings.csv:** Our dataset file

**Dataset contains following features:**
1. hotel
2. is_canceled
3. lead_time
4. arrival_date_year
5. arrival_date_month
6. arrival_date_week_number
7. arrival_date_day_of_month
8. stays_in_weekend_nights
9. stays_in_week_nights
10. adults
11. children
12. babies
13. meal
14. country
15. market_segment
16. distribution_channel
17. is_repeated_guest
18. previous_cancellations
19. previous_bookings_not_canceled
20. reserved_room_type
21. assigned_room_type
22. booking_changes
23. deposit_type
24. agent
25. company
26. days_in_waiting_list
27. customer_type
28. adr
29. required_car_parking_spaces
30. total_of_special_requests
31. reservation_status
32. reservation_status_date


## Result

* It appears that a disproportionately high number of bookings are from Portugal, probably because the hotel is located in Portugal itself. The second country is the United Kingdom which is approx. 75% behind.
* From all non-canceled bookings, across all room types and meals, the average prices are: — Resort hotel: 47.56 € per night and person. — City hotel: 59.29 € per night and person.
* The prices in the Resort hotel are much higher during the month of August. There is summer season there in portugal at that time. The price of the city hotel varies less and is most expensive during may and september where there is spring and autumn season respectively.
* Repeated guests do not cancel their reservations. Of course there are some exceptions. Also most of the customers are not repeated guests.
* Most people do not seem to prefer to stay at the hotel for more than 1 week. But it seems normal to stay in resort hotels for up to 12–13 days. Although this changes according to the segments, staying longer than 15 days certainly creates outliers for each segment.
* Customers from Aviation Segment do not seem to be staying at the resort hotels and have a relatively lower day average.
* The weekends and weekdays averages are roughly equal.
* Customers in the Aviation Segment are likely to arrive shortly due to business. Also probably most airports are a bit away from sea and its most likely to be closer to city hotels.
* The cancellation rate for groups is greater than 50%.
* The cancellation rate for offline TA/TOs (Travel Agents/Tour Operators) and online TAs is greater than 33%.
* Direct segments have a lower rate of cancellation.
* When the lead time exceeds about 60, guests frequently cancel their bookings (cancellation rate is higher after this point). Additionally, people want their vacation or work schedules to be calculated across 100 days, or 50% of the data.
* City hotels receive more guests throughout the year. Resort hotels appear to be slightly closer to city hotels in the summer when comparing proportions.
* The City Hotel sees an increase in visitors in the spring and fall when rates are also the greatest. Less people arrive in July and August, when the prices are still lower.
* From June through September, when costs are at their greatest, fewer guests stay at the Resort hotel. The winter season draws the fewest visitors to both hotels.
