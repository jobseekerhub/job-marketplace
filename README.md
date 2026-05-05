# JobSeekerHub - Job Marketplace Platform

A comprehensive, fully functional job marketplace platform connecting job seekers with employers.

## 🎯 Features

### For Job Seekers
- Browse and search job opportunities
- Advanced filtering by location, salary, industry, experience
- Create professional profiles
- Track job applications
- Save favorite jobs

### For Employers
- Post job listings
- Manage applications
- Review candidate profiles
- Shortlist candidates

## 🛠 Tech Stack

### Frontend
- React 18 with TypeScript
- Tailwind CSS
- Redux Toolkit
- Vite

### Backend
- Node.js & Express.js
- MongoDB
- JWT Authentication

### DevOps
- Docker & Docker Compose
- GitHub Actions ready

## 🚀 Quick Start

### Using Docker
```bash
git clone https://github.com/jobseekerhub/job-marketplace.git
cd job-marketplace
docker-compose up -d
```

Access:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000/api

### Manual Setup
```bash
git clone https://github.com/jobseekerhub/job-marketplace.git
cd job-marketplace
npm install
npm run dev
```

## 📁 Project Structure

```
job-marketplace/
├── frontend/          # React application
├── backend/           # Node.js API
├── docker-compose.yml
└── package.json
```

## 📦 Available Scripts

```bash
npm run dev           # Start both services
npm run build         # Build production
npm run test          # Run tests
```

## 📄 License

MIT License
