# Road-Transportation-System

Description:
A dummy road transport database of Odisha. The database contains routes from one city/town to another. Details like total distance to be covered, intermediate halting stations, different resources available along route etc. have also been included in the database. Search facility is provided for route details and other information required during the journey. Booking for a journey is allowed. Admin can manipulate the database of buses available for transportation.

Key Features:
•	 Booking of a journey on a single platform
•	Track the journey
•	A full knowledge of intermediate stations
•	Facilities available throughout the journey 

Target Audience:
•	Any user who wants to discover the routes in course from initial and destination.
•	Any user who wants to book a journey.




Basic Structure:

 







							









































Explanation: 
•	Admin Role: -
       Int Login()- used for login
                 Int adminview()- menu for admin
Int checkListOfBusesRegistered()- check the list of buses registered in the database
                 Int registerBus()- used to  resister bus
                 Int deleteBus()- can delete bus info

                 
•	Passenger Role: -

 void main_menu() – menu for passenger
 int Login() – used for login
 void register_user() – used for registering
 void save_user – save user to database
 void reservation() – reservation of seats
 void book_det() – view reservation details
 void cancellation() – cancellation of seats 
 void display(string name) – view Passenger’s details
 string get_username() – get username of the passenger
 string get_password() – get password of the passenger

•	General Information Section: -

Provides information on distance between source and destination.
Routes between source and destination.
Hospitals and Restaurants between source and destination.

OOP Concepts Covered:
•	Classes
•	Inheritance
•	Polymorphism
•	Dynamic Memory Allocation
•	Templates


File Structure:
•	program.cpp - main program containing all the required header files, classes, data members and member and non-member functions.
•	db_bus.csv – database containing all bus details
•	login.csv – database containing user login details
•	Passenger.csv – database containing passenger’s booking details
•	hospitals.csv – database containing hospitals grouped by their cities
•	resturants.csv – database containing restaurants grouped by their cities
