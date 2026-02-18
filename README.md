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

## ✨ Core Capabilities

- Context-aware dashboards (Personal + Team)
- Real-time task synchronization
- Firebase-backed secure member validation
- Automated deadline intelligence
- Pomodoro-based Focus Engine
- Daily task briefing automation
---

## 🧭 User Onboarding & Help System

<img src="https://i.ibb.co/JwsSk05F/help.png" width="500"/>

To improve user experience for new subscribers, WellTask includes a built-in **Help Shortcut Menu**.

When a user subscribes to the bot for the first time:

- A shortcut **Help button** is available.
- Users can instantly view all available features.
- No need to remember slash commands.
- Provides guided navigation through:
  - Dashboard access
  - Task creation
  - Focus Hub
  - Productivity reports
  - Member sync features

This ensures smooth onboarding and reduces user learning friction.

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

WellTask allows structured task creation directly inside Zoho Cliq chat with real-time cross-dashboard synchronization.

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

Only members who are already present in the channel appear in the **Assign-To dropdown**, ensuring secure and valid assignment.

---

### 🔄 Intelligent Cross-Dashboard Sync (Key Feature)

When a manager or team member assigns a task via the form:

- The task is added to the **Channel Shared Dashboard**
- Simultaneously added to the **Assigned User’s Personal Dashboard**
- The assigned member receives a detailed real-time notification including:
  - Task Name
  - Due Date
  - Priority Level
  - Assigned By
  - Workspace & Project details

This ensures full transparency and seamless collaboration between team and personal workflows.

Both dashboards stay synchronized in real-time via backend updates.

---

### 👤 Personal Bot Mode

When `/addtask` is used in personal bot chat:

- Task is created as personal
- Assign-To field is hidden
- Automatically syncs with Personal Dashboard
- No channel visibility

---

### 🖼 Task Creation Interface

<div align="center" style="overflow-x: auto; white-space: nowrap;">
  <img src="https://i.ibb.co/S4FDR5Cf/addtaskform.png" width="450"/>
  <img src="https://i.ibb.co/DPN5vbyX/Screenshot-2025-11-30-125540.png" width="450"/>
</div>

---
## 👥 Automated Member Sync & Access Control

WellTask maintains strict access control to ensure that only valid channel members can view and interact with shared dashboards.

If a specific channel member is not officially synced, they will not receive project updates or access dashboard data. This prevents unauthorized visibility.

---

### 🔁 Automatic Admin Sync & Member Removal

- When the bot is added to a channel, the **Admin is automatically synced**.
- A dropdown appears showing all other members who need to be synced.
- Only synced members are stored in Firebase (`allowed_user` system).
- If a member leaves or is removed from the channel:
  - A scheduled daily check at **9:30 AM** automatically removes them from `allowed_user`.
  - They are removed from dashboard access.
  - They are removed from the Assign-To dropdown.
  - They no longer receive task updates.

This ensures only live channel members remain authorized.

---

### 🔁  `/syncmembers` – Manual Refresh for New Members

- Channel admins can type `/syncmembers` anytime.
- The command shows a dropdown containing **only new members** who are not yet synced.
- Removed users are automatically excluded.
- Firebase is updated in real-time with valid members only.
- If all users are already synced, the bot displays:
  > "No new members to sync."

This ensures secure and regularly updated membership validation.

---

### 🔐 Firebase-Backed Member Validation

WellTask continuously updates Firebase to store only active channel members.

Advantages:
- Prevents unauthorized access
- Keeps Assign-To dropdown clean
- Maintains accurate team visibility
- Ensures secure data boundaries

---

### 🖼 Member Sync & Security Flow

<div align="center" style="overflow-x: auto; white-space: nowrap;">
  <img src="https://i.ibb.co/4ZRCD4Zd/firebase.png" width="420"/>
  <img src="https://i.ibb.co/vxtX0hxs/sync-mem-auto-bot.png" width="420"/>
  <img src="https://i.ibb.co/m5qTzSfw/bot-added.png" width="420"/>
  <img src="https://i.ibb.co/TMR5G3L5/remove-add-sync-mem.png" width="420"/>
</div>

---

## 🚨 Smart Alerts & Daily Task Intelligence

WellTask includes an automated alerting engine that continuously monitors task urgency and deadline risks.

---

### 🔴 Deadline Risk Alerts

<img src="https://i.ibb.co/ZRtddJBP/deadline-alerts.png" width="900"/>

WellTask automatically sends **Deadline Risk Alerts** when:

- A task is marked as **High Priority**
- The due date is near or approaching
- The task is at risk of being overdue

Alert includes:
- Task Name
- Priority Level (High)
- Due Date
- Risk indication

Only priority-wise important tasks are highlighted.  
Lower-priority tasks are intentionally filtered to avoid notification overload.

This ensures users focus only on critical work.

---

### 🌅 Daily Task Briefing (9:30 AM Automation)

<img src="https://i.ibb.co/vCsybg7j/dailytaskoverview.png" width="900"/>

Every morning at **9:30 AM**, WellTask sends an automated **Daily Task Briefing**.

The briefing includes:
- All pending tasks
- Priority classification
- Due dates
- Structured overview of the day’s workload

This feature helps users:
- Plan their day effectively
- Prioritize critical tasks
- Stay accountable without opening the dashboard

Powered by scheduled automation and backend cron logic.

---

## 🎯 Focus Hub – Real-Time Pomodoro Productivity Engine

WellTask includes a fully integrated Focus Hub designed for distraction-free productivity.

Users only need to **start the session from the Focus Hub dashboard** — all remaining workflow logic is automatically handled inside Zoho Cliq bot in the background.

---

### 🚀 How It Works

- Start Focus Session from Focus Hub
- Real-time "Focus Started" notification
- Timer runs in the background
- Fully non-distractive workflow

All updates reflect instantly inside the Focus Hub dashboard.

---

### ⏳ Break & Session Controls

Users can:

- Take Break
- Skip Break
- Finish Early

When **Break** is clicked:

- Break timer starts automatically
- Timer duration follows customized break settings
- Runs completely in background
- No manual intervention required

Once the break duration is completed:

- The focus session automatically resumes
- Continues tracking for the same task
- No need to restart manually

All actions update the Focus Hub dashboard in real-time.

---

### ⚙️ Customizable Settings

- Focus duration configurable
- Short break duration configurable
- Long break duration configurable
- Break time excluded from productivity metrics
- Completed tasks restorable anytime

Everything runs based on personalized configurations.

---

### 🔄 Real-Time Updates

- Session state updates instantly
- Dashboard reflects timer state
- Background automation handles transitions
- No interruption to channel workflow

---

### 🖼 Focus Hub Interface

<div align="center" style="overflow-x: auto; white-space: nowrap;">
  <img src="https://i.ibb.co/MYx751W/Screenshot-2025-11-30-125610.png" width="420"/>
  <img src="https://i.ibb.co/WW5NGcB3/Screenshot-2025-11-30-125630.png" width="420"/>
  <img src="https://i.ibb.co/ycq47Ny7/focus-hub-break.png" width="420"/>
</div>

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

Shortlisted in **Round-1 of Zoho CliqTrix ’26**  
(Top 35 Teams – Zoho Cliq Track)

---

## 🛠 Engineering Challenges

- **API Integration:** Managed integration between Zoho Cliq bot, widget, and Firebase backend.
- **Complex Debugging:** A small issue in one module impacted others — required structured isolation and testing.
- **New Ecosystem Learning:** Adapted to Deluge scripting and Zoho Cliq event-driven architecture.
- **Real-Time Sync Issues:** Ensured consistent dashboard updates across personal and channel modes.

These challenges strengthened my understanding of real-time systems, secure access control, and scalable bot architecture.

---


