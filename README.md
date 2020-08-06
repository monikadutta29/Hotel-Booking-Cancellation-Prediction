# Hotel-Booking-Cancellation-Prediction
__Objective__ – To analyse the dataset associated with the hotel booking demand and build a model to predict whether the hotel booking gets cancelled or not.

## About the dataset
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
All personally identifying information has been removed from the data.
1.	__hotel__ - Hotel (H1 = Resort Hotel or H2 = City Hotel)
2.	__is_canceled__ - Value indicating if the booking was canceled (1) or not (0)
3.	__lead_time__ - Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
4.	__arrival_date_year__ - Year of arrival date

5.	__arrival_date_month__ - Month of arrival date
6.	__arrival_date_week_number__ - Week number of year for arrival date 

7.	__arrival_date_day_of_month__ - Day of arrival date
8.	__stays_in_weekend_nights__ - Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
9.	__ stays_in_week_nights__ - Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
10.	__adults __ - Number of adults
11.	__children__ - Number of children
12.	__babies__ - Number of children
13.	__ meal__ - Type of meal booked. Categories are presented in standard hospitality meal packages.
  <br> - Undefined/SC – no meal package
  <br> - BB – Bed & Breakfast   
  <br> - HB – Half board (breakfast and one other meal – usually dinner)
  <br> - FB – Full board (breakfast, lunch and dinner)
14.	__country__ - Country of origin. Categories are represented in the ISO 3155–3:2013 format
15.	__market_segment__ - Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
16.	__distribution_channel__ - Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
17.	__is_repeated_guest__ - Value indicating if the booking name was from a repeated guest (1) or not (0)
18.	__previous_cancellations__ - Number of previous bookings that were cancelled by the customer prior to the current booking
19.	__previous_bookings_not_canceled__ - Number of previous bookings not cancelled by the customer prior to the current booking
20.	__reserved_room_type__ - Code of room type reserved. Code is presented instead of designation for anonymity reasons.
21.	__assigned_room_type__ - Code for the type of the room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g overbooking) or by customer request. Code is presented instead of designation for anonymity reasons.
22.	__booking_changes__ - Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
23.	__deposit_type__ - Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories:
 	<br> No Deposit – no deposit was made; 
  <br> Non-Refund – a deposit was made in the value of the total stay cost; 
  <br> Refundable – a deposit was made with a value under the total cost of stay.
24.	__agent__ - ID of the travel agency that made the booking
25.	__company__ - ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
26.	__days_in_waiting_list__ - Number of days the booking was in the waiting list before it was confirmed to the customer
27.	__customer_type__ - Type of booking
  <br> Contract - when the booking has an allotment or other type of contract associated to it; 
  <br> Group – when the booking is associated to a group; 
  <br> Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; 
  <br> Transient-party – when the booking is transient, but is associated to at least other transient        booking
28.	__adr__ - Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights
29.	__required_car_parking_spaces__ - Number of car parking spaces required by the customer
30.	__total_of_special_requests__ - Number of special requests made by the customer (e.g. twin bed or high floor)
31.	__reservation_status__ - Reservation last status, assuming one of three categories:
  <br> Cancelled – booking was cancelled by the customer; 
  <br> Check-Out – customer has checked in but already departed; 
  <br> No-Show – customer did not check-in and did inform the hotel of the reason why
32.	__reservation_status_date__ - Date at which the last status was set. This variable can be used in conjunction with the Reservation Status to understand when was the booking cancelled or when did the customer checked-out of the hotel
 
