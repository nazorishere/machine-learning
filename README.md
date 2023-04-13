# machine-learning

1. Create a new repo called "machine-learning" and include a read-me file which will give more information about the repo.
2. Using the data set provided, carry out an exploratory and explanatory analysis using a jupyter notebook
3. Push this notebook to the repo ("machine-learning")  and include more information on the read-me of 
   the analysis task to give more context on the dataset and the whole analysis.
4. The link to the repo should be included in the document that will be provided.



Exploratory Data Analysis for Hotel Booking Demand
Introduction
This repository contains the code and data used to perform an exploratory data analysis (EDA) on hotel booking demand.

The hospitality industry has been affected by various factors in recent years, including technology advancements and the pandemic. In this context, data analysis can provide valuable insights that can help hotels improve their services and optimize their operations.

The data used in this analysis is from Hotel Booking Demand dataset available on Kaggle. This dataset contains information on hotel bookings, including the number of adults and children, the booking channel, the type of room booked, and whether the booking was canceled or not.

The aim of this EDA is to explore the dataset, gain insights, and provide a summary of the findings. The analysis is performed in Python using Jupyter Notebooks.

Data Description
The dataset used in this analysis contains two separate hotel datasets: one for a city hotel and one for a resort hotel. The data was originally collected by Nuno Antonio, Ana Almeida, and Luis Nunes of the Polytechnic Institute of Porto, Portugal.

The city hotel dataset contains 79,330 observations of 32 features, including:

hotel: Hotel (H1 = Resort Hotel or H2 = City Hotel)
is_canceled: Value indicating if the booking was canceled (1) or not (0)
lead_time: Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
arrival_date_year: Year of arrival date
arrival_date_month: Month of arrival date
arrival_date_week_number: Week number of year for arrival date
arrival_date_day_of_month: Day of arrival date
stays_in_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
stays_in_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
adults: Number of adults
children: Number of children
babies: Number of babies
meal: Type of meal booked.
country: Country of origin of the guest.
market_segment: Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
distribution_channel: Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
is_repeated_guest: Value indicating if the booking name was from a repeated guest (1) or not (0)
previous_cancellations: Number of previous bookings that were cancelled by the customer prior to the current booking
previous_bookings_not_canceled: Number of previous bookings not cancelled by the customer prior to the current booking
reserved_room_type: Code of room type reserved. Code is presented instead of designation for anonymity reasons.
assigned_room_type: Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request.
booking_changes: Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
deposit_type: Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit, Non Refund and Refundable
agent: ID of the travel agency that made