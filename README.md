# Event Management Platform - Internship Assessment

Thank you for considering my submission for the Event Management Platform internship assessment. Below you'll find details about the project and how to set it up.

## Project Overview

This project is an Event Management Platform designed to allow users to browse upcoming events, book tickets, and manage their bookings. Additionally, administrators have access to an admin dashboard for event management.

## Features Implemented

- **Event Listing and Details**: Users can view a list of upcoming events with details such as title, date, location, and ticket availability.
- **Booking Tickets**: Users can select the number of tickets they wish to book for an event and complete a simple booking process.
- **User Dashboard**: Users have access to a dashboard where they can view their booked events and cancel bookings if needed.
- **Admin Dashboard**: Administrators can manage events by creating new events, editing event details, and deleting events. They can also view all bookings and manage them, including canceling bookings and viewing attendee details.
- **Basic Styling and UI/UX**: A clean and simple design has been applied using Tailwind CSS to ensure a consistent look and feel across the platform. Usability and intuitive navigation have been prioritized for an enhanced user experience.
- **Error Handling and Validation**: Basic error handling and validation for user inputs have been implemented, along with informative error messages to guide users in case of invalid actions.

## Tech Stack Used

- **Frontend**:
  - React.js
  - React Router
  - Axios for API requests
  - Tailwind CSS for styling

- **Backend**:
  - Node.js with Express.js
  - MongoDB with Mongoose for data storage
  - JWT for authentication
  - bcrypt for password hashing

## You can play around with the app via this link:
- [The working frontend](https://etite-events-management-challenge-frontend-3d1y.vercel.app/#/users/login)
- [Backend](https://etite-events-management-challenge-backend.onrender.com/api/v1/events/all)
- [Figma](https://www.figma.com/file/xHGZ5djI9o7hvRltvge7xO/Etite-challenge?type=design&node-id=0-1&mode=design&t=jCg9kgcKFciHR891-0)

## Setup Instructions

1. Clone this repository to your local machine.
2. Navigate to the frontend and backend directories separately and run `npm install` to install dependencies.
3. Create a `.env` file in the backend directory and configure environment variables as needed (e.g., database connection string, JWT secret).
4. Run the backend server using `npm start` or `npm run dev` for development.
5. Run the frontend development server using `npm run dev`.
6. Access the application through your browser at `http://localhost:3000`.
