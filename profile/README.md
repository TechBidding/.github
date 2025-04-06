# 🛠 Developer Marketplace Platform

A modern, scalable platform designed for **developers** and **clients** to connect and collaborate on real-world projects. Think of it as a dev-focused version of Fiverr or Upwork — tailor-made for software engineers and teams.

Built using **Microservices Architecture**, **Kafka**, **NestJS**, and **MongoDB**, this platform is designed to be **scalable**, **modular**, and **production-ready**.

---

## 📦 Microservices Overview

### **1. User Microservice**
- 🔐 User Registration & Login
- 🧾 OAuth & JWT Authentication
- 👤 Profile & Portfolio Management
- ⭐ Reviews and Ratings

### **2. Service Listing & Project Posting Microservice**
- 📝 Developers List Services
- 📣 Clients Post Projects
- 💬 Project Bidding
- ✅ Proposal Review & Selection

### **3. Real-Time Communication Microservice**
- 💬 Real-time Chat System
- 🔔 Global Notification System (Kafka + DB)

### **4. Project Execution & Payment Microservice**
- 🚀 Milestone Tracking
- 💰 Escrow-based Payments

---

## 🔁 Project Workflow

### Developer Side
1. Register & Set Up Profile
2. List Services & Pricing
3. Browse & Bid on Projects
4. Communicate with Clients
5. Track Milestones
6. Get Paid via Escrow
7. Receive Reviews

### Client Side
1. Register & Complete Profile
2. Post Projects
3. Compare Developer Proposals
4. Select Developer
5. Create & Approve Milestones
6. Release Payments
7. Leave Reviews

---

## ✅ Project Progress

### 🟢 Done
- ✅ Kafka integrated for notification ingestion
- ✅ User Management Service for client as well as for developers.
- ✅ Project Management Service to list and colaborate with the project
- ✅ Notificatoin Managemet Service with kafka.
- ✅ [UI]: Authentication flow (Login & Registration)
- ✅ [UI]: Navbar component

### 🟡 In Progress
- 🔧 [UI]: Project listing page
- 🔧 [UI]: Service creation page

### 🔴 To Do
- ⬜ Review & Rating system
- ⬜ Milestone tracking UI/logic
- ⬜ Real-time chat (WebSocket or socket.io)
- ⬜ Escrow-based payment handling
- ⬜ Admin dashboard (Optional for moderation)
- ⬜ Elasticsearch integration (future enhancement)

---

## 🧠 Tech Stack

| Layer        | Tech                     |
|--------------|--------------------------|
| Frontend     | React, Tailwind CSS      |
| Backend      | NestJS                   |
| Database     | MongoDB, Mongoose        |
| Communication| Kafka (event-driven), REST|
| Auth         | JWT, Google/GitHub OAuth |
| Notifications| Kafka + MongoDB          |

---

## 🚀 Getting Started (Instructions TBD)

To be added once basic microservices and UI are integrated.

---

## 💡 Long-Term Vision
- ML-based recommendation engine / Skill-based project recommendations (ML-powered)
- Elasticsearch for optimized project search
- Dispute resolution system
- Admin moderation features


---
