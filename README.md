# Travelling-System-Using-C++

This project aims to develop an online travel system using C++, focused on ticket booking for buses, trains, and cabs. The system allows users to book tickets and make reservations efficiently.

## Features

### User Management

- **User-Profile Structure**: Stores user information such as username, password, and email ID. Functions for adding new clients, logging in, and writing to and initializing the user profile list.
  
  **Functions**:
  - `AddNewClient()`: Adds a new client profile.
  - `LoginClient()`: Handles user login.
  - `LogoutClient()`: Handles user logout.
  - `WriteToFile()`: Writes user data to a file.
  - `InitializeListing()`: Initializes the user profile listing.

### Booking System

- **Train Booking**: Users can add new trains, make reservations, check seat availability, and view train details. Train data is managed in the `train_data.txt` file.
  
  **Functions**:
  - `AddTrain()`: Adds new trains to the system.
  - `ReserveTrain()`: Makes reservations for trains.
  - `CheckTrainAvailability()`: Checks seat availability for trains.
  - `ViewTrainDetails()`: Displays details of trains.

- **Bus Booking**: Users can add new buses, make reservations, check seat availability, and view bus details. Bus data is managed in the `bus_data.txt` file.
  
  **Functions**:
  - `AddBus()`: Adds new buses to the system.
  - `ReserveBus()`: Makes reservations for buses.
  - `CheckBusAvailability()`: Checks seat availability for buses.
  - `ViewBusDetails()`: Displays details of buses.

- **Cab Booking**: Users can book cabs by providing pickup and drop-off details. The cost is calculated based on distance. Booking details are displayed, and users can confirm or exit. Cab data is managed in the `cab_data.txt` file.
  
  **Functions**:
  - `BookCab()`: Books a cab and calculates the cost based on distance.
  - `ViewCabDetails()`: Displays details of cabs.

### Main Menu and Navigation

- **Main Menu**: Begins with a menu where users can add new profiles, log in, and exit.
  
  **Functions**:
  - `DisplayMainMenu()`: Shows the main menu options.
  - `HandleMenuSelection()`: Handles user input from the main menu.

- **Main Program Loop**: Runs in loops to allow navigation between different functionalities.

- **File Handling**: Manages user profiles, train data, bus data, and cab data through text files. Functions for reading from and writing to these files.
  
  **Functions**:
  - `WriteToFile()`: Writes data to text files.
  - `LoadFromFile()`: Loads data from text files.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mouryaansh10254/Travelling-System-Using-C++.git
   cd Travelling-System-Using-C++

## Usage
 - **Add New Profiles**: Create user profiles through the main menu.
 - **Login and Logout**: Access user-specific features by logging in.Log out when done.
 - **Booking Tickets**: Choose between trian,bus,or cab booking from the main menu.
