# AI Smart Study Planner

An AI powered weekly study schedule generator for university students.

**Course:** CSE 4104 – Software Development III
**Team:** CSE4104-7E-T06
**Section:** 7E
**Course Teacher:** Md. Riaz Mahmud, Assistant Professor, Department of CSE, NUBTK

## Team Members

| Name | Student ID | Role |
|---|---|---|
| Sanjed Ahmed Ratul | 11230321582 | Team Leader |
| Asafur Rahman Sifat | 11230321367 | Member |
| Sk. Md. Habibullah | 11230321381 | Member |

## Project Description

AI Smart Study Planner is a web application that helps university students organize their subjects, assignments and exam dates. Using Google Gemini AI, it creates a personalized 7-day study plan based on deadlines, subject difficulty, estimated hours and the student's available study time. The plan also includes short explanations.

## Features

- User registration, login and logout
- Add, edit and delete subjects with difficulty level
- Add, edit and delete assignments and exams
- Dashboard with upcoming deadlines and progress
- AI generated 7-day study plan with explanations
- Mark study sessions as completed
- Save, view and delete study plans
- Admin can view and manage users

## Technology Used

| Part | Technology |
|---|---|
| Frontend | React.js, CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| AI Service | Google Gemini API |
| Deployment | Vercel (frontend), Render (backend) |
| Tools | Git, GitHub, VS Code |

## System Architecture

```
Frontend (React.js)
        ↓
Backend API (Node.js + Express.js)
        ↓
Database (MongoDB)
        ↓
AI Service (Google Gemini API)
```

## Repository Structure

```
frontend/        Frontend code (React.js)
backend/         Backend code (Node.js + Express.js)
database/        Database files
documentation/   Proposal, SRS, System Design, UI Design, User Flow and Development Plan documents
design/          Wireframes (UI screens) and User Flow diagram
diagrams/        Architecture, ER, Use Case and Activity diagrams
README.md
```

## Project Setup Instructions

1. Clone the repository
   ```
   git clone <repository-link>
   ```
2. Run the backend
   ```
   cd backend
   npm install
   npm start
   ```
3. Run the frontend
   ```
   cd frontend
   npm install
   npm run dev
   ```
4. Create a `.env` file inside `backend/` and add:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   GEMINI_API_KEY=your_gemini_api_key
   ```

## Development Plan

| Week | Work | Responsible |
|---|---|---|
| Week 06 | Backend Development (login, register, subjects, tasks APIs) and Database setup | All members |
| Week 07 | Frontend Development (all pages in React.js) | Sifat |
| Week 08 | AI Integration (Gemini AI study plan) | Ratul |
| Week 09 | Feature Completion (dashboard, saved plans, admin panel) | All members |
| Week 10 | Testing and Debugging | Habib |
| Week 11 | Deployment | Ratul |

## Team Task Distribution

| Member | Responsibilities |
|---|---|
| Sanjed Ahmed Ratul (Team Leader) | Backend Development, AI Integration, Deployment |
| Asafur Rahman Sifat | Backend Development, Frontend Development, UI Design |
| Sk. Md. Habibullah | Backend Development, Database Management, Testing, Documentation |

## Documents

| Week | Document |
|---|---|
| Week 02 | `documentation/CSE4104-7E-T06_Proposal.pdf` |
| Week 03 | `documentation/CSE4104-7E-T06_SRS.pdf` |
| Week 04 | `documentation/CSE4104-7E-T06_SystemDesign.pdf` |
| Week 05 | `documentation/CSE4104-7E-T06_UIDesign.pdf` |
| Week 05 | `documentation/CSE4104-7E-T06_UserFlow.pdf` |
| Week 05 | `documentation/CSE4104-7E-T06_DevelopmentPlan.pdf` |

## Diagrams

- `diagrams/CSE4104-7E-T06_ArchitectureDiagram.pdf`
- `diagrams/CSE4104-7E-T06_ERDiagram.pdf`
- `diagrams/CSE4104-7E-T06_UseCaseDiagram.pdf`
- `diagrams/CSE4104-7E-T06_ActivityDiagram.pdf`

## UI Design

- Wireframes of all main screens are in the `design/` folder
- Prototype: https://claude.ai/artifact/6uugjGhW3JBDizkDRW4YLb

## Progress

| Week | Task | Status |
|---|---|---|
| Week 01 | Team formation and project idea | Done |
| Week 02 | Project proposal and GitHub repository | Done |
| Week 03 | Software Requirement Specification (SRS) | Done |
| Week 04 | System Design and Software Architecture | Done |
| Week 05 | UI/UX Design and Development Planning | Done |
