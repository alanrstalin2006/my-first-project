# CampusPulse — Campus IT Helpdesk & Issue Tracker

A portfolio-ready Information Technology project using **Node.js, Express, REST APIs, and vanilla JavaScript**.

CampusPulse lets students report campus/IT issues, search and filter tickets, and track progress through a status workflow.

## Features
- Create tickets with category, description, and location
- Search and filter reports
- Update status: Open → In Progress → Resolved
- REST API with validation and HTTP status codes
- JSON-file persistence (no database setup needed)
- Responsive dashboard, demo data, Helmet security headers

## Run locally
Requires Node.js 18+.

```bash
npm install
npm run dev
```
Open http://localhost:3000

## API
| Method | Endpoint | Purpose |
|---|---|---|
| GET | /api/tickets?q=&status= | Search/list |
| POST | /api/tickets | Create ticket |
| PATCH | /api/tickets/:id | Update status |
| GET | /api/health | Health check |

## Roadmap
- [ ] MySQL/PostgreSQL database
- [ ] Authentication and role-based access
- [ ] File attachments and notifications
- [ ] Analytics and CSV export
- [ ] Deployment

## Learning outcomes
REST, middleware, input validation, asynchronous file I/O, Fetch API, DOM rendering, and application security fundamentals.
