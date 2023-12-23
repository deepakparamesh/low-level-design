# Problem definition

An airline management system is a software used to manage all activities of the airline system efficiently. Nowadays, every airline has a management system to digitize the process of scheduling flights, managing staff, ticket reservations, and performing other necessary airline management tasks. Moreover, the system keeps track of the number of aircraft, pilots, and their availability at airports. The system provides customers the complete flight information so they can view the available flights and schedule them online. Similarly, the admin can manage all the airline activities with the help of this system. Therefore, the airline management system facilitates its customers as well as admins and controls all the operations of the airline company.

## Expectations from the interviewee

There are several components present in the airline management system, each with specific constraints and requirements. The following provides an overview of some of the main things that the interviewer will want to hear you discuss in more detail, during the interview.

## Flight reservation

Flight reservation is an essential part of the airline management system. The system has to ensure that no two people should be mapped to the same seat. The interviewer expects you to ask questions to identify how the system will complete flight reservations:

- How will the system ensure that multiple users do not have the same seat on the aircraft?

- Can one itinerary reserve multiple flights?

- Can the customer reserve the whole aircraft?

## Payment handling

One of the airline management system's most significant attributes is its payment structure for its customers. This can vary, so the interviewer would expect you to ask the questions listed below:

What payment methods can the customer use, for example, credit card or cash?

How does the customer make the payment? Does the customer pay online or in persone?

Will the customer be able to pay in advance for a flight booking, or is a just-in-time (JIT) payment method available?

## Price variance

Now that we’ve discussed the payment methods of the airline management system, let’s ask the interviewer about the pricing model. You may ask the questions listed below:

Is the price set manually, or does the system calculate the price for each flight?

Does every seat has the same price, or is it calculated based on the seat type?

Does the weekdays and weekends affect the price of the flight?

Is the price of the flight affected by an increase in demand?

How does the duration of the flight affect the payment?

## Flight cancellation

In the airline management system, the customer may want to cancel the flight after booking it. Therefore, you can ask the following questions:

Can the customer cancel a flight?

What is the time limit to cancel the flight?

Which type of users are allowed to request a flight cancellation?

## Design approach

We’ll design this airline management system using the bottom-up approach. For this purpose, we will follow the steps below:

Identify and design the smallest components first, including seat, flight, etc.

Use these small components to design bigger components, including airport, aircraft that can be composed of multiple seats, etc.

Repeat the steps above until we design the whole airline management system.

## Design pattern

It is always a good practice to discuss the design patterns that an airline management system falls under, during the interview. Stating the design patterns will give the interviewer a positive impression and shows that the interviewee is well-versed in the advanced concepts of object-oriented design.

The following design patterns can be used to design the airline management system:

The Singleton design pattern

The Observer design pattern

Let’s explore the requirements of the airline management system in the next lesson.

## Requirement

R1: A customer should be able to search for flights by the date, departure, and destination airport.

R2: A customer should be able to reserve tickets for available flights. Customers should also be able to book multiple flights at once.

R3: The customer should be allowed to book multiple seats for a single flight.

R4: The system should allow the customer to check flight details, such as available seats, flight schedules, and departure/arrival times.

R5: The admin should be able to add new flights. The admin should be able to update or cancel scheduled flights.

R6: An airline should be able to own multiple aircrafts. The admin should be able to add these aircrafts to the system.

R7: An airline should be able to operate its flights from different airports.

R8: The admin should be able to assign pilots and crew members to flights effectively.

R9: The customer should be able to make payments against their flight reservations.

R10: The customer should be able to cancel their previous reservations.

R11: The front desk officer should be able to reserve tickets, create itineraries, and make flight payments for the customer.

R12: The flight crew should be able to view the schedule for their assigned flights.

R13: The system should send the customer a notification whenever a reservation has been made or canceled or when there is an update for their flight.

