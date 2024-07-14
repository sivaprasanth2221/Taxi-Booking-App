# Taxi Booking System

This is a simple taxi booking system implemented in Java. The system allows users to book taxis, display booking details, and exit the application. It manages the allocation of taxis based on their availability and location, and keeps track of each taxi's earnings and booking history.

## Features

- Book a taxi by providing pickup and drop locations and pickup time.
- Display details of all taxi bookings.
- Manage taxi allocation based on availability and proximity to the pickup location.
- Keep track of taxi earnings and booking history.

## Classes

### MainClass

The `MainClass` contains the main method that runs the application. It provides a simple text-based menu for users to book a taxi, display booking details, or exit the application.

### TaxiBooking

The `TaxiBooking` class manages the list of taxis and the booking process. It includes methods to book a taxi and display booking details. 

#### Methods

- `booking(char pickupLocation, char dropLocation, int pickupTime)`: Books a taxi based on the provided pickup and drop locations and pickup time.
- `display()`: Displays the details of all taxi bookings.

### Taxi

The `Taxi` class represents a taxi with attributes such as current location, customer ID, pickup and drop locations, pickup and drop times, and earnings. It implements the `Cloneable` interface to allow cloning of taxi objects.

## How to Run

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/taxi-booking-system.git
    ```

2. **Navigate to the project directory**:
    ```sh
    cd taxi-booking-system
    ```

3. **Compile the Java files**:
    ```sh
    javac -d . MainClass.java TaxiBooking.java Taxi.java
    ```

4. **Run the application**:
    ```sh
    java TaxiBooking.MainClass
    ```

## Example Usage

Choose any one

Book Taxi
Display Details
Exit
1
Enter Pickup Location
A
Enter Drop Location
B
Enter Pickup Time
9
Taxi number 1 is booked!
Choose any one

Book Taxi
Display Details
Exit
2
Taxi 1
currentLocation=B
customerId=1
pickupLocation=A
dropLocation=B
pickupTime=9
dropTime=10
earnings=150

Choose any one

Book Taxi
Display Details
Exit
3
Thank You!!!
