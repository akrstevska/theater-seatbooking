# Online Theater Management System

## Description

The **Online Theater Management System** is a web-based application designed to streamline the management of a theater's operations. This system provides functionalities for managing theater shows, showtimes, reservations, and customer information, offering both administrators and customers a convenient platform for interacting with the theater. 

This system was developed as a **team project** in our **second year** for the **Software Engineering** class.

The system allows users to easily book theater seats, view available shows, and reserve tickets in real-time using an interactive seating map. Admins can manage show details, review reservations, and approve them through a dedicated admin panel. The backend and frontend are both hosted on **Azure** for reliable performance and availability.

## Features

- **Interactive Seat Booking Map**:  
  The system features a real-time, interactive map of theater seats. Customers can select their desired seats based on availability, with the system updating in real-time to reflect reserved and available seats. Customers first select a show, then choose a repertoire (date and time), after which they can see a live seat map for their chosen showtime.

- **User Login System**:  
  Only logged-in users are able to make reservations. This ensures that only registered users can access the booking system and manage their bookings. The login system is secure and user-friendly.

- **Seat Reservation Limits**:  
  Users can reserve a maximum of **4 seats** per repertoire to ensure fair ticket distribution. This limitation prevents large-scale seat reservations by a single user for one show.

- **Admin Panel**:  
  The system includes an admin panel that allows administrators to manage shows, repertoire (dates and times), and reservations. Admins can approve or reject seat reservations made by users, helping ensure that seat availability is properly managed.

- **Real-Time Reservation Management**:  
  When a user reserves seats, the system updates the available seats in real-time. This ensures that no two users can reserve the same seat simultaneously. The reservation process is efficient and seamless for a smooth user experience.

- **Backend & Frontend**:  
  - **Backend**: Built using **PHP** for server-side logic, managing users, reservations, and shows.
  - **Frontend**: The frontend is developed using **HTML**, **CSS**, and **JavaScript** for a responsive, user-friendly interface. The interactive seat booking map is integrated into the frontend for a dynamic user experience.
  - Both the **backend and frontend are hosted on Azure** for reliable performance.

## Technologies Used

- **PHP** (for backend)
- **HTML**, **CSS**, **JavaScript** (for frontend)
- **Azure** (for hosting the application)
- **MySQL** (for database management)
- **AJAX** (for real-time seat booking functionality)

## Installation

Clone the repository:
   ```bash
   git clone https://github.com/yourusername/online-theater-management-system.git
   ```
### Set up the backend:
1. Ensure you have **PHP** and **MySQL** installed.
2. Configure the database connection and run the provided SQL script to set up the necessary tables.

### Set up the frontend:
1. Open the frontend files (`index.html`, `style.css`, etc.) in your preferred web server environment.
2. Deploy the application to **Azure** for hosting.

## How to Use

1. **Sign up / Log in**: Users must sign up or log in to access the booking system.
2. **Select a Show**: Choose the show you would like to attend.
3. **Select a Repertoire**: Pick a specific date and time for the show.
4. **Choose Seats**: Use the interactive map to select available seats for the show.
5. **Reserve**: Confirm the reservation and complete the booking process.

For **administrators**, log in to access the **Admin Panel**, where you can:
- Add and manage shows and repertoire.
- Review and approve/reject seat reservations.

## Live Demo

You can view a live demo of the system here:  
[Online Theater Management System Demo](https://your-demo-link.com)

## Contribution

This project was created as part of a **team assignment** in our **Software Engineering** course. We worked collaboratively to design, develop, and test the system.

Feel free to contribute by submitting issues or pull requests.

