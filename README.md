# iRacing Monarch Application

A professional, modular web platform for iRacing enthusiasts and teams—enabling detailed tracking of iRating progress, yearly stats, race results, and a calendar of events, plus team dashboards and personal analytics. Built on FastAPI (Python) and React (JavaScript), containerized for reliability, and designed for both local and cloud deployment.

---

## Features

- **Dashboard:**  
  iRating progression visualized for all licenses, yearly stats, recent race results, and an interactive event calendar.
- **Your Races:**  
  Browse, filter, and review your historical iRacing performance.
- **Your Team:**  
  Team management features to view and plan joint races (future extensibility).
- **Modern, Responsive UI:**  
  Built using React & Material-UI with live charts (Chart.js) and dashboard widgets.
- **FastAPI Backend:**  
  REST API, JWT/OAuth2 authentication, and PostgreSQL with async endpoints.
- **Containerized:**  
  One-command launch for full stack using Docker Compose.
- **Real-Time Ready:**  
  Easily supports updates and live race/event data (future extensibility).

---

## Tech Stack

| Layer      | Technology                          |
|:-----------|:------------------------------------|
| Frontend   | React, Material-UI, Chart.js        |
| API/Auth   | Axios, React Query, Redux Toolkit   |
| Backend    | FastAPI, SQLAlchemy, Alembic        |
| Database   | PostgreSQL                          |
| Auth       | JWT, OAuth2, Passlib (bcrypt)       |
| Caching    | Redis                               |
| Task Queue | Celery                              |
| DevOps     | Docker & Docker Compose             |

---

## Quick Start

### Prerequisites

- [Docker](https://www.docker.com/products/docker-desktop)
- [Python 3.11+](https://www.python.org/downloads/)
- [Node.js 18+](https://nodejs.org/en/download/)

### 1. Clone the Repository

