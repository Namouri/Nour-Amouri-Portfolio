# Nour Amouri Portfolio💻

This is the personal portfolio website of **Nour Amouri**, showcasing skills, projects, experience, and a contact form with email functionality.

<img width="500" height="393" alt="portfolioPic" src="https://github.com/user-attachments/assets/18b3371b-da51-4d79-bbc9-4a98d8a9f69f" />

The project has two main parts:

1. **Frontend** – built with React, Vite, and TypeScript.
2. **Backend** – built with Node.js and Express, handling the contact form submissions securely.

---

## Features

- **Hero Section**: Catchy introduction with animated buttons for projects and resume.  
- **About Section**: Expandable experience cards showing detailed professional experience.  
- **Projects Section**: Displays portfolio projects with images and descriptions.  
- **Skills Section**: Interactive skill cards.  
- **Contact Form**: Users can send messages via email. Backend is connected using Nodemailer or SendGrid.  
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices.  
- **Expandable Experience Cards**: Cards show hints to tap/click and reveal more content without overlapping sections.

---

## Live Demo

- https://nouramouri.vercel.app  

---

## Tech Stack

- **Frontend**: React, Vite, TypeScript, CSS3, HTML5  
- **Backend**: Node.js, Express, Nodemailer / SendGrid  
- **Hosting**: Vercel (frontend), Render (backend)  
- **Environment Variables**: Used for API URLs and email credentials (via `.env` or Vercel/Render secrets)

---

## Setup Instructions


```bash
###frontend
git clone https://github.com/Namouri/portfolio-frontend.git
cd portfolio-frontend
npm install
npm run dev

### Backend
git clone https://github.com/Namouri/portfolio-backend.git
cd portfolio-backend
npm install
npm start
