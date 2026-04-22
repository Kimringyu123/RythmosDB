# Rythmos DB — Site Description

## Short Description (for README / Vercel project name)
> **Rythmos DB** is an internal operations platform for media analytics teams — combining account management, SOP tracking, team performance, time logging, and real-time messaging in a single web app.

---

## Full Description

**Rythmos DB** is a purpose-built internal dashboard designed for media analytics and client success teams. It centralizes everything a team needs to manage accounts, track deliverables, monitor performance, and communicate — all in one place, without switching between tools.

### 🗂 What It Does

**Account Management**
Track all client accounts with statuses, assigned analysts, SOP progress, cadence types, and handler assignments. Each account has its own overview, channel, and SOP tracker.

**SOP Tracker**
A structured phase-by-phase checklist system tied to each account. Teams can upload custom SOP steps per account, assign steps to specific members, log time directly from the tracker, and export progress reports as PDFs.

**Performance Dashboard**
Real-time KPI scoring per analyst and team, with phase breakdowns, completion rates, and leaderboard-style rankings. ManComm sees the full picture; analysts see their own stats.

**Time Tracker**
Log hours against specific SOP steps and accounts. Includes a live timer, manual entry, and a timesheet view filterable by date range and account.

**Leave Calendar**
Submit and manage leave requests with a visual calendar view. ManComm can approve or reject requests; the team can see who's out on any given day.

**Team Hub**
A directory of all team members organized by team, with role badges, account assignments, KPI scores, and contact details. Supports adding, editing, and archiving members.

**Channels (Messaging)**
Slack-style real-time messaging powered by Supabase. Channels can be public (all teams), team-specific, or linked to a specific account — so only assigned members see account channels. Supports replies, reactions, GIFs, and file attachments.

**AI Assistant**
A built-in Claude-powered assistant for drafting reports, analyzing SOP gaps, and answering operations questions — without leaving the app.

**Reports & PDF Export**
Generate and download SOP progress reports as formatted PDFs, per account and per analyst.

**Activity Log**
A live feed of everything happening across the platform — joins, updates, completions, messages, and more.

---

### 👥 Who It's For

| Role | Access Level |
|---|---|
| COO / Operations Manager | Full access — all accounts, all teams, all data |
| HR Manager / L&D | Full team visibility, leave management |
| Team Leader | Own team's accounts and members |
| Client Success Manager | Assigned accounts |
| Media Analyst | Own accounts, own time logs |

---

### ⚙️ Tech Stack

- **Frontend:** Vanilla HTML/CSS/JS — single-file app, zero build step
- **Backend & Auth:** [Supabase](https://supabase.com) (PostgreSQL + Realtime)
- **Hosting:** Vercel (static deployment)
- **AI:** Anthropic Claude API
- **GIFs:** Tenor API

---

### 🚀 Deployment

Hosted on Vercel as a static single-page app. No server required — just deploy `index.html` and the Supabase backend handles all data, auth, and real-time updates.
