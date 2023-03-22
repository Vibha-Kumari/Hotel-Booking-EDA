# Hotel-Booking-EDA
HOTEL BOOKING ANALYSIS

Contributor :   Vibha Kumari
                                              
Define Your Problem Statement?

We are provided with a hotel bookings dataset.
Our main objective is to perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.


Data Summary:
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

hotel: Name of hotel (City or Resort)
is canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
lead-time: time (in days) between booking transaction and actual arrival.
arrival_date_year: Year of arrival
arrival_date_month: month of arrival
arrival_date_week_number: week number of arrival date.
arrival_date_day_of_month: Day of month of arrival date
stays_in_weekend_nights: No. of weekend nights spent in a hotel
stays_in_week_nights: No. of weeknights spent in a hotel
adults: No. of adults in single booking record.
children: No. of children in single booking record.
babies: No. of babies in single booking record.
meal: Type of meal chosen
country: Country of origin of customers (as mentioned by them)
market_segment: What segment via booking was made and for what purpose.
distribution_channel: Via which medium booking was made.
is_repeated_guest: Whether the customer has made any booking before (0 for No and 1 for Yes)
previous_cancellations: No. of previous canceled bookings.
previous_bookings_not_canceled: No. of previous non-canceled bookings.
reserved_room_type: Room type reserved by a customer.
assigned_room_type: Room type assigned to the customer.
booking_changes: No. of booking changes done by customers
deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
agent: Id of agent for booking
company: Id of the company making a booking
days_in_waiting_list: No. of days on waiting list.
customer_type: Type of customer(Transient, Group, etc.)
adr: Average Daily rate.
required_car_parking_spaces: No. of car parking asked in booking
total_of_special_requests: total no. of special request.
reservation_status: Whether a customer has checked out or canceled, or not showed
reservation_status_date: Date of making reservation status. 

#Total number of rows in data: 119390
 #Total number of columns: 32
 
 
 
 
Exploratory Data Analysis:

Exploratory Data Analysis is a process of examining or understanding the data and extracting insights or main characteristics of the data.

 The primary motive of EDA is to
•	Examine the data distribution
•	Handling missing values of the dataset(a most common issue with every dataset)
•	Handling the outliers
•	Removing duplicate data
•	Encoding the categorical variables
•	Normalizing and Scaling.


Purpose of  using certain graphs.

1. pie chart 
It represents data visually as a fractional part of a whole, which can be an effective communication tool for the even uninformed audience.

It enables the audience to see a data comparison at a glance to make an immediate analysis or to understand information quickly.


2. Line chart:
The line chart is used to show trends over time or categories.
Here, the category appears horizontally(X-axis) and value vertically(Y-axis).

3. Column charts
It is used to compare values across multiple categories.
Here, the category appears horizontally(X-axis) and values vertically(Y-axis).
In the column charts, you can also show information about parts of a whole across different categories, and you can show this in absolute value as well as relative terms. Here comes the concept of a stacked column chart and 100% stacked column charts.

4. Bar charts
As you’re quite familiar with column charts, you will find that working with bar charts is very synonymous.
The only difference between them is that in a bar chart, values are represented on the X-axis and categories on the Y-axis.
We typically use a bar graph to show values across categories when the duration or category text is long.
Stacked bar charts are used to compare parts of a whole(relative and absolute) and compare change over categories or time.

5. Histogram
It is used to graphing the frequency over a distribution. It is a very useful graph in the analytics world and can infer many useful insights from the data.
Visually, all the bars are touching each other with no space between them.

6. Box plot
It is also known as Box and whiskers plot.
Within the box itself, there is 25% of data above the median and 25% of data below the median, so 50% of the data is within the box.
By using this plot, we can easily spot outliers and the distribution of the plot.

CONCLUSION

1•	august is the most booked month.

2•	Jan is the least booked month.

3•	2016 is the most booked year ,

4•	in which both  city hotel and resort hotel  contribution is high in comparison of 2015 and 2017.

5•	city hotel has highest  booking cancelled

6•	highest booking has been done through online TA.

7•	We can see that the percent of City hotel is more compared to Resort hotel.

8•	Resort Hotel tend to be on the expensive side and most people will just stick with city hotel.

9•	August is the most occupied (busiest) month with 11.62% bookings and

10•	January is the most unoccupied month with 5.0% bookings.

11•	2016 is the most booked year with 47.50% bookings and

12•	2015is the least booked year with 18.42% bookings.

13•	highest distribution is made by TA/TO.

14•	prt is the top travelling country and city hotel is most preferred by them .

15•	resort hotel is more  preferred  hotel by only citizen of gbr which is second highest country.

16•	Agent no. 9 has made most no. of bookings.

17•	Most demanded room type is A, but better adr rooms are of type H,

18•	G and C also. Hotels should increase the no. of room types A and H to maximise revenue.

19•	Most preferred meal type is BB (Bed and breakfast).

20•	Avg adr of Resort hotel is slightly lower than that of City hotel. Hence, City hotel seems to be making slightly more revenue.
21•	City hotel has slightly higher median lead time. 

22•	Also median lead time is significantly higher in each case,

23•	this means customers generally plan their hotel visits way to early.

24•	City hotel has significantly longer waited time; hence City Hotel is much busier than Resort Hotel.

25•	Both hotels have very small percentage that customer will repeat, but Resort hotel has slightly higher repeat % than City Hotel.

26•	TA/TO is mostly used for planning Hotel visits ahead of time.

27•	But for sudden visits other mediums are most preferred.

28•	GDS channel brings higher revenue generating deals for City hotel, in contrast to that most bookings come via TA/TO. City Hotel can work to increase outreach on GDS channels to get more higher revenue generating deals.

29•	Resort Hotel need to increase outreach on GDS channel to increase revenue.

30•	TA/TO has highest booking cancellation %.

          Therefore, a booking via TA/TO is 30% likely to get cancelled.
31•	We see that most of the bookings that are cancelled have waiting period of less 150 days but also most of bookings that are not cancelled also have waiting period less than 150 days. Hence this shows that waiting period has no effect on cancellation of bookings.

32•	lead time has no effect on cancellation of bookings, as both curves of cancelation and not cancelation are similar for lead time too.

33•	Now we will check whether not getting allotted the same room type as demanded is the cause of cancellation of bookings

34•	We see that most of the bookings that are cancelled have waiting period of less 150 days but also most of bookings that are not cancelled also have waiting period less than 150 days. Hence this shows that waiting period has no effect on cancellation of bookings.

35•	We see that not getting same room as demanded is not the case of cancellation of rooms. A significant percentage of bookings are not cancelled even after getting different room as demanded.

36•	 number of guests comes in month of August.
37•	Avg adr rises from beginning of year up to middle of year and reaches peak at August and then lowers to the end of year. But hotels do make some good deals with high adr at end of year also.

38•	Most guest are from Portugal .

Challenges:
(1) There was a lot of duplicate data.
(2) Data was present in wrong datatype format.
(3) Choosing appropriate visualization techniques to use was difficult.
(4) A lot of null values were there in the dataset.





