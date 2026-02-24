# Conference Event Planner
A streamlined web application designed to help users organize, schedule, and manage conference sessions and attendee registrations. This project focuses on intuitive UX and efficient data handling to simplify the complexities of event coordination.

# Project Purpose
This application was built to demonstrate core frontend logic and state management. It provides a clean interface for users to browse available sessions, add them to a personalized itinerary, and manage event logistics in real-time.

# Tech Stack
Frontend: React.js / JavaScript (ES6+)

Styling: CSS3 / Bootstrap (or Tailwind, if applicable)

State Management: React Hooks (useState, useEffect)

Icons/Assets: FontAwesome / Lucide-React

# Key Features
Session Scheduling: View a full list of conference talks, workshops, and keynotes.

Personalized Agenda: Users can select sessions to build a custom "My Schedule" view.

Conflict Validation: Prevents users from booking two sessions occurring at the same time.

Capacity Tracking: Visual indicators for sessions that are nearing maximum occupancy.

Search & Filter: Quickly find sessions by topic, speaker, or time slot.

# Getting Started
Installation
Clone the repo:

Bash
git clone https://github.com/AustinRJames/conference_event_planner.git
cd conference_event_planner
Install dependencies:

Bash
npm install
Run the application:

Bash
npm start
The app should now be running on http://localhost:3000

# Project Highlights
src/components/: Modularized UI components (Header, SessionCard, Agenda).

src/data/: Mock JSON data representing the conference schedule.

Logic: Implementation of array methods (filter, map, reduce) to dynamically update the user's schedule.

# Skills Demonstrated
Component Composition: Building reusable UI elements.

Conditional Rendering: Displaying different views based on user selection or session availability.

Data Flow: Managing one-way data flow and lifting state to keep the UI in sync.
