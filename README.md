**Communication Tracker**
Overview
The Communication Tracker is a web application designed to manage and track communication events. It provides distinct interfaces for administrators and users, with features like overdue communication alerts, calendar views, and reporting tools.

**Features** <br />
Admin Module
Company Overview: Displays a summary of company-related communications.
Manage Company: Tools to manage company details and communication settings.
Manage Communication Methods: Configure communication channels effectively.
User Module
User Dashboard: Personalized dashboard for users to manage their communications.
Notifications: Real-time updates on communication tasks.
Calendar View: Visual representation of upcoming, due, and overdue tasks.
Common Features
Intuitive navigation and user-friendly design.
Color-coded highlights for communication statuses.
Fully responsive interface optimized for mobile and desktop.
Live Demo
https://saranya193.github.io/communication-tracker/

Repository
https://github.com/Saranya193/communication-tracker.git

Installation and Setup
1.Clone the repository:
git clone <repository-url>  
cd communication-tracker  
2.Install dependencies:
npm install  
3.Start the development server:
npm start  
Technologies Used
Frontend: React, React Router, Tailwind CSS
State Management: Context API
Icons: Font Awesome
Styling: Custom CSS and Tailwind
Folder Structure:
communication-tracker/
├── public/  
│   ├── index.html  
│   └── ...                 # Additional files  
├── src/  
│   ├── components/         # Shared components (layouts)  
│   │   ├── AdminLayout.js  
│   │   ├── UserLayout.js  
│   ├── context/            # Company state management  
│   ├── data/               # Mocked Data  
│   ├── pages/              # Individual page components  
│   ├── App.css  
│   ├── App.js  
│   ├── App.test.js  
│   ├── index.css  
│   ├── index.js  
│   └── ...                 # Additional files  
├── package.json            # Project dependencies  
├── README.md               # Documentation  
└── ...                     # Additional files  

Additional Notes
All external dependencies are documented in package.json.
The application is fully tested for responsiveness and cross-browser compatibility.


