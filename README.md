# codsoft-internship
# Software Projects Portfolio

A collection of full-stack web applications built with **Next.js**, **Prisma**, **PostgreSQL**, and **TypeScript**.

---

## Table of Contents
- [1. Job Portal](#1-job-portal)
- [2. Restaurant Ordering Platform](#2-restaurant-ordering-platform)
- [3. Student Management System](#3-student-management-system)
- [Tech Stack Overview](#tech-stack-overview)
- [Getting Started](#getting-started)
- [License](#license)

---

## 1. Job Portal

### Description
**Job Portal** is a modern web application that connects job seekers with employers. It features an intuitive user interface, real-time job notifications, and advanced search and filtering options, making it seamless for candidates to discover relevant career opportunities and for employers to manage listings.

### Tech Stack
- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Next.js API Routes, TypeScript
- **Database & ORM:** PostgreSQL, Prisma ORM

### Key Features
- User authentication for Job Seekers and Employers
- Advanced search and multi-criteria filtering (location, salary, job type)
- Real-time notification updates for application status
- Employer dashboard to post, edit, and manage job listings

---

## 2. Restaurant Ordering Platform

### Description
**Restaurant Ordering Platform** is a digital food ordering system where customers can browse interactive menus, place customized orders, and track their order status in real time. The platform streamlines order flow and kitchen operations for modern dining establishments.

### Tech Stack
- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Next.js API Routes, TypeScript
- **Database & ORM:** PostgreSQL, Prisma ORM

### Key Features
- Interactive digital menu with category filtering and item customizations
- Cart management and checkout flow
- Real-time order tracking from placement to preparation and fulfillment
- Administrative order management dashboard for restaurant staff

---

## 3. Student Management System

### Description
**Student Management System** is a comprehensive information portal engineered for academic institutions. It provides an intuitive dashboard for managing student records, tracking attendance, logging grades, and generating performance analytics to streamline administrative workflows.

### Tech Stack
- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Next.js API Routes, TypeScript
- **Database & ORM:** PostgreSQL, Prisma ORM

### Key Features
- Centralized student directory and profile management
- Attendance tracking and automated reporting
- Gradebook management with grade calculation and transcript generation
- Admin dashboard with high-level institutional analytics

---

## Tech Stack Overview

| Layer | Technology |
| :--- | :--- |
| **Framework** | [Next.js](https://nextjs.org/) |
| **Language** | [TypeScript](https://www.typescriptlang.org/) |
| **Database** | [PostgreSQL](https://www.postgresql.org/) |
| **ORM** | [Prisma](https://www.prisma.io/) |

---

## Getting Started

### Prerequisites
- Node.js (v18.0.0 or higher)
- PostgreSQL database instance
- npm, yarn, or pnpm

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <REPOSITORY_URL>
   cd <PROJECT_DIRECTORY>
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   Create a `.env` file in the root directory:
   ```env
   DATABASE_URL="postgresql://user:password@localhost:5432/dbname?schema=public"
   ```

4. **Run Database Migrations**
   ```bash
   npx prisma migrate dev
   ```

5. **Start Development Server**
   ```bash
   npm run dev
   ```

---

## License

Distributed under the MIT License. See `LICENSE` for more information.
