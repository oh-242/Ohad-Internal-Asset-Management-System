# 🗂️ نظام عُهَد — Ohad Asset Management System

> A bilingual (Arabic/English) internal asset management web app for government organizations and private enterprises — built as an MVP for the SE4231 Software Project Management course at PSAU.

---

## 📌 Project Overview

**Ohad** automates the process of assigning, tracking, and retrieving organizational assets (عُهَد) — such as laptops, monitors, vehicles, and access cards — replacing paper-based workflows with a fully digital process.

This project is inspired by **Saudi Vision 2030's Digital Transformation** objective and the National Digital Transformation Program (NTP).

---

## 🚀 How to Run

No installation, no server, no internet required.

```
1. Download index.html
2. Double-click it
3. Opens directly in your browser ✅
```

Tested on: Chrome · Edge · Firefox · Safari

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🌐 **Bilingual** | Full Arabic / English toggle with RTL support |
| 👤 **Employee View** | View current assets, submit new requests, return assets |
| 🔑 **Manager View** | Approve / reject requests, view activity log |
| 📦 **Inventory View** | Browse all assets with search and category/status filters |
| 📋 **Request Workflow** | Submit → Pending → Approved / Rejected |
| ↩️ **Return Workflow** | Confirm asset return with condition report |
| 🔔 **Toast Notifications** | Real-time feedback messages in both languages |
| 📱 **Responsive** | Works on desktop and mobile |

---

## 🗂️ Project Structure

```
ohad_mvp/
├── index.html      ← Complete single-file application (HTML + CSS + JS)
└── README.md       ← This file
```

All code lives in a single `index.html` file — no frameworks, no dependencies.

---

## 📸 Pages

### 👤 Employee Page
- Stats: active assets · pending requests · total approvals
- Table of current assigned assets with return action
- Full request history with status badges

### 🔑 Manager Page
- Pending approval queue with approve / reject buttons
- Live activity log

### 📦 Inventory Page
- Full asset inventory (10 sample assets)
- Search by name, serial, or custodian
- Filter by category and status

---

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (variables, grid, flexbox, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| i18n | Built-in AR/EN translation object |
| Storage | In-memory state (no backend needed for MVP) |

---

## 🔗 Saudi Vision 2030 Alignment

| Vision Element | Alignment |
|----------------|-----------|
| **Pillar** | Thriving Economy · Ambitious Nation |
| **Goal** | Digital Transformation of Government Services |
| **Program** | National Digital Transformation Program (NTP) |
| **Impact** | Eliminates paper عهدة forms · improves accountability · reduces asset loss |

---

## 📚 Course Info

| Field | Details |
|-------|---------|
| University | Prince Sattam Bin Abdulaziz University (PSAU) |
| Course | SE4231 – Software Project Management |
| Project Weight | 20% of final grade |
| Submission | May 21, 2026 |

---

## 👥 Team

Built as part of the SE4231 course project.  
*You are not required to implement the system — only to plan it.*  
This MVP was developed as a bonus deliverable.

---

## 📄 License

Academic use only — PSAU SE4231 Course Project 2025–2026.
