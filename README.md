# Smart-Medical-Kiosk-for-Self-Health-Monitoring-in-College-Hostels
A web-based kiosk system enabling hostel students to self-monitor vital health metrics (BP, heart rate, temperature, oxygen levels) via IoT sensors. Features instant health reports, emergency alerts to wardens/doctors, and secure data dashboards. Built with React.js, Node.js/Express, MongoDB, AWS IoT Core, and Raspberry Pi integration.

Smart Medical Kiosk is an innovative web-based self-health monitoring system designed for college hostels. Students can track vital signs (temperature, heart rate, SpO2, BMI) via IoT sensors, view personalized records, request doctor consultations, and trigger emergency alerts—all in one secure, user-friendly interface. Built for EPICS project, inspired by real-world hostel health challenges.

<!-- Replace with your screenshot from the attached image -->
🚀 Features
Real-Time Health Monitoring: Scan vitals with graphical charts (Chart.js) and AI-driven anomaly alerts.

Personalized Health Records: Secure profile with login, history tracking, and data privacy (JWT auth).

Doctor Consultation: Schedule remote consults via forms/chat (expandable to video).

Emergency SOS: Quick alerts to wardens/doctors with one-click contacts.

Admin Dashboard: Trends analytics for hostel staff.

Responsive UI: Mobile-first design with intuitive icons (health status, warnings, SOS).

🏗️ Tech Stack
Frontend	Backend	Database	Tools & Integrations
React.js, HTML/CSS/JS, Chart.js	Node.js/Express	MongoDB	AWS IoT Core (future), Raspberry Pi sensors, JWT, Nodemailer
📱 Pages & Structure
Home: Project intro, features overview, CTA to monitor.

Health Monitoring: Live vitals display, charts, start scan button.

Profile/Records: User data, history, updates (auth required).

Consult Doctor: Appointment forms, chat interface.

Emergency Contacts: SOS button, quick links.

About/Help: FAQs, team, user guide.

See the website wireframe table below for details
Run backend: cd backend && npm start (localhost:5000)
