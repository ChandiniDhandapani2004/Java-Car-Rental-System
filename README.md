# Java-based Car Rental System

## Overview
The Java-based Car Rental System is a simple console application designed to manage the operations of a car rental business. It allows users to rent and return cars, track customer information, and calculate rental costs based on the number of days. The application simulates a real-world car rental process, providing a seamless experience for both customers and administrators.

## Features
- Rent a Car:
  - Customers can browse available cars and rent them for a specified number of days.
  - The application calculates the total rental cost based on the car's daily rental price.
- Return a Car: 
  - Customers can return rented cars, and the system updates their availability status.
- Customer Management: 
  - Automatically assigns unique customer IDs and tracks rental history.
- Car Management: 
  - Tracks the availability and rental status of cars.

## Cars in the System
- Toyota Camry
- Honda Accord
- Mahindra Thar
- Tata Nexon
- Maruti Suzuki Swift
- Skoda Slavia
- Kia Seltos

##  Technologies Used
- Language: Java
- Tools: Java Development Kit (JDK)

## How to Run
1. Install Java: Ensure you have JDK installed on your system.  
   [Download JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
   
3. Clone the Repository:  
   git clone https://github.com/<your-username>/java-car-rental-system.git
   cd java-car-rental-system
   
4. Compile and Run the Program:  
   javac Main.java
   java Main

## Usage
### Menu Options:
1. Rent a Car:
   - Enter your name, select a car from the available options, and specify the rental duration.
   - Confirm the rental to proceed.
2. Return a Car:
   - Enter the car ID to return it and mark it as available.
3. Exit:
   - End the session and exit the application.

### Example Flow:
1. Start the application.
2. Choose option `1` to rent a car.
3. Enter your name and car details.
4. Choose option `2` to return a car after use.

## Future Enhancements
- Add a graphical user interface (GUI) for improved usability.
- Integrate a database to persist customer and rental data.
- Implement advanced features like dynamic pricing and real-time availability updates.

##  Contribution
Contributions are welcome!  
1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Submit a pull request with a detailed description of the changes.
