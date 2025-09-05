# Project-2

HOTEL BOOKING EDA

Objective We are provided with a hotel bookings dataset.

Our main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

Dataset We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

hotel : Hotel (Resort Hotel or City Hotel)

is_canceled : Value indicating if the booking was canceled (1) or not (0)

lead_time : Number of days that elapsed between the entering date of the booking into the PMS and the arrival date

arrival_date_year : Year of arrival date

arrival_date_month : Month of arrival date

arrival_date_week_number : Week number of year for arrival date

arrival_date_day_of_month : Day of arrival date

stays_in_weekend_nights : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

stays_in_week_nights : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

adults : Number of adults

children : Number of children

babies : Number of babies

meal : Type of meal booked. Categories are presented in standard hospitality meal packages:

country : Country of origin.`

market_segment : Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

distribution_channel : Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

is_repeated_guest : Value indicating if the booking name was from a repeated guest (1) or not (0)

previous_cancellations : Number of previous bookings that were cancelled by the customer prior to the current booking

previous_bookings_not_canceled : Number of previous bookings not cancelled by the customer prior to the current booking

reserved_room_type : Code of room type reserved. Code is presented instead of designation for anonymity reasons.

assigned_room_type : Code for the type of room assigned to the booking.

booking_changes : Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or

cancellation deposit_type : Indication on if the customer made a deposit to guarantee the booking.

agent : ID of the travel agency that made the booking

company : ID of the company/entity that made the booking or responsible for paying the booking.

days_in_waiting_list : Number of days the booking was in the waiting list before it was confirmed to the customer

customer_type : Type of booking, assuming one of four categories

adr : Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

required_car_parking_spaces : Number of car parking spaces required by the customer

total_of_special_requests : Number of special requests made by the customer (e.g. twin bed or high floor)

reservation_status : Reservation last status, assuming one of three categories a). Canceled – booking was canceled by the customer b). Check-Out – customer has

checked in but already departed c). No-Show – customer did not check-in and did inform the hotel of the reason

reservation_status_date : Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the

booking canceled or when did the customer checked-out of the hotel Total number of rows in data: 119390 Total number of columns: 32

Know your data

Dataset Information

Duplicate Values

Missing Values/Null Values

Understanding Your Variables

Check Unique Values for each variable.

Data wrangling

count that in which year of which month most number of customers arrived at hotel.

Customer type, Room type, room_comparision, Deposit_type, Is_canceled checked.

How many customer have changed their booking.

remove duplicates values

finding uniques values for each variables

Find hotel ratio Adding a two new column of total staying days,total people stays

Remove outliers by box plot. Did All th manipulation

What main questions was arising :-

Which types of customers mostly make bookings?

Which room type is in most demand and which room type generatesthe highest adr?

Which distribution channel brings betterrevenue-generatingg deals for hotels?

Which significant distribution channel has the highest cancellation percentage?

What is the trend of bookings within a month?

Which Hotel has Highest booking ratio(comparision)?

What is preferred stay length in hotel if we compare with Customer type?

In which year most booking has happened for bothe type hotels?

From which country most of the guests are coming ?

In which month most of the booking happened?

Which market segment has booked and canceled the booking?

What type of Customer has highest booking as Couples, Single, Group?

Which meal type is the most preffered meal of customers?

Finding out corelation between Different variables?

which has highet ADR?

Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

Bar Plot

Histogram

Scatter Plot

Pie Chart

Line Plot

Heatmap

Box Plot

Pair plot

We plot different graph (univariate and bivariate ) to make find out the last conclusion:-

Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall adr of City hotel is slightly higher than Resort hotel.

Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred.

Both hotels have significantly higher booking cancellation rates and very few guests less than 3 % return for another booking in City hotel. 5% guests return for stay in Resort hotel.

Most of the guests came from european countries, with most of guests coming from Portugal.

Guests use different channels for making bookings out of which most preferred way is TA/TO.

Almost 30% of bookings via TA/TO are cancelled.

July- August are the most busier and profitable months for both of hotels.

Couples are the most common guests for hotels, hence hotels can plan services according to couples needs to increase revenue.

For customers, generally the longer stays (more than 15 days) can result in better deals in terms of low adr.

Higher lead time has higher chance of cancellation. Also, history of previous cancellations increases chances of cancellation.

Challenges

There was a lot of duplicate data.

Data was present in wrong datatype format.

Choosing appropriate visualization techniques to use was difficult.

A lot of null values were there in the dataset.
