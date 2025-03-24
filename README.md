# Zen Employee Attendance Tracker

## Important Note About This Demo

This is a demonstration application that simulates a multi-device attendance tracking platform. In its current form, it has the following limitations:

### Current Implementation (Demo Mode)

- **Local Storage**: The application currently uses browser localStorage to store data, which means:
  - Data is specific to each browser and device
  - You cannot access the same data across different devices
  - Changes made on one device won't be visible on another device

- **Simulated Sync**: The application includes visual elements that simulate real-time synchronization, but these are for demonstration purposes only.

### How This Would Work in Production

In a real production environment, this application would be connected to:

1. **Backend Server**: A Node.js, Python, or other server-side application that would handle authentication, data storage, and business logic.

2. **Database**: A database like PostgreSQL, MongoDB, or MySQL would store all user and attendance data.

3. **Real-time Updates**: Technologies like WebSockets or Server-Sent Events would provide true real-time updates across all devices.

4. **Authentication System**: A robust authentication system with secure session management would ensure users can log in from any device and access their data.

## Deployment Instructions

To deploy this application with true multi-device functionality:

1. Set up a backend server using Node.js, Express, and a database like MongoDB or PostgreSQL
2. Implement proper authentication with JWT or similar technology
3. Replace the simulated cloud storage with actual API calls to your backend
4. Deploy both the frontend and backend to a hosting service like Vercel, Netlify, or AWS

## Contact

For more information or to request a fully functional version of this application, please contact the developer.

