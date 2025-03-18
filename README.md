# PROJECT-CAREERBRIDGE

## Introduction

Welcome to **PROJECT CAREERBRIDGE**, a comprehensive job-seeking portal designed to connect job seekers with potential employers. This project provides an intuitive user interface to browse job listings, apply for jobs, and interact with an AI-powered chatbot for assistance. The application is structured to ensure a seamless user experience with a well-organized codebase.

## Project Structure

The project is organized into two main directories: `public` and `src`.

### 1. Public Directory

The `public` directory contains static assets such as CVs and PNG images used across the application.

- **public/**
  - **cv/**: Contains sample CVs and resume templates.
  - **images/**: Includes all PNG images used in the application.

### 2. Src Directory

The `src` directory is the heart of the project, containing all the main components and logic of the application. It is further divided into several subdirectories or components:

- **components/**: Contains reusable UI components.
  - **Application/**: Manages the application process, including job applications.
  - **Auth/**: Handles authentication processes such as login and registration.
  - **Chatbot/**: Integrates an AI-powered chatbot for user assistance.
  - **Home/**: Contains components for the homepage.
  - **Job/**: Manages job listings and job details.
  - **Layout/**: Contains layout components such as headers and footers.
  - **PageNotFound/**: Displays a 404 error page for unknown routes.

Each of these directories includes relevant JSX, CSS, and main files necessary for the component's functionality.

## File Structure

```
PROJECT JOBPORTAL-FE/
├── public/
│   ├── cv/
│   │   └── sample-cv.pdf
│   ├── images/
│   │   ├── logo.png
│   │   └── banner.png
├── src/components/
│   ├── Application/
│   │   ├── Application.jsx
│   │   └── Application.css
│   ├── Auth/
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   └── Auth.css
│   ├── Chatbot/
│   │   ├── Chatbot.jsx
│   │   └── Chatbot.css
│   ├── Home/
│   │   ├── Home.jsx
│   │   └── Home.css
│   ├── Job/
│   │   ├── JobList.jsx
│   │   ├── JobDetail.jsx
│   │   └── Job.css
│   ├── Layout/
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   └── Layout.css
│   ├── PageNotFound/
│   │   ├── PageNotFound.jsx
│   │   └── PageNotFound.css
│   ├── index.js
│   ├── App.js
│   └── App.css
└── README.md
```
###  Public Directory

  ### FOR EMPLOYER: email: 'admin@gmail.com', password: 'Password123', role: 'Employer'.
  ### FOR JOB-SEEKER: email: 'tester123@gmail.com', password: 'Password123',  role: 'Job Seeker'


