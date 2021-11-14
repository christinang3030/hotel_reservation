# Hotel Reservation System
DBMS for a hotel reservation system

In this project, we create a database management system for managing bookings at a hotel. According to our design, guests can book available rooms, with each room providing a certain service to guests. To do this, we design eight schemas: Guest, Room, Service, Booked, Available, Employee, Transaction, and ArchivedGuest. Guest contains relevant information relating to each guest within the system, such as their ID, name, age, whether or not they currently have a reservation, and the date their information was last updated. Room provides information about each room at the hotel, including the room ID, type of room, and price of booking. Service indicates what services each room provides. Booked and Available are used to organize data regarding which rooms are booked and which are available. Employee is similar to Guest in that it contains information regarding employees of the hotel. Transaction records the payments of guests at the hotel who have booked a room. ArchivedGuest is a schema that contains archived guest information that have not been updated since a certain date. Through the creation of these schemas, we effectively simulate how a hotel would manage its bookings.
