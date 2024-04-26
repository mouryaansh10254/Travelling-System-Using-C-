# Travelling-System-Using-C++
This project aims to develop an online travel system, primarily focused on ticket booking, using C++.The system facilitates the booking of bus and train tickets, as well as cab reservations. This projects enables users to book tickets without any issues .

The provided c++ code implements a Travelling System with functionlites for Train Booking,Bus Booking and Cab Booking.

Three module of project are:-
-User Management
-Booking System
-Main Menu and Navigation

User Management:-This module consist of functions for User-Profile Structure and Login and Logout Mechanism.
->User-Profile Structure: It store user information such as username,password and emial id.Functions like 'Adding_new_client','login_client','WriteToFile' and 
  'InitializeListing' manage user Profiles and  handle user authentication.
->Login and Logout Mechanism: User can log in and log out through the 'login_client' and 'logout_client' functions.

Booking System:-This module consist of function for Train Booking,Bus Booking and Cab Booking.
->Trian Booking: User can install new trains,make reservations,check seat availability and view train details.Train data is stored in the 'train_data.txt' file.
->Bus Booking: User can install new bus,make reservations,check seat availability,and view bus details.Bus data is stored in the 'bus_data.txt' file.
->Cab Booking: User can book a cab by providing pickup and drop-off-details,including distance.The cost calculation is based on the distance traveled.Booking details are displayed,and users can confirm or exit.Cab data is stored in the 'cab_data.txt' file.

Main Menu and Navigation:-This modulw consist of function for main menu and file handling.
->Main Menu:- The program begins with a main menu where users can add new profiles,log in and exit.
->Main Program Loop:- The program runs in loops,allowing users to navigate between different functionalities.
->File Handling:- User profiles,train data,bus data and cab data are stored in text.File I/O functions('WriteToFile','loadFromFile)handle reading from and writing to these files.

Basically this run only on terminal.

Thank you
