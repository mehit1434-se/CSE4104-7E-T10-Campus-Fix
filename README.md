# Campus Fix: An AI-Powered Smart Campus Issue Reporting and Management System

## Team Information
- **Team Name:** CSE4104-7E-T10
- **Section:** 7E
- **Team Leader:** Mysha Rahaman Mehit (11230321434)
- **Members:** Nafisha Binta Zorz Nishi (11230321340), Tahmid Ahmid Rafi (11230321358)

## Objectives
- Build a web platform where students can submit campus issue reports easily.
- Use AI to automatically categorize complaints and generate short summaries.
- Suggest a priority level (Low / Medium / High) for each complaint.
- Detect similar or duplicate complaints to reduce repeated work.
- Allow responsible personnel to review reports and update their progress.
- Give students transparent status tracking of their submitted reports.
- Provide administrators with a dashboard to monitor and analyze campus issues.

## Features
- Authentication with student, staff and admin roles
- Complaint submission (title, description, location, optional photo)
- AI-based categorization and summarization (Gemini API)
- AI-suggested priority and duplicate complaint detection
- Complaint tracking: Pending, In Progress, Resolved
- Admin / staff dashboard with filters
- Notifications for status updates
- Statistics (most common issues, average resolution time)

## Technology Stack
| Layer | Technology |
|---|---|
| Frontend | React.js |
| Backend | Node.js + Express.js |
| Database | MongoDB (MongoDB Atlas) |
| AI Integration | Google Gemini API |
| Authentication | JWT |
| Version Control | Git + GitHub |
| Deployment | Vercel (frontend), Render (backend) |

## Repository Structure
```
campus-fix/
├── client/        # React frontend
├── server/        # Node.js + Express backend
├── docs/          # Proposal, SRS and diagrams
└── README.md
```
