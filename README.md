# This project models an airline management database using SQL, covering the complete workflow of bookings, tickets, flights, boarding passes, and aircraft configurations. The system ensures proper handling of multi-passenger bookings, connecting flights, seat allocations, and boarding processes.
The goal of this project is to design and implement a relational database schema that reflects real-world airline operations while maintaining data integrity, efficiency, and scalability.
#The purpose of this project is to:
-Manage multi-passenger bookings and unique tickets for each traveler.
-Handle connecting flights and round trips within a single ticket.
-Ensure unique seat allocations at check-in through boarding passes.
-Track flights, airports, and aircraft seat configurations.
-Provide a foundation for queries such as passenger manifests, flight schedules, and seat utilization.
#Key Features
✔️ Relational Schema Design – Created normalized tables for bookings, tickets, flights, boarding passes, airports, aircrafts, and seats.
✔️ Business Rules Implemented –
-Unique ticket numbers per passenger
-Unique flight-seat combinations to avoid double booking
All tickets in a booking share the same flight segment(s)
✔️ Flight & Passenger Handling – Supports one-way, round-trip, and connecting flights.
✔️ Data Integrity – Enforced primary and foreign keys to maintain consistency across entities.
✔️ Query Support – Designed to answer operational questions like:
-How many passengers are booked on a flight?
-Which seats are available or assigned?
-What are the flight segments for a given ticket?
