<p align="center">
  <img src="https://i.ibb.co/7xkRGcJx/647cf60a-aa9e-41c4-b87b-6e3f55eb4367.png" width="140"/>
</p>

<h1 align="center">WellTask</h1>
<h3 align="center">Real-Time Productivity Bot & Widget for Zoho Cliq</h3>

<p align="center">
  <b>Secure • Real-Time • Focus-Driven • Team-Ready</b>
</p>

---

## 📌 Overview

WellTask is a real-time productivity bot built for Zoho Cliq that enables seamless **personal task management** and **team collaboration** directly within chat.

It integrates dashboards, Pomodoro-based focus tracking, automated alerts, and analytics — all inside Zoho Cliq without switching applications.

Built with real-time architecture and secure access validation.

---

## 🔐 Secure Access & Identity Verification

<img src="https://i.ibb.co/1tPgCzzJ/welltask-security-check.png" width="900"/>

Before granting dashboard access, WellTask performs identity verification and secure access validation.

### Security Highlights
- Verified user authentication
- Role-based access control
- Automatic admin synchronization
- Scheduled 9:30 AM member integrity check
- Automatic removal of unauthorized users
- Secure separation between personal and team boards

---

## 📊 Smart Dashboard Access – `/welltask`

WellTask intelligently detects context and opens the correct dashboard automatically.

---

### 👤 Personal Bot Mode

When you type `/welltask` inside the **WellTask personal bot chat**:

- Your **Personal Dashboard** opens instantly
- Shortcut menus are available (no need to type commands repeatedly)
- Quick-access buttons allow instant navigation
- Fully interactive widget-based interface

You simply click — no repeated typing required.

---

### 👥 Channel Mode

You can add the WellTask bot to any specific Zoho Cliq channel.

Once added:

- All team features become accessible inside the channel
- Members can collaborate in real-time
- Tasks sync across shared dashboards

When you type `/welltask` inside a channel:

- It opens the **Shared Team Dashboard**
- Displays a **short preview overview**
- Provides button to open full dashboard
- Maintains role-based access control

---

### 🔄 Available Views

- **Kanban View** (Column-based workflow tracking)
- **List View** (Structured task listing)

Users can switch between both views dynamically.

---

### 🖼 Dashboard Preview (Personal & Channel Modes)

<div align="center" style="overflow-x: auto; white-space: nowrap;">
  <img src="https://i.ibb.co/GQzgmw92/Screenshot-2026-02-18-131411.png" width="450"/>
  <img src="https://i.ibb.co/DffB3743/persoanl-channel-1.png" width="450"/>
  <img src="https://i.ibb.co/d4k5GfbF/Screenshot-2025-11-30-130301.png" width="450"/>
  <img src="https://i.ibb.co/DPN5vbyX/Screenshot-2025-11-30-125540.png" width="450"/>
</div>

---

## 📝 Real-Time Task Creation – `/addtask`

WellTask allows structured task creation directly inside Zoho Cliq chat.

---

### 👥 Channel Mode – Structured Team Task Creation

When you type `/addtask` inside a channel:

A dynamic task creation form opens with the following fields:

- Task Name  
- Workspace Selection  
- Project Selection  
- Column / Group Selection  
- Priority (Low / Medium / High)  
- Due Date  
- Assign-To (Dropdown of existing channel members)

Only members who are already present in the channel appear in the **Assign-To dropdown**.

Once submitted:

- The task appears instantly in the **Team Dashboard**
- It syncs automatically to the assigned user’s **Personal Dashboard**
- The assigned user receives a real-time notification containing:
  - Task Name
  - Due Date
  - Priority
  - Assigned By
  - Workspace & Project details

All updates happen in real-time via backend synchronization.

---

### 👤 Personal Bot Mode

When `/addtask` is used in personal bot chat:

- Task is created as personal
- Assign-To field is hidden
- Automatically syncs with Personal Dashboard

---

### 🖼 Task Creation Interface

<div align="center" style="overflow-x: auto; white-space: nowrap;">
  <img src="https://i.ibb.co/S4FDR5Cf/addtaskform.png" width="450"/>
  <img src="https://i.ibb.co/DPN5vbyX/Screenshot-2025-11-30-125540.png" width="450"/>
</div>

---



## 🎯 Focus Hub – Pomodoro Productivity Engine

<img src="https://i.ibb.co/MYx751W/Screenshot-2025-11-30-125610.png" width="900"/>
<img src="https://i.ibb.co/WW5NGcB3/Screenshot-2025-11-30-125630.png" width="900"/>

A fully integrated focus tracking system designed to boost productivity.

### Features
- Customizable focus duration
- Short & long break configuration
- Real-time "Focus Started" notifications
- Automated break alerts
- Skip break / Complete early options
- Break time excluded from productivity metrics
- Restorable completed tasks

---

## 📈 Productivity Analytics

<img src="https://i.ibb.co/zTRksWxm/Screenshot-2025-11-30-125707.png" width="900"/>
<img src="https://i.ibb.co/3520qFT0/Screenshot-2025-11-30-125721.png" width="900"/>

- Daily productivity reports
- Weekly & Monthly insights
- Pomodoro tracking
- Focus minutes tracking
- Break usage analytics
- Task time distribution visualization

---

## ⚙️ Tech Stack

### 🖥 Frontend
- 🌐 HTML  
- 🎨 CSS  
- ⚡ JavaScript  

Frontend deployed via **Vercel** using GitHub integration and embedded inside Zoho Cliq as a widget.

### 🔥 Backend
- Firebase (Realtime Database)
- Real-time synchronization architecture
- Secure data handling

### 🧠 Zoho Cliq Integration
- Deluge scripting (Zoho's native programming language)
- Bot & Widget framework
- Slash-command handling
- Scheduler-based automation
- Role-based access logic

---

## 🚀 Deployment & Architecture Highlights

- Frontend deployed on Vercel via GitHub CI/CD
- Firebase backend for real-time updates
- Integrated inside Zoho Cliq environment
- Event-driven command handling
- Cron-based scheduler (9:30 AM integrity check)
- Secure user validation system
- Real-time dashboard synchronization
- Separation of personal and team contexts

---

## 🏆 Achievement

Shortlisted in **Zoho CliqTrix ’26**  
Top 35 Teams – Zoho Cliq Track

Designed with real-world SaaS product principles and automation-focused workflow engineering.

---
