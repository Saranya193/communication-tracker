**Communication Tracker**
Overview
The Communication Tracker is a web application designed to manage and track communication events. It provides distinct interfaces for administrators and users, with features like overdue communication alerts, calendar views, and reporting tools.

**Features** <br />
**Admin Module** <br />
Company Overview: Displays a summary of company-related communications.<br />
Manage Company: Tools to manage company details and communication settings.<br />
Manage Communication Methods: Configure communication channels effectively.<br />
**User Module** <br />
User Dashboard: Personalized dashboard for users to manage their communications.<br />
Notifications: Real-time updates on communication tasks.<br />
Calendar View: Visual representation of upcoming, due, and overdue tasks.<br />
**Common Features**
Intuitive navigation and user-friendly design.<br />
Color-coded highlights for communication statuses.<br />
Fully responsive interface optimized for mobile and desktop.<br />
Live Demo <br />
https://saranya193.github.io/communication-tracker/<br />

Repository<br />
https://github.com/Saranya193/communication-tracker.git<br />

**Installation and Setup** <br />
1.Clone the repository:<br />
git clone <repository-url>  <br />
cd communication-tracker  <br />
2.Install dependencies:<br />
npm install  <br />
3.Start the development server:<br />
npm start  <br />
**Technologies Used** <br />
Frontend: React, React Router, Tailwind CSS<br />
State Management: Context API<br />
Icons: Font Awesome<br />
Styling: Custom CSS and Tailwind<br />
**Folder Structure:**<br />
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

**Additional Notes**
All external dependencies are documented in package.json.
The application is fully tested for responsiveness and cross-browser compatibility.


