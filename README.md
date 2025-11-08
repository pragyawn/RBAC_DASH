# 🎯 Role-Based Access Control (RBAC) Dashboard  
### Moksha 2025 Event Management Platform  

---

## 🧩 Overview

The **RBAC Dashboard** is a dynamic event management platform built for **Moksha 2025**, designed to streamline event scheduling, approval workflows, and real-time coordination for 100+ student societies.  

It introduces a **role-based access control system** that ensures secure, seamless collaboration between organizers, faculty, and administrators — replacing scattered manual processes with a centralized, automated solution.

---

## 🚀 Key Features

- 🔐 **Role-Based Access Control (RBAC):**  
  Implements secure role segregation (Admin, Society Head, Faculty Coordinator, Event Member) ensuring complete data integrity and preventing unauthorized modifications.

- 📅 **Dynamic Event Scheduling & Approvals:**  
  Automates the event proposal and approval workflow, reducing manual coordination efforts by **70%**.

- ⚙️ **Conflict Resolution System:**  
  Detects scheduling overlaps and helps users choose optimal event slots in real-time, improving operational efficiency.

- 🌐 **Real-Time Event Updates:**  
  Enables live event creation, modification, and tracking for over **100+ student societies**.

- 🧠 **Smart Dashboard:**  
  Provides intuitive visual summaries for upcoming events, pending approvals, and resource allocation.

- 🎨 **Modern & Intuitive UI:**  
  Designed with **Next.js** and **Tailwind CSS**, ensuring a responsive, fast, and accessible interface that improved adoption and reduced onboarding time.

---

## 🛠️ Tech Stack

| Category | Technology |
|-----------|-------------|
| **Frontend** | React.js, Next.js, TypeScript, Tailwind CSS |
| **Backend** | NextAuth (for authentication), Node.js (via Next API routes) |
| **Database** | MongoDB (Mongoose ORM) |
| **Authentication** | NextAuth.js with JWT session management |
| **Version Control** | Git, GitHub |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/pragyawn/RBAC_DASH.git
cd RBAC_DASH

## 2️⃣ Install Dependencies
```bash
npm install


### 3️⃣ Configure Environment Variables
```bash
MONGODB_URI=your_mongodb_connection_string
NEXTAUTH_SECRET=your_secret_key
NEXTAUTH_URL=http://localhost:3000

### 4️⃣ Run the Application
```bash
npm run dev

