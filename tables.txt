Tables:

User

User_ID (Primary Key)
Name
Email
Password
Role
Event

Event_ID (Primary Key)
Title
Description
Date
Time
Venue_ID (Foreign Key referencing Venue table)
Ticket_Availability
Ticket

Ticket_ID (Primary Key)
Event_ID (Foreign Key referencing Event table)
Seat_Number
Price
Status
Booking

Booking_ID (Primary Key)
User_ID (Foreign Key referencing User table)
Event_ID (Foreign Key referencing Event table)
Booking_Date
Total_Price
Status
Payment

Payment_ID (Primary Key)
Booking_ID (Foreign Key referencing Booking table)
Payment_Method
Transaction_ID
Amount
Venue

Venue_ID (Primary Key)
Name
Address
Capacity
Facilities


