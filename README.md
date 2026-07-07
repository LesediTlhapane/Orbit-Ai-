# OrbitAI — Project Intelligence Platform

## About Aura Tech Intelligence (Pty) Ltd

**Aura Tech Intelligence (Pty) Ltd** is a South African-based AI engineering and consultancy firm specialising in:

- **AI Automation Systems** — Building intelligent automation pipelines for enterprise workflows
- **AI-Integrated Course Design** — Creating professional development programmes that embed AI literacy
- **Intelligent Project Delivery** — Leveraging AI to accelerate software and course development lifecycles
- **Intelligent Process Automation** — Streamlining operations with AI-powered solutions

**OrbitAI** is our flagship project intelligence platform — built to reflect how we work: agile, AI-augmented, and focused on delivering measurable outcomes.

---

## Project Overview

OrbitAI is a full-featured project management and collaboration tool designed specifically for AI engineers, course designers, and automation specialists. It combines:

- 🔷 **Real-time task boards** (Kanban-style)
- 🧠 **AI-powered assistant** (Claude integration for intelligent recommendations)
- 📊 **Interactive project roadmaps** (drag-and-drop timeline)
- 🔐 **Firebase authentication** (Email/Password + Google Sign-In)
- 📱 **Responsive design** with light/dark mode

---

## Key Features

### 1. Project Management
- Create and manage multiple projects
- Each project has its own colour, type, and description
- Real-time task tracking across all projects

### 2. Task Board (Kanban)
- Drag-and-drop cards between phases: *Backlog → Planning → In Progress → Review → Done*
- Filter by: All, Critical, Mine, Type (Courses, Automation, Bugs)
- Priority badges and type tags for quick visual scanning

### 3. AI Assistant (Claude Integration)
- Contextual AI help for:
  - Course outline generation
  - Automation workflow design
  - Backlog prioritisation
  - Acceptance criteria writing
- Quick-chips for common requests
- AI-generated comments on tickets

### 4. Interactive Roadmap
- Visualise project timelines on a 12-month grid
- Drag bars to reposition projects
- Resize bars by dragging the right edge (adjusts project duration)
- Auto-saves changes to Firestore

### 5. Sprints & Backlog
- Automatic grouping: *Backlog*, *Current Sprint*, *Completed*
- Visual progress bars for each sprint
- Click any ticket to open detailed view

### 6. Team Collaboration
- Member directory with role badges
- Real-time notifications for assignments
- Comment threads with AI-insights

### 7. User Experience
- Light / Dark mode toggle
- Toast notifications
- Mobile-responsive interface

---

## Technology Stack

| Category | Technology |
|----------|------------|
| **Frontend** | Vanilla JavaScript, HTML5, CSS3 |
| **Backend** | Firebase (Firestore, Auth) |
| **AI** | Claude API (Anthropic) |
| **Icons** | Tabler Icons |
| **Fonts** | DM Sans, DM Mono (Google Fonts) |
| **Hosting** | Firebase Hosting (recommended) |

---

## Getting Started

### Prerequisites
- Node.js (for local development server)
- Firebase account (free tier works)
- Anthropic API key (for AI features)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-org/orbitai.git
   cd orbitai
