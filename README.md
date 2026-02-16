# Movie_ticket_Bookings
The Movie Ticket Booking System is a simplified MySQL-based backend project designed to manage essential movie booking operations. It allows storing and retrieving information about movies, users, shows, seats, and bookings
Functional Requirements
FR1: The system shall store user account details (name, email, password).
FR2: The system shall store movie metadata (title, genre, duration).
FR3: The system shall maintain show schedules for each movie.
FR4: The system shall allow assigning seats to bookings.
FR5: The system shall retrieve available seats for any show.
FR6: The system shall store booking information linked to users and shows ER Diagram (Textual Representation)
Entities:- USERS(user_id, name, email, password)
- MOVIES(movie_id, title, genre, duration)
- SHOWS(show_id, movie_id, show_date, show_time, price)
- SEATS(seat_id, seat_number)
- BOOKINGS(booking_id, user_id, show_id, seat_id, booking_time)
