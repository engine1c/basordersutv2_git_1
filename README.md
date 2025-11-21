<h1 align="center">📱 1C + Flutter Mobile App</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Backend-1C%3AEnterprise-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Frontend-Flutter-02569B?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Android-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/API-15%2B-orange?style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active_Development-success?style=flat-square">
  <img src="https://img.shields.io/github/license/placeholder/placeholder?style=flat-square">
</p>

---
For cooperation inquiries, please contact: i9engine.app@gmail.com

# 🌍 Languages
- 🇬🇧 [English README](README_EN.md)  
- 🇵🇱 [Polski README](README_PL.md)  
- 🇷🇺 [Русский README](README_RU.md)  
- 🇺🇦 [Українська README](README_UA.md)  

---

# 🚀 Overview

A cross-platform system combining **1C:Enterprise (managed forms) backend** with a **Flutter Android app** supporting:

✔ Real-time editing of customer orders  
✔ Full sync with 1C  
✔ Access to reference directories  
✔ Authentication with encryption + 1C token  
✔ Light/Dark themes  
✔ Multilingual interface (EN/PL/RU/UK)

The project is built for **speed, clarity, and adaptability** — suitable for any organization using 1C.

---

# 🧩 Architecture

## 📐 High-Level Architecture Diagram
```text
                   ┌─────────────────────────┐
                   │     Flutter Mobile App   │
                   │  (Android, API 15+)      │
                   │  - UI/UX                 │
                   │  - Auth (encrypted)      │
                   │  - Themes & Languages    │
                   │  - Orders & Catalogs     │
                   └───────────────▲─────────┘
                                   │ REST API
                                   │ Token exchange
                                   │ JSON
                   ┌───────────────┴──────────┐
                   │     1C:Enterprise         │
                   │  Managed Forms Backend    │
                   │                           │
                   │ Documents: Orders         │
                   │ Directories: Contractors, │
                   │ Warehouses, Items, etc    │
                   │ Reports: Order Analysis   │
                   │ Registers: HTTP Activity  │
                   │            Sessions       │
                   └───────────────────────────┘
🔧 Backend: 1C Structure
📄 Documents

Customer Order

📚 Directories

Organizations

Contractors

Contractor Agreements

Contact Persons

Positions

Warehouses

Items (with product photos)

Units Classifier

Users

📊 Report

Order Analysis

📒 Information Registers

HTTP User Activity

User Sessions

📱 Frontend: Flutter App
🔐 Authentication

Login & password (encrypted)

Token retrieval from 1C

✏ Features

Real-time editing of customer orders

Full order journal with date filters

View Contractors and Items directories

🎨 Customization

Light / Dark themes

Interface languages: EN / PL / RU / UK

🧩 Adaptability

This mobile solution can be:

customized for any business workflow

embedded as a communication module with your 1C configuration

extended for CRM, warehouse operations, field agents, etc.

🤝 Contribution

Pull requests are welcome!
For major changes, open an issue first.

📄 License