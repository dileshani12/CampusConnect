# CampusConnect

A full-stack campus platform designed to improve student life by bringing together job opportunities, student marketplaces, accommodation services, study management tools, and AI-powered career guidance.

## Project Overview

CampusConnect is a university-focused web application that provides students with a centralized platform to access academic and campus-related services. It helps students discover opportunities, buy and sell academic items, connect with others, manage their studies, and access career guidance.

## Key Features

- **Job Portal** – Browse internships and part-time opportunities, apply with CV uploads, and track application status.
- **Admin Hiring Console** – Manage job applications, review candidates, and approve or reject applications.
- **Student Dashboard** – Access quick actions, events, trending content, and job opportunities.
- **AI Career Counselor** – Get career guidance through an AI-powered chat using Google Gemini API.
- **Campus Marketplace** – Buy and sell academic-related items within the student community.
- **Small Business Stores** – Provides small business owners with an opportunity to create stores and showcase their products for sale.
- **Accommodation & Chat** – Explore accommodation listings and communicate with property owners.
- **Time Management** – Manage assignments, study sessions, and examinations.
- **Q&A Forum** – Share questions and help other students through a category-based discussion platform.

## My Contribution – Campus Marketplace

I contributed to the development of the Campus Marketplace component, focusing on providing a platform for students to buy and sell academic-related items.

My responsibilities included:

- Implementing item creation and listing functionality.
- Developing item update and deletion functionality.
- Implementing item search functionality.
- Developing a marketplace experience for buying and selling academic-related products.
- Creating a dedicated store feature to support small business owners in showcasing and selling their products.

## Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React 18, Vite, React Router, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| AI Integration | Google Gemini API |
| Other Tools | Axios, Socket.io, Multer, Framer Motion |

## Repository Structure

- `frontend/` – React frontend application.
- `backend/` – Node.js and Express backend API.

## Prerequisites

- Node.js 18 or later
- MongoDB (local or MongoDB Atlas)
- Google Gemini API key (for AI career counselor functionality)

## Environment Variables

### Backend

Create a `.env` file inside the `backend/` directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

### Frontend

Create a `.env` or `.env.local` file inside the `frontend/` directory if required.

```env
VITE_API_URL=http://localhost:5000
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/dileshani12/CampusConnect.git
cd CampusConnect
```

### 2. Set Up the Backend

```bash
cd backend
npm install
node server.js
```

### 3. Set Up the Frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL provided by Vite in your browser.

## Project Type

University Group Project – Third Year

This repository is a fork of the original team project repository by Anuk Cooray.

Original Repository: https://github.com/Anuk-Cooray/CampusConnect

