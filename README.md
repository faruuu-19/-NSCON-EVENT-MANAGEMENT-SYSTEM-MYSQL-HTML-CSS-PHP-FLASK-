# NASCON Event Management System

This project is a full-featured database-driven web application to manage the annual (NASCON). It automates registration, event scheduling, sponsorship handling, accommodations, judging, and analytics.

## Features

- Role-based access (Admin, Organizer, Participant, Sponsor, Judge)
- Event creation and multi-round scheduling
- Venue conflict detection using SQL constraints
- Participant and team registration
- Sponsorship package management
- Accommodation booking and auto-allocation
- Payment tracking (participants and sponsors)
- Score input and leaderboard for judges
- Reports: Event stats, revenue, accommodation, demographics

## Technologies

- **Frontend:** HTML, CSS, JavaScript
- **Backend:**  Node.js (choose your stack)
- **Database:** MySQL / PostgreSQL
- **Authentication:** Session or JWT-based
- **Styling:** Bootstrap or Tailwind CSS

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/nascon-event-management.git
cd nascon-event-management

# Setup environment (example for Node.js)
npm install
cp .env.example .env

# Initialize the database
# Run provided SQL scripts in /database/setup.sql

# Start the server
npm run start
