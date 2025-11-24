## Problem statement
Manual booking still prevails in many small theatres and student environments, which leads to long queues, human errors, and difficulties faced in managing seat availability. In addition, many customers have reported inconvenience checking show timings, ticket prices, and available seats.
It seeks to address these issues by developing a Python-based Movie Ticket Booking System that streamlines the process of ticket booking by automating it. The proposed system will have an interface where users can choose a movie, decide on show timings, select available seats, and automatically calculate the price.

## Scope of the project
The scope of this project is to design a Python-based system for viewing available movies, selecting show timings, choosing seats, calculating ticket prices, and confirming bookings. The system is designed to be simple and user-friendly to perform basic ticket booking operations. It does not involve online payments or connectivity to a database.

## Target users
- Students and Beginners in Python: Those learning GUI development, event handling, or file operations using Tkinter.
- Developer Desktop Application Exploration: Anyone who wants to learn how to create user-friendly desktop applications using Python.
- Small Theaters or Local Cinemas: Smaller venues that require a basic ticket booking interface without complex backend systems. Educators and Trainers Teachers who would like a concrete example to illustrate some GUI development concepts. Hobbyists and Programmers Building Portfolio Projects Individuals looking for more practical, project-oriented opportunities for demonstrating their skills.

## High-level features
- Graphical User Interface (GUI):
  Built with Tkinter for a clean, easy-to-use desktop interface.
  Structured layout that includes movie selection, options for showtime, and seat grid.
- Movie & Showtime Selection:
  Drop down menu to select from multiple movies.
  Radio buttons to select from available showtimes.
- Interactive Seat Selection:
  Visual seating grid (rows A–F, 10 columns).
  Clickable seats allow the user to select or deselect.
  Pre-booked seats are disabled and have a differentiated color.
- Booking Validation:
  Ensures that users select at least one seat before booking.
  Prevents the selection of unavailable seats.
- Price Calculation Automation
  Calculates the total cost based on the number of selected seats.
  Displays a detailed booking summary.
- Confirmation Popup
  Pops up a window that acknowledges movie, time, seats, and price.
- Event Logging System
  Records all bookings into booking_log.txt with date & time.
