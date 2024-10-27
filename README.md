# Hotel-Booking-System
A web-based Hotel Booking System for managing guest bookings, rooms, and payments. Features include room selection, automated payment calculations, booking updates, search functionality, and a booking summary. Built with HTML, CSS, and JavaScript, with data stored locally in localStorage.


This **Hotel Booking System** is a web-based application designed to streamline the management of hotel bookings, guests, rooms, and payments. The system offers a user-friendly interface for adding, updating, and viewing bookings, along with a **Booking Summary** for quick insights on total bookings and payment collected.

## Features

- **Add, Update, and Delete Bookings**: Easily manage hotel bookings with CRUD functionality.
- **Room Types and Pricing**: Choose from various room types, each with pre-defined daily rates.
- **Date-Based Payment Calculation**: Payment is automatically calculated based on the selected room type and booking duration.
- **Search Bookings**: Quickly find bookings by guest name for easy management.
- **Booking Summary**: View the total number of bookings and the total payment collected.
- **Persistent Data Storage**: All booking data is stored in `localStorage`, ensuring data is saved across sessions.

## Tech Stack

- **HTML**: Structure and layout.
- **CSS**: Styling and responsive design.
- **JavaScript**: Functionality for managing bookings, calculating payments, and storing data in `localStorage`.

## Screenshots

![Hotel Booking System Screenshot](screenshot-url)

## Setup

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/yourusername/hotel-booking-system.git
    ```
2. Open the project folder.
    ```bash
    cd hotel-booking-system
    ```
3. Open `index.html` in your preferred browser to view the application.

## Usage

1. **Book a Room**:
    - Go to the **Book Room** section.
    - Enter guest details, select room type, and set check-in and check-out dates.
    - Click the **Book Room** button, and the booking will appear in the **Current Bookings** section.

2. **Manage Bookings**:
    - In the **Current Bookings** section, use the **Update** button to modify a booking or **Cancel** to delete it.
    - Use the search bar to find specific bookings by guest name.

3. **View Booking Summary**:
    - Navigate to the **Booking Summary** section to see the total number of bookings and total payment collected.

## File Structure

- `index.html`: Main HTML file that structures the application layout.
- `styles.css`: CSS file containing styling for the layout, buttons, and responsiveness.
- `script.js`: JavaScript file managing the logic for booking management, payment calculation, and data persistence.

## Future Enhancements

- **Database Integration**: Replace `localStorage` with a database for more secure and scalable data management.
- **Authentication**: Add user login to protect data and allow multiple hotel staff members to manage bookings.
- **Calendar View**: Add a calendar-based booking view for a more comprehensive room availability display.

