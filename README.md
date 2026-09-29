# GJU Clubs Portal

### A unified digital platform for student clubs, activities, and campus engagement.

The **GJU Clubs Portal** is a student-led project designed to explore how club activities and student engagement at the German Jordanian University can be brought together within one digital platform.

The platform connects students, club teams, and university stakeholders through a centralized experience for discovering activities, managing initiatives, coordinating opportunities, and tracking engagement.

> This is a student-developed project and is not an official German Jordanian University platform.

---

## The Problem

Student clubs play an important role in university life, but managing activities across different clubs can involve fragmented communication, manual processes, and information spread across multiple channels.

Students may also find it difficult to discover opportunities, activities, events, and ways to become involved across campus.

The GJU Clubs Portal explores how these experiences can be brought together through a **single, structured digital platform**.

---

## Our Solution

We designed and developed a **full-stack web platform** that brings student-club activities and engagement into one centralized experience.

The platform supports different types of users and provides dedicated experiences for students, club teams, and administrative roles.

The project explores areas including:

- Student club and activity management
- Events and initiatives
- Volunteer opportunities and applications
- Student participation and engagement
- Attendance and feedback
- Club performance and activity insights
- Role-based experiences
- English and Arabic accessibility

The goal is to make campus involvement easier to **discover, organize, manage, and understand**.

---

## Tech Stack

The GJU Clubs Portal is built as a full-stack TypeScript application.

### Frontend

- **React 18**
- **TypeScript**
- **Vite**
- **Tailwind CSS**
- **Radix UI / shadcn/ui**
- **TanStack Query**
- **React Hook Form**
- **Wouter**
- **Recharts**
- **Lucide React**

### Backend

- **Node.js**
- **Express.js**
- **TypeScript**
- **REST APIs**
- **Zod** for validation

### Data Layer

- **Drizzle ORM**
- **PostgreSQL-ready architecture**
- **Neon Database support**
- Shared TypeScript schemas across frontend and backend

### Internationalization

- **i18next**
- **react-i18next**
- English and Arabic support
- Right-to-left (RTL) interface support

### Development & Tooling

- **Git & GitHub** — version control and collaboration
- **Replit** — development and prototyping
- **Vite** — frontend development and builds
- **esbuild** — server bundling
- **TypeScript** — end-to-end type safety

---

## High-Level Architecture

The project follows a full-stack architecture with shared TypeScript models across the application.

```text
                     ┌─────────────────────┐
                     │        Users        │
                     │                     │
                     │ Students • Clubs •  │
                     │ Administrative Roles│
                     └──────────┬──────────┘
                                │
                                ▼
                     ┌─────────────────────┐
                     │    React Web App    │
                     │                     │
                     │   TypeScript + UI   │
                     └──────────┬──────────┘
                                │
                                ▼
                     ┌─────────────────────┐
                     │      REST API       │
                     │                     │
                     │  Node.js + Express  │
                     └──────────┬──────────┘
                                │
                                ▼
                     ┌─────────────────────┐
                     │     Data Layer      │
                     │                     │
                     │ Drizzle + PostgreSQL│
                     └─────────────────────┘
```

The architecture uses shared schemas and TypeScript types between the frontend and backend to maintain consistency across the application.

---

## Key Engineering Areas

Development of the portal involved work across both **product design and full-stack engineering**, including:

- Designing role-based user experiences
- Building reusable frontend components
- Developing responsive dashboards and interfaces
- Creating REST API endpoints and application services
- Modeling structured application data
- Implementing forms and schema-based validation
- Building data visualization components
- Supporting English and Arabic interfaces
- Implementing RTL layouts for Arabic
- Designing accessible and responsive user experiences
- Connecting frontend experiences with backend services

---

## Current Status

### 🚧 Functional Prototype — Active Development

The GJU Clubs Portal has progressed into a functional full-stack prototype demonstrating how a centralized platform for student clubs and campus engagement could operate.

The current implementation includes multiple user experiences, interactive workflows, frontend and backend services, and bilingual support.

The project continues to evolve through technical development, interface improvements, and feature iteration.

---

## Team

The GJU Clubs Portal is a **student-led project developed at the German Jordanian University**.

### [Ban Y. Tarawneh](https://www.linkedin.com/in/ban-tarawneh/)

### [Team Member Name](https://www.linkedin.com/in/karmel-qawasmi-40b70b197/)


---

## About This Repository

This GitHub organization provides a public overview of the project's technical and product direction.

The application's development repositories and implementation details are maintained separately.

> **Disclaimer:** GJU Clubs Portal is a student-developed project and is not an official digital service or platform of the German Jordanian University.

---

<p align="center">
  <b>Student Engagement • Full-Stack Development • Campus Technology • GJU</b>
</p>
