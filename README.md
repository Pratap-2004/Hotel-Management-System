# Hotel Management System

## Description
Hotel Management System is a web-based application designed for managing room bookings, payments, and user/admin interactions for a hotel. The system ensures a user-friendly experience, integrating features for both users (guests) and hotel administrators.

## Features

### User Features:
- **User Login/Signup**: Users can create an account and log in to manage their bookings.
- **Room Booking**: Users can book rooms, view room details, and select services.
- **Booking History**: Users can view their previous bookings.
- **Room Cancellation**: Users can cancel their room bookings if plans change.

### Admin Features:
- **Admin Login/Signup**: Admins can manage room bookings, add or remove rooms, and confirm or deny booking requests.
- **Room Management**: Admins can modify room details, manage room statuses, and oversee all bookings.
- **Booking Confirmation**: Admins can confirm room bookings and process payments.

### Additional Features:
- **Image Gallery**: Displays images of the hotel rooms.
- **Room Brochure**: Shows the room rate card and details.
- **Payment Gateway**: Integrated payment options for users to complete the booking.

## Tools Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL (Database file: `iwp.sql`)

## Working of the System

1. A new user signs up and logs in using their email and password.
2. The user books a room, and the request is sent to the hotel administrator.
3. The admin either confirms or deletes the booking request. Users can also delete their requests.
4. Once confirmed, users can pay for the room.
5. After check-out, payment is finalized, and the booking is added to the history.
6. Users can extend their stay if needed, with an option to modify the check-out date.


## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Hotel-Management-System.git

