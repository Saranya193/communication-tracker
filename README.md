# Communication Tracker

## Overview

The **Communication Tracker** is a web application designed to manage and track communication events. It provides distinct interfaces for administrators and users, with features like overdue communication alerts, calendar views, reporting tools, and more. This tool is essential for businesses to efficiently manage communication timelines, organize methods, and track interactions with companies.

---

## Features

### Admin Module
- **Company Overview**: Displays a summary of company-related communications.
- **Manage Company**: Tools to manage company details and communication settings.
- **Manage Communication Methods**: Configure communication channels effectively.
  
### User Module
- **User Dashboard**: Personalized dashboard for users to manage their communications.
- **Notifications**: Real-time updates on communication tasks.
- **Calendar View**: Visual representation of upcoming, due, and overdue tasks.

### Reports
- **Generate Reports**: Ability to generate detailed communication reports based on selected criteria (e.g., communication status, overdue communications, company-specific reports).
- **Export to CSV**: Option to export communication data to a CSV format for further analysis.
- **Analytics**: Visual analytics (charts, graphs) to represent communication data over time, identifying patterns or trends.
  
### Common Features
- **Intuitive Navigation**: Easy-to-use navigation for admins and users.
- **Color-Coded Statuses**: Communication statuses are highlighted using color codes to help quickly identify overdue tasks, upcoming communication, etc.
- **Fully Responsive Interface**: Optimized for both mobile and desktop views.
- **User Profiles**: Customizable user profiles with preferences for notifications and alerts.

---

## Live Demo

You can view the live demo of the Communication Tracker here:

[Live Demo](https://saranya193.github.io/communication-tracker/)

---

## Repository

You can find the source code of this project on GitHub:

[Repository Link](https://github.com/Saranya193/communication-tracker.git)

---

## Installation and Setup

To run this project locally, follow these steps:

### 1. Clone the repository:
git clone https://github.com/Saranya193/communication-tracker.git <br />
cd communication-tracker  <br />

### 2. Install Dependencies:
Run the following command to install the required dependencies:  <br />
npm install  <br />
### 3. Start the Development Server:
Run the following command to start the application:  <br />
npm start <br />
This will start the development server, and the application will be available at http://localhost:3000. <br />
## Technologies Used
### Frontend:
React: For building the user interface.
React Router: For navigation between pages.
Tailwind CSS: For styling and design.
Font Awesome: For icons.
### State Management:
Context API: For managing state across components.
### Additional Tools:
Custom CSS: For additional styling.
Chart.js: For analytics and data visualization.

## Folder Structure
communication-tracker/ <br />
├── public/  
│   ├── index.html  
│   └── ...                 # Static files  
├── src/  
│   ├── components/         # Shared components (e.g., layouts)  
│   ├── context/            # State management   
│   ├── data/               # Mocked Data files  
│   ├── pages/              # Individual pages (e.g.,Reports)   
│   ├── App.css  
│   ├── App.js  
│   ├── index.css  
│   ├── index.js  
│   └── ...                 # Additional files  
├── package.json            # Project dependencies  
├── README.md               # Documentation  
└── ...                     # Additional files  


