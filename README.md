# **Design Document**

Welcome to the main repository for **CreatorsFIU** – a virtual marketplace designed exclusively for the FIU community. This repository contains the core source code for both the **frontend** (React.js) and **backend** (Node.js & Express.js), along with essential documentation.

---

## **Table of Contents**
1. [Purpose](#purpose)
2. [Project Structure](#project-structure)
3. [Docs](#docs)


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

```
## **Docs**

The `docs/` folder contains essential documentation for the CreatorsFIU project:

- **`architecture-diagram.png`**  
  A visual representation of the system architecture, showing the interaction between the frontend, backend, database, and external APIs.

- **`design-plan.md`**  
  A detailed design document outlining the platform's layout, user flows, and technical specifications.

- **`contribution-guide.md`**  
  A step-by-step guide for contributors, covering how to fork the repo, create branches, and submit pull requests.

- **`team-notes.md`**  
  Meeting notes and updates about the project’s progress, team discussions, and decisions.

To access these documents:
1. Navigate to the `docs/` folder in the repository.
2. Open the respective file to view or edit.
3. For any updates, ensure proper version control by committing your changes.

### **Quick Links**
- [Architecture Diagram](docs/architecture-diagram.png)
- [Design Plan](docs/design-plan.md)
- [Contribution Guide](docs/contribution-guide.md)
- [Team Notes](docs/team-notes.md)

---

For additional resources and up-to-date planning, refer to our [Notion page](https://www.notion.so/Getting-Started-187f2506fdf380a3a55ace9ca6915dde) for team collaboration, project management, and detailed instructions.

