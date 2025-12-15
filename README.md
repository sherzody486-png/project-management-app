# Project Management Intelligence System

A professional internal project management & intelligence platform with AI-powered insights, real-time KPI tracking, and advanced analytics.

## 🎯 Features

### Core Features
- **Dashboard & Analytics**: Real-time KPI tracking with visual indicators
- **Project Management**: Create projects with multiple indicators
- **Indicator Tracking**: Daily/weekly/monthly update frequency
- **Role-Based Access**: Admin and Project Manager roles
- **AI Assistant**: Gemini-powered project insights
- **Audit Trail**: Complete change history

### Advanced Features
- Automatic progress calculation
- Anomaly detection in trends
- Predictive analytics
- AI-generated reports
- Alert notifications
- Admin analytics
- PDF/Excel exports

## 📋 Tech Stack

**Frontend**: React 18, TypeScript, Tailwind CSS, Redux  
**Backend**: Firebase, Cloud Firestore, Cloud Functions  
**AI**: Google Gemini API

## 🚀 Quick Start

```bash
git clone https://github.com/sherzody486-png/project-management-app.git
cd project-management-app

# Frontend
cd frontend && npm install && npm run dev

# Backend (new terminal)
cd backend && npm install && firebase emulators:start
```

## 📚 Documentation

- [Architecture](./docs/ARCHITECTURE.md)
- [Database Schema](./docs/DATABASE.md)
- [AI Integration](./docs/AI_PROMPTS.md)
- [Deployment](./docs/DEPLOYMENT.md)
- [Local Setup](./docs/SETUP.md)

## 🔐 Security

- Firebase Authentication
- Role-based access control
- Firestore security rules
- End-to-end encryption
- Audit trail

## 📊 Data Model

| Collection | Purpose |
|-----------|----------|
| users | User profiles & roles |
| projects | Project definitions |
| indicators | KPI tracking |
| indicatorUpdates | Audit trail |
| notifications | User alerts |
| reports | Generated reports |

---
Built with ❤️ for intelligent project management