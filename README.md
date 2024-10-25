# AirMaster - Airline Management System

## Overview

The **Airline Management System** is a desktop application developed using Java Swing that provides a graphical user interface (GUI) for managing airline operations. It includes features such as viewing flight details, adding customer information, booking flights, managing journey details, ticket cancellation, and generating boarding passes. The system is designed to be user-friendly, with intuitive navigation and a visually appealing interface

## Features

- **Flight Details:** View all available flights with their respective details.
- **Customer Management:** Add and manage customer details, including personal information and travel preferences.
- **Book Flight:** Easily book flights for customers through an intuitive interface.
- **Journey Details:** Track and manage the journey details of booked flights.
- **Ticket Cancellation:** Cancel a flight booking and manage related customer details.
- **Boarding Pass:** Generate and print a boarding pass for a booked flight.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/azizbelkhouja/AirMAster.git
   ```
   
2. **Open the project in your preferred IDE (e.g., IntelliJ IDEA, Eclipse).**

3. **Set up the required dependencies:**
   - Ensure that you have Java Development Kit (JDK) installed (preferably JDK 8 or later).

4. **Compile and run the project:**
   - Navigate to the main class `Home.java` and run it.

## Usage

Once the application is running, you'll be presented with the main screen, which contains the following options in the menu bar:

- **Details:**
  - **Flight Details:** Opens a window displaying all flight information.
  - **Add Customer Details:** Allows you to add new customer details.
  - **Book Flight:** Opens the booking interface for customers.
  - **Journey Details:** Displays details about booked journeys.
  - **Cancel Ticket:** Opens the interface to cancel a booked ticket.

- **Ticket:**
  - **Boarding Pass:** Generates and prints the boarding pass for a booked flight.

### Navigation

- **Image and Heading:** The main screen displays a welcome image and heading.
- **Menu Bar:** Use the menu bar at the top to navigate between different features.

## Code Overview

The main components of the application are:

- **Home.java:** The main class that initializes the application and handles the menu interactions.
- **AddCustomer.java:** Manages adding customer details.
- **FlightInfo.java:** Displays flight details.
- **BookFlight.java:** Handles the flight booking process.
- **JourneyDetails.java:** Manages journey details for flights.
- **Cancel.java:** Handles ticket cancellations.
- **BoardingPass.java:** Generates boarding passes.

### GUI Components

- **JFrame:** The main window container.
- **JLabel:** Used for displaying text and images.
- **JMenuBar:** The top menu bar containing various options.
- **JMenu and JMenuItem:** Used for creating menu options and sub-options.
- **ImageIcon:** Displays images in the GUI.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you'd like to change.
