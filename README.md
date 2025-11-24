# MOVIE TICKET BOOKING SYSTEM

## Overview
This project is a Python Tkinter application that gives users a simple and interactive way to book movie tickets. It lets users pick a movie, choose a showtime, and select seats from a visual seating grid. Seats that are already booked are clearly marked and cannot be selected, while available seats can be clicked to toggle selection. After the user chooses their seats, the app calculates the total price, shows a confirmation message, and saves the booking details. 

## Features 
Movie Selection: The user will be able to select a movie from a dropdown list of available movies.
Selection by Showtime: Several show times pop up, with options based on radio buttons.
Interactive Seat Layout: The seats are in grid format, where the available, selected, and booked seats are represented with different colours.
Seat validation ensures users cannot select seats which are already booked.
Real-time Seat Highlighting: Clicking a seat toggles its selection status visually.
Price Calculation: Automatically calculates the total cost based on the number of selected seats.
Booking Confirmation: Pops-up a confirmation window displaying the booking summary.
Booking Log: Saves details of each booking into a log file, booking_log.txt, along with the timestamp.
User-Friendly Interface: Dark-themed, clean, intuitive GUI created using Tkinter

## Technologies/Tools used
Python 3.8
Tkinter
datetime module
Object-Oriented Programming
File handling
Custom Color Themes

## Steps to install and run the project
Install Python 3.8+
Download from: https://www.python.org/
Create a project folder
Save the code in a file called movie_ticket_booking.py:
Open terminal/command prompt
Change directory into the project folder.
Run the application
Windows: python main.py Use the layout Select a movie, choose a time, pick seats, and click Book Tickets. A log file is created automatically: booking_log.txt.

## Instructions for testing
Run the application using movie_ticket_booking.py.
Select a movie and showtime.
Click different seats to confirm selection/deselection works.
Try booking without selecting seats to see the validation.
Book by selecting seats to see the confirmation popup.
open booking_log.txt to verify the booking was logged as expected.

## Screenshots 
<img width="1919" height="1199" alt="Screenshot 2025-11-24 235505" src="https://github.com/user-attachments/assets/6ba6b1a0-63a5-4c44-a0b1-810823187e40" />
<img width="1919" height="1199" alt="Screenshot 2025-11-24 235520" src="https://github.com/user-attachments/assets/ea4f5b0b-73eb-4d29-88a3-e53552129054" />
