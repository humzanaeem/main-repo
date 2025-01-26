# **Design Document**

Welcome to the main repository for **CreatorsFIU** – a virtual marketplace designed exclusively for the FIU community. This repository contains the core source code for both the **frontend** (React.js) and **backend** (Node.js & Express.js), along with essential documentation.

---

## **Table of Contents**
1. [Purpose](#purpose)
2. [Project Structure](#project-structure)


---

## **Purpose**
This repository serves as the core for the CreatorsFIU project. It includes:
- The **frontend** codebase (React.js) for the user-facing interface.
- The **backend** codebase (Node.js & Express.js) for server-side logic and APIs.
- Documentation files for architecture, design plans, and team notes.

---

## **Project Structure**

```plaintext
main-repo/
├── frontend/               # React.js code for the user-facing interface
│   ├── public/             # Static assets like images, favicon
│   ├── src/
│   │   ├── components/     # Reusable React components
│   │   ├── pages/          # Page components like HomePage, LoginPage
│   │   ├── styles/         # CSS files for styling
│   │   ├── App.js          # Main React app entry point
│   │   └── index.js        # Entry point for React rendering
│   └── package.json        # Frontend dependencies and scripts
├── backend/                # Node.js & Express.js code for server and APIs
│   ├── controllers/        # Logic for handling API requests
│   ├── models/             # Database models or schema definitions
│   ├── routes/             # API endpoints
│   ├── config/             # Configuration files like environment variables
│   ├── server.js           # Main entry point for the server
│   └── package.json        # Backend dependencies and scripts
├── docs/                   # Folder for documentation
│   ├── architecture-diagram.png   # System architecture visual
│   ├── design-plan.md             # Platform design details
│   ├── contribution-guide.md      # How to contribute to the project
│   └── team-notes.md              # Meeting notes and progress updates
└── README.md              # Project overview and guidelines
