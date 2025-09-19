# VIT ProjectMate

VIT ProjectMate is a web-based project portal designed specifically for VIT University students to simplify the process of team formation and project collaboration. Built with a modern full-stack JavaScript architecture (Node.js, Express.js, MongoDB, EJS), it brings streamlined workflows and rich profile features to inspire innovation and professional growth within the university community.

# Key Features

- Student registration/login, profile creation, and editing

- **Team management:** Create, join, accept/reject project teams

- **Project dashboard:** Browse, filter, apply to projects

- Notifications for application, acceptance, and status changes

- Secure authentication (Passport.js) and encrypted password storage (bcrypt)

- File uploads for richer profiles (Multer)

- Real-time project and status updates

- Responsive and accessible web UI

# Tech Stack

- **Frontend:** HTML, CSS, JavaScript, EJS

- **Backend:** Node.js, Express.js

- **Database:** MongoDB (NoSQL)

- **Authentication:** Passport.js, bcrypt

- **File Handling:** Multer

- **Deployment:** Local server or any Node-compatible cloud provider

# Installation

**1. Clone the repository**

- git clone https://github.com/aarushichaddha/VIT_ProjectMate.git
cd VIT_ProjectMate

**2. Install dependencies**

- npm install

**3. Configure environment variables**

- Create a .env file for MongoDB URI, session secrets, etc.

**4. Run MongoDB**

- Ensure MongoDB is installed and running on your system (or use a cloud MongoDB Atlas cluster).

**5. Start the server**

- npm start
  
The application will run on http://localhost:4000 by default.

# Usage

- Register as a new student or login as an existing user

- Create a project or apply to join ongoing projects

- Manage your profile and track your project/team status

- Project owners can accept/reject applicants in real time

- Receive notifications (visual/text) for project/application status changes

# Screenshots
**Landing Page:** The main landing page that introduces the VIT Project Portal and provides primary navigation to either explore existing projects or create a new one.
<img width="1919" height="877" alt="Screenshot 2025-09-18 231057" src="https://github.com/user-attachments/assets/ba7d910a-f822-4379-8369-c55185090968" />

**About Page**: Details the mission and vision of VIT ProjectMate, explaining its purpose as a collaborative platform for students.
<img width="1919" height="879" alt="Screenshot 2025-09-18 231114" src="https://github.com/user-attachments/assets/394d8355-613f-49c6-8216-3db1188c0e7b" />

**Contact Page:** Provides a form for users to send messages and also lists direct contact information, including email, phone, and GitHub.
<img width="1917" height="869" alt="Screenshot 2025-09-18 231211" src="https://github.com/user-attachments/assets/5c6987ea-f73b-467f-911c-6fb34c0a8790" />

**Gallery Page:** A visual showcase of different project ideas, hackathons, and technologies to inspire users.
<img width="1919" height="880" alt="Screenshot 2025-09-18 231230" src="https://github.com/user-attachments/assets/007ca5af-e1ef-4a88-ba7c-5dddf4141d1f" />

**User Profile Page:** The user's public dashboard, displaying their information, skills, and providing quick links to edit their profile or manage their projects and applications.
<img width="1919" height="855" alt="Screenshot 2025-09-18 231246" src="https://github.com/user-attachments/assets/9a881575-206f-4605-8b1e-7d60ac3d7ec6" />

**Edit Profile Page:** A form that allows users to update their personal information, including their name, institute, profile picture, and links to professional networks.
<img width="1919" height="914" alt="Screenshot 2025-09-18 231359" src="https://github.com/user-attachments/assets/73ea72d4-e3cb-4e17-96f3-3488e0808144" />

**My Applications Page:** A personal dashboard for users to view and track the status of the applications they have submitted to join projects.
<img width="1913" height="878" alt="Screenshot 2025-09-18 231255" src="https://github.com/user-attachments/assets/8733e2c0-8c97-488e-bcbd-c72ae4f93616" />

**Your Projects Page:** A management area where users can view, edit, or delete the projects they have created.
<img width="1919" height="876" alt="Screenshot 2025-09-18 231307" src="https://github.com/user-attachments/assets/074b1956-075c-4e3a-9b58-fbd29ac03244" />
<img width="1917" height="877" alt="Screenshot 2025-09-18 231421" src="https://github.com/user-attachments/assets/b8e89daf-9d50-4bb4-bfcf-0fde7231ab03" />

**Incoming Requests Page:** A dashboard for project owners to see a list of students who have applied to join their projects, allowing them to manage team formation.
<img width="1919" height="874" alt="Screenshot 2025-09-18 231319" src="https://github.com/user-attachments/assets/8c1400fb-9c1b-4618-ae6d-3e5f841a8db0" />













# Architecture

- MVC Pattern: The application is modularized into Model-View-Controller layers for maintainability.

- RESTful Routing: Follows REST principles for project, user, and team actions.

# Hardware & Software Requirements

- 1GHz or faster processor, 1-2GB+ RAM, 4-6GB+ disk space

- Node.js v11+, MongoDB v4.4+, modern desktop browser

# Deployment

- Can be run locally or deployed to cloud-based Node servers (Heroku, AWS, etc.)

- Static assets and file uploads are handled securely
