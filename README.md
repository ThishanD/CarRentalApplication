# CarRentalApplication
functionalities: Car Inventory, Rental Management, Return Management, Admin Privileges


1. Car Inventory:
    o Maintain a collection of available cars for rent.
    o Each car should have 
    ▪ Unique identifier
    ▪ Maker
    ▪ Model
    ▪ Rental price
    ▪ Availability status
2. Rental Management
    o Allow regular users to search for available cars based on the filters 
    mentioned below:
    ▪ Maker
    ▪ Model
    ▪ Rental price.
    o Display the list of available cars that match the search criteria.
    o Enable regular users to select a car and specify the rental duration.
    o Generate a rental agreement with details such as car information, rental 
    duration, and total cost, user details.
    o User can view all rental agreements from “My Rental Agreement” tab.
    o Can edit rental agreement details before accepting.
    o Regular user should not be able to edit/delete rental agreement once 
    agreed.
3. Return Management
    o Allow regular user to mark the rented cars as “request for return”.
    o Admin user can validate all cars marked as “request for return”.
    o Allow admin user to mark the rented car as returned after completing the 
    validation/inspection.
    o Update the availability status of the car once returned.
    Classification: Internal
4. Admin Privileges
    o Provide an admin user with additional functionalities for managing the 
    car inventory.
    o Allow the admin user to add new cars to the inventory, including car 
    details and rental price.
    o Enable the admin user to remove cars from the inventory.
    o Admin user can update the car details such as rental price.
    o Allow the admin user to update the availability status of the cars.
