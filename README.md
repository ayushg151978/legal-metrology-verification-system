# Legal Metrology Online Verification & Digital Certification System

> **SIH Problem Statement ID:** 26036  
> **Organization:** Department of Consumer Affairs (DoCA), Ministry of Consumer Affairs, Food & Public Distribution  
> **Category:** Software / Legal Metrology Ecosystem  

---

## 📌 Problem Overview
Under the **Legal Metrology Act, 2009** and the **Legal Metrology (General) Rules, 2011**, every weighing and measuring instrument used in commercial transactions or public protection requires periodic verification and stamping. 

This platform digitizes the complete lifecycle management of weights and measures—replacing manual physical registers with online application submission, inspector assignment scheduling, automated tolerance verification, digital QR-enabled certificates, and automated statutory compliance tracking.

---

## ✨ Key Features & Stakeholder Workflows

### 🏛️ Multi-Role Stakeholder Portals (RBAC)
- **Business / Trader Portal:** 
  - Online verification & periodic re-verification application submission (`/applications/new`).
  - Integrated statutory stamping fee and late renewal penalty ledger (`/payments`).
  - Real-time application tracking and official digital certificate download.
- **Legal Metrology Officer (LMO) Portal:** 
  - Dynamic inspection work queue and schedule allocation.
  - Verification of calibrated **Inspector Working Standard Test Kits** before testing.
  - Recording of physical lead/wire seals and holographic sticker serial numbers.
- **Admin & Department Oversight:** 
  - Centralized jurisdiction analytics (District/Zone compliance monitoring).
  - Complete immutable audit logging and user account management.
- **Unauthenticated Public Portal (`/verify`):** 
  - Real-time consumer verification of shop scales and instant certificate authentication via dynamic QR code scanning.

---

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript, Tailwind CSS, Lucide Icons, Vite
- **Backend:** Node.js, Express.js, JWT Authentication
- **Database & ORM:** PostgreSQL, Prisma ORM
- **Utilities & Engines:** 
  - QR Code Generator & PDF Certificate Renderer
  - Legal Metrology Max Permissible Error (MPE) Rules Engine
  - Daily Expiry Monitoring Cron Jobs

---

## 🚀 Quick Setup & Installation

### Prerequisites
- **Node.js:** v18.0.0 or higher
- **PostgreSQL Database** running locally or on a cloud instance

### 1. Repository Setup
```bash
# Clone the repository
git clone [https://github.com/YOUR_USERNAME/legal-metrology-verification-system.git](https://github.com/YOUR_USERNAME/legal-metrology-verification-system.git)
cd legal-metrology-verification-system
