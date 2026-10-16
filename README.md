# OrbitGuard Workforce OS

**OrbitGuard Workforce OS** is a workforce management and attendance system developed to make employee attendance tracking easier and more reliable. The project combines face recognition, GPS-based location verification, and attendance records in a single web application.

The goal is to reduce manual attendance work and give administrators a convenient way to manage employees and monitor daily attendance.

## Key Features

- **Face Recognition Attendance:** Detects and recognizes faces during the attendance process.
- **Location Verification:** Uses GPS coordinates to check whether an employee is within the permitted office area.
- **Check-In and Check-Out:** Keeps track of employee attendance timings.
- **Role-Based Access:** Provides separate access for administrators and employees.
- **Employee Management:** Allows administrators to maintain employee profiles and workforce records.
- **Attendance History:** Displays attendance records for reviewing previous entries.
- **Attendance Dashboard:** Presents attendance activity and workforce information in an organized interface.
- **Responsive Design:** Supports desktop and mobile screen sizes.
- **Supabase Integration:** Uses Supabase for authentication and database-related functionality.

## Admin Dashboard

The administrator panel is designed to manage day-to-day workforce operations. Depending on the configured permissions, administrators can register employees, manage employee information, configure attendance locations, review attendance records, and manage biometric enrollment.

## Employee Dashboard

Employees can use their dashboard to access their profile, mark attendance through the face scanner, and review their individual check-in and check-out records.

## How Attendance Works

1. The employee opens the attendance scanner.
2. The application detects the face through the camera.
3. The system checks the employee's location against the configured office boundary.
4. After the required validations pass, the application records the attendance.
5. The attendance information becomes available in the relevant dashboard and history views.

The exact flow depends on the biometric verification, location permissions, and backend configuration.

## Technology Stack

**Frontend**
- React.js
- Tailwind CSS
- React Router
- Framer Motion

**Backend**
- Node.js
- Express.js

**Database and Authentication**
- Supabase

**Face Recognition**
- face-api.js
- TensorFlow.js

**Location Services**
- Browser Geolocation API
- Office radius and polygon-based geofence validation

## Installation and Setup

Make sure Node.js and npm are installed on your system.

Clone the repository and open the project directory:

```bash
git clone <your-repository-url>
cd <your-project-folder>
npm install
npm run dev
```

Configure the required environment variables before running the application. These may include the Supabase project URL, the Supabase public client key, and backend configuration values.

For security, never expose a Supabase service-role key or other private credentials in frontend code or a public repository.

## Live Demo

[View the project](https://shreya841.github.io/Smart-attendence-system/)

*Note: Attendance, authentication, and database features require the relevant backend services and configuration to be available.*

## Purpose of the Project

This project explores how face recognition and location verification can be used to improve attendance management. It also provides practical experience with frontend development, backend integration, authentication, database operations, and responsive dashboard design.

## Developer

**Shreya Dwivedi**

Software Engineer
