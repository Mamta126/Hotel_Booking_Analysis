# Hotel-Booking-Analysis
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions!
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
![Hotel-Booking](https://user-images.githubusercontent.com/89864373/132099143-4d15689a-568b-4cb9-adad-cdf9a9ef9ff7.jpg)


# Dataset Specs
* Count of rows= 119390
* Count of columns= 32

# Programming Language
* Python 

# IDE
* Google Colaboratory

# Nomenclature
Naming our dataframe is very crutial for any data analysis project as you have to call the dataframe time and again for every set of operation which are to be performed for the in-depth analysis.

In this case, our copy of the dataframe will be called 'df' , simple and easy to recall.

# Data Variables Glossary

* **hotel**
Two hotels are given:
Resort Hotel
City Hotel
* **is_canceled**
1: Canceled
0: Not canceled
* **cancelation**
0 as not_canceled
1 as canceled
* **df_not_canceled_guests**
dataframe with just not_canceled bookings
* **lead_time**
gap between booking and arrival
* **arrival_date_year**
arrival year
* **arrival_date_month**
arrival month
* **arrival_date_week_number**
arrival week
* **arrival_date_day_of_month**
arrival date
* **stays_in_weekend_nights**
count of nights the guests booked the hotel during Sat-Sun
* **stays_in_week_nights**
count of nights the guests booked the hotel during Mon-Fri
* **total_stay_nights**
duration of stay including weekend nights and week nights stay
* **adults**
count of adults
* **children**
count of children
* **babies**
count of babies
* **meal**
meal type (no meal package; BB; HB; FB)
* **country**
country of guests
* **df_country_guests_top10**
top10 countries with most visitors
* **market_segment**
TA: Travel agents
TO: Tour operators
* **distribution_channel**
* **is_repeated_guest**
1: Yes
0: No
* **previous_cancellations**
count of previous bookings that were cancelled by the customer before final booking
* **previous_bookings_not_canceled**
count of no canceled bookings
* **reserved_room_type**
booked room category
* **assigned_room_type**
assigned room category
* **booking_changes**
count of changes made by the customer before final booking
* **deposit_type**
type of deposit made by the customer
* **agent**
travel agent id
* **company**
booking company id
* **days_in_waiting_list**
count of days the booking was in the waiting list before it was confirmed
* **customer_type**
Transient
Contract
Group
Transient-party
* **adr**
average daily rate for the booking
* **price**
total price spent by a guest entity
* **required_car_parking_spaces**
count of car parking spaces alloted by the customer
* **total_of_special_requests**
count of special requests made by the customer
* **reservation_status**
status of reservation
* **reservation_status_date**
date corresponding to status of reservation

# INTRODUCTION & OBJECTIVE OF THE CHASE
Vacations, business stay or a casual trip to a new city, hotel bookings are mandatory and each one of us desires to optimize our stay. Optimization, for someone could be booking a hotel where he/she pays less for a good deal, or maybe just getting the only luxurious suite, in a 7-star hotel during a non-peak period.

We are given a Hotel Booking dataset, which stores tabular information about the guests' booking pattern, stay duration, choice of meal and much more for a consecutive year range and we’ll be performing a profound analysis on the dataset, to dig out details and predict a few trends pertaining to the data. Firstly, I don't want to pay any surged random price for my booking rather, I will be happy to pay an optimized value for my stay. Secondly, I want my vacation to be safe, as I am accompanying my loved ones, so I would prefer a hotel with less crowd and well equipped with health and safety measures.

Our analysis, would be capable of helping prospective guests in choosing the right hotel, right stay duration and much more for their stay and moreover, would also be introspecting for hotel management in bringing out changes (if, any) in their services for the guests.

Let's begin the chase!

# SUMMARY OF CONCLUSIONS
In conclusion, our analysis of hotel booking data shows that various factors such as the number of people, lead time, room type, hotel type, and booking channels have a significant impact on hotel revenue and customer behavior. We found that the CITY HOTEL is the most preferred hotel type, generating higher revenue than Resort hotel. The Room Type A is the most demanded room type, but Room Types G, H, and F provide better adr than Room Type A. Bookings peaked in the year 2016, and almost 30% of the bookings made at the City hotel got canceled. TA/TO is the most used channel for planning hotel visits ahead of time, while other mediums are preferred for sudden visits. The GDS channel brings higher revenue generating deals for City hotel, while Resort hotel has more revenue generating deals by direct and TA/TO channel. The ADR for Resort hotel is highest between May to September, whereas the best time to book a City hotel is from October to March. The people from the top 10 countries choose Resort hotels over City hotels, and most guests come from Portugal and Great Britain. Additionally, we observed that as the total number of people increases, the adr also increases, and the longer the stay length, the best price customers will get. Finally, most of the customers prefer BB (bed & breakfast) meal type in both hotel types, and car parking space is not a significant concern for most customers.

