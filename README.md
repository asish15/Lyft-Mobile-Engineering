# Lyft-Mobile-Engineering

Task 4 - Android - Kotlin - Payment Info
Description
Task 4 involved implementing the Payment Info feature in the Lyft Android application using Kotlin. This feature allows users to manage their payment methods, including adding, editing, and deleting payment options.

Implementation Details
In this task, we leveraged the following technologies and practices:

Android development using Kotlin.
Integration with the Lyft backend to securely store and retrieve payment information.
Data validation and error handling to ensure a smooth user experience.
Properly handling user authentication and authorization for managing payment methods.
Code Structure
The code for Task 4 is organized into the following main components:

PaymentInfoFragment: This fragment displays the user's saved payment methods and allows them to add, edit, or delete payment options.
PaymentInfoViewModel: Manages the data and business logic related to payment information.
PaymentInfoRepository: Handles communication with the Lyft backend for payment operations.

Task 5 - Kotlin - Who's the Closest Driver?
Description
Task 5 involved implementing the "Who's the Closest Driver?" feature in the Lyft Android application using Kotlin. This feature allows users to quickly find the nearest available Lyft driver based on their current location.

Implementation Details
In this task, we used the following technologies and practices:

Android development using Kotlin.
Location services to determine the user's current location.
Integration with the Lyft backend to fetch real-time driver availability and location data.
A user-friendly interface that displays the closest driver's details, including their name, profile picture, and estimated arrival time.
Code Structure
The code for Task 5 is organized into the following main components:

ClosestDriverFragment: This fragment displays the closest driver's information, including their name, profile picture, and estimated arrival time.
ClosestDriverViewModel: Manages the data and business logic related to finding the closest driver.
LocationService: Handles location tracking and retrieval.
DriverService: Communicates with the Lyft backend to fetch driver information.
