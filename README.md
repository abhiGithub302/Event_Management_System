# EventEase

EventEase is a comprehensive event management platform built using Next.js, designed to simplify event creation, management, and real-time attendee engagement. It offers seamless user experiences for attendees, organizers, and administrators with real-time updates and efficient workflows.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

EventEase streamlines the process of organizing and participating in events. Attendees can register for events, receive real-time updates, and interact with organizers. Event organizers can create, manage, and monitor events, while administrators oversee all activities to ensure smooth operations.

## Features

### Frontend

1. **User Authentication:**
   - Allow users to register and log in.
   - Option for "Guest Login" to access limited features.

2. **Event Dashboard:**
   - Display a list of upcoming and past events.
   - Include filters for categories and dates.

3. **Event Creation:**
   - Provide a form to create an event with fields like event name, description, date/time, and more.

4. **Real-Time Attendee List:**
   - Show the number of attendees for each event in real-time.

5. **Responsive Design:**
   - Ensure the platform works seamlessly on all devices.

### Backend

1. **Authentication API:**
   - Use JWT for secure authentication.

2. **Event Management API:**
   - Provide CRUD operations for events with ownership restrictions.

3. **Real-Time Updates:**
   - Use WebSockets for real-time updates.

4. **Database:**
   - Efficiently store event and user data.

## Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Real-time Communication:** WebSockets
- **Deployment:** Vercel (frontend) and Render (backend)

## Getting Started

To set up the project locally, follow these steps:

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB database (local or cloud-based).
- Configure environment variables for email notifications and real-time updates.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/abhiGithub302/Event_Management_System.git
2.Navigate to the project directory:
  ```bash
  cd Event_Management_System
3.Install dependencies:
  ```bash
  npm install