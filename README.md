<div align="center">
<br /> <img src="https://github.com/user-attachments/assets/1c0131c7-9f2d-4e3b-b47c-9679e76d8f9a" alt="Project Banner"> <br /> <div> <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=black" alt="next.js" /> <img src="https://img.shields.io/badge/-Vapi-white?style=for-the-badge&color=5dfeca" alt="vapi" /> <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" /> <img src="https://img.shields.io/badge/-Firebase-black?style=for-the-badge&logoColor=white&logo=firebase&color=DD2C00" alt="firebase" /> </div> <h3 align="center">Prepwise: An AI-powered job interview preparation platform</h3> <div align="center"> Developed with advanced AI voice and generative technologies to simulate real job interviews and provide instant AI-driven feedback. </div> </div>
📋 Table of Contents

🤖 Introduction

⚙️ Tech Stack

🔋 Features

🤸 Quick Start

🕸️ Snippets

🔗 Assets

🚀 More

<a name="introduction">🤖 Introduction</a>

Prepwise is a full-stack AI-driven platform designed to help users prepare for job interviews through interactive mock interviews using Vapi AI voice agents.
It analyzes user responses in real time and provides personalized feedback using Google Gemini AI.

Built with Next.js for frontend and backend logic, Firebase for authentication and data storage, and styled using Tailwind CSS, this project combines sleek UI/UX with robust AI capabilities.

<a name="tech-stack">⚙️ Tech Stack</a>

Next.js 15

Firebase Authentication & Firestore

Tailwind CSS

Vapi AI (Voice AI Agent)

Google Gemini API

shadcn/ui Components

Zod Validation

<a name="features">🔋 Features</a>

👉 Authentication — Secure login and signup using Firebase.

👉 AI-Powered Interview Creation — Automatically generate interview questions using Gemini based on your selected role, experience level, and tech stack.

👉 Voice AI Interviews — Simulated real-time interviews powered by Vapi Voice Agents.

👉 Instant AI Feedback — After each interview, users receive structured AI feedback with detailed evaluation metrics and improvement suggestions.

👉 Dashboard — Track and manage all previous interviews.

👉 Modern, Responsive UI — Beautiful, intuitive design with dark mode and mobile responsiveness.

👉 Custom Feedback Categories — The system evaluates based on:

Communication Skills

Technical Knowledge

Problem-Solving

Confidence & Role Fit

<a name="quick-start">🤸 Quick Start</a>
Prerequisites

Ensure the following are installed:

Git

Node.js

npm

Clone the Repository
git clone https://github.com/your-username/prepwise.git
cd prepwise

Install Dependencies
npm install

Setup Environment Variables

Create .env.local in the project root:

NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=


Fill these with your credentials from Firebase, Vapi, and Google AI Studio.

Run the Project
npm run dev


Now open http://localhost:3000
 to explore the project.

<a name="snippets">🕸️ Snippets</a>

You can include all the provided code snippets (e.g., globals.css, lib/utils.ts, feedback/page.tsx, etc.) from your project — they remain the same as in your implementation.

<a name="assets">🔗 Assets</a>

All UI assets and icons used in this project can be found in the /public directory or replaced with your custom designs.

<a name="more">🚀 More</a>

This project demonstrates the integration of Voice AI, Generative AI, and Full Stack Development within a single platform.
It is part of my personal portfolio showcasing advanced Next.js development, API integration, and AI workflow design.

If you’d like to connect or collaborate on AI-driven web applications, feel free to reach out.

🧑‍💻 Developed by

John Moshe
Full Stack Developer | AI & Web Enthusiast
