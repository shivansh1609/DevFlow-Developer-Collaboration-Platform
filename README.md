<div align="center">

# 🚀 Technestia

###  Modern Developer Collaboration Platform

Build • Collaborate • Innovate

<p align="center">

<a href="https://technestia.onrender.com">
<img src="https://img.shields.io/badge/🌐_Live_Demo-Visit_Now-blue?style=for-the-badge">
</a>

</p>

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?logo=socket.io)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss)

</div>

---

# 📖 About

Technestia is a **full-stack developer collaboration platform** that enables developers to create projects, collaborate with teams, communicate in real time, track milestones, receive notifications, and manage project workflows from a unified workspace.

Built with **Next.js App Router, PostgreSQL, Prisma, NextAuth, Socket.IO**, and a custom **Node.js server**, Technestia delivers a modern real-time collaboration experience.

---

# 🌐 Live Demo

### 🔗 https://technestia.onrender.com/

---

# ⚡ Tech Stack

| Category | Technologies |
|------------|------------------------------------------------|
| **Frontend** | Next.js 15, React 19, TypeScript, Tailwind CSS, Radix UI, SWR |
| **Backend** | Next.js Route Handlers, Custom Node.js Server |
| **Database** | PostgreSQL + Prisma ORM |
| **Authentication** | NextAuth (Credentials, Google, GitHub) |
| **Realtime** | Socket.IO |
| **Media** | Cloudinary |
| **Email** | Resend |

---

# ✨ Core Features

## 🔐 Authentication & Security

- Email OTP Verification
- Credentials Login
- Google OAuth
- GitHub OAuth
- Forgot Password
- Reset Password
- Secure JWT Session Management

---

## 👤 User Profiles

- Public Developer Profiles
- Profile Editing
- Social Links
- Password Management
- Account Deletion

---

## 📂 Project Management

- Create Projects
- Update Project Information
- Public / Private Visibility
- Technology Tags
- Screenshots
- Social Links
- Delete Projects

---

## 🤝 Collaboration

- Invite Developers
- Join Requests
- Accept / Reject Invitations
- Remove Collaborators
- Leave Projects
- Permission Levels
  - LIMITED
  - FULL

---

## 🎯 Milestone Management

- Create Milestones
- Update Progress
- Approval Workflow
- Proof URL
- Visibility Controls

Status Support

- Not Started
- In Progress
- Completed
- Skipped

---

## 💬 Real-Time Chat

- Direct Messages
- Group Conversations
- Typing Indicators
- Online Presence
- Read Receipts
- Message Editing
- Message Deletion
- Unread Counters

---

## 🔔 Notifications & Activity Feed

- Real-time Notifications
- Activity Timeline
- Mark Read
- Mark All Read
- Multi-device Synchronization

---

## ⭐ Feedback System

- Ratings
- Comments
- Update Feedback
- Delete Feedback
- Emoji Reactions

---

## 🔍 Search

Search across

- Users
- Projects
- Milestones

---

# ⚡ Realtime Events

| Event | Purpose |
|--------|---------|
| activity:new | New Activity Feed |
| notification:new | Push Notification |
| notification:read-sync | Read Synchronization |
| collab:sync | Collaboration Updates |
| chat:room:sync | Room Synchronization |
| chat:message:new | New Message |
| chat:message:edit | Edit Message |
| chat:message:delete | Delete Message |
| chat:typing:start | Typing Started |
| chat:typing:stop | Typing Stopped |
| chat:message:seen | Seen Status |
| chat:presence:state | User Presence |

---

# 🏗 Architecture

```
                   Next.js Frontend
                          │
                          │
                 Route Handlers (API)
                          │
        ┌─────────────────┴─────────────────┐
        │                                   │
 PostgreSQL + Prisma                 Socket.IO Server
        │                                   │
        └─────────────────┬─────────────────┘
                          │
                  Connected Clients
```

---

# 📁 Project Structure

```
src
│
├── app
│   ├── api
│   ├── dashboard
│   └── project
│
├── components
├── hooks
├── lib
├── prisma
├── utils
│
server.js
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/Bhivanshu45/technestia.git
```

## Install Dependencies

```bash
npm install
```

## Database Migration

```bash
npx prisma migrate dev
```

## Start Development Server

```bash
npm run dev
```

---

# 🔑 Environment Variables

```env
DATABASE_URL=

NEXTAUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=

NEXT_PUBLIC_SOCKET_URL=
SOCKET_CORS_ORIGIN=

NEXT_PUBLIC_API_BASE_URL=

RESET_PASSWORD_PAGE_URL=

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

RESEND_API_KEY=
```

---

# 📌 Roadmap

## ✅ Completed

- Authentication
- Project Management
- Collaboration
- Milestones
- Real-Time Chat
- Notifications
- Activity Feed
- Search
- Feedback System

---

## 🚧 Upcoming

- 🤖 AI Milestone Generator
- 🤖 AI Sprint Planner
- 🤖 AI Project Health Analysis
- 🤖 AI Feedback Summary
- Redis Caching
- BullMQ Workers
- Docker Support
- API Rate Limiting
- Monitoring
- Automated Testing

---

# ⚠ Current Limitations

- Milestone Assignment Model
- Advanced Search Pagination
- Automated Testing
- API Rate Limiting
- Centralized Monitoring

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

<div align="center">

### ⭐ If you like this project, don't forget to star the repository.

Made with ❤️ by **Shivanshu Pandey**

</div>
