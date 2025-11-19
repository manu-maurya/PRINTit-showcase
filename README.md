<h1 align="center">🚀 Manu H — Full Stack Developer</h1>

<p align="center">
  Building scalable, cross-platform ecosystems using 
  <strong>Flutter • React • Firebase</strong><br/>
  Founder & Solo Developer of <strong>Printit</strong> — The “Printer on Wheels”
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&pause=1200&color=13F7E5&center=true&vCenter=true&width=700&lines=Startup+Founder;Built+Entire+4-Portal+Stack+Solo;Full+Stack+Developer;Production-Ready+Code" />
</p>

---

# 🖨️ Featured Project: Printit

**Status:** Under Active Development 🚧 | **Current Phase:** MVP Construction  
**Role:** Founder & Sole Architect

**Printit** is a hyperlocal service aggregation platform (The "Zomato for Printers") that connects users with local print shops, streamlining the document printing workflow through a digital ecosystem.

---

## 🏗️ System Architecture

I architected a **4-Portal Ecosystem** to handle the complex logistics of printing and delivery:

```mermaid
graph TD
    User["User App (Flutter)"] -->|Uploads Docs| Firebase
    Delivery["Delivery App (Flutter)"] -->|Live Tracking| Firebase
    Shop["Print Shop Portal (React)"] -->|Order Queue| Firebase
    Admin["Admin Dashboard (React)"] -->|Analytics| Firebase
    Firebase[("Firebase Backend")] -->|Auth & DB| CloudFunctions
```
## 🛠️ Tech Stack

- **Mobile Apps:** Flutter (Provider State Management, Google Maps API)
- **Web Portals:** React.js (Material UI, Redux)
- **Backend:** Firebase (Firestore, Cloud Functions, Auth)
- **Payment:** Razorpay Integration

---

## 📱 App Screenshots

| User App (Landing) | Authentication | Shop Listing | Document Upload |
|:---:|:---:|:---:|:---:|
| ![UserHome](https://github.com/user-attachments/assets/248a0f43-c40e-476c-a4f8-c57910dbb78e) | ![Authentication](https://github.com/user-attachments/assets/8ecbb490-0462-4dbc-b422-afafe8eb36bb) | ![ShopList](https://github.com/user-attachments/assets/c5a21939-083d-4314-80f1-12dd6a9174f9) | ![Upload](https://github.com/user-attachments/assets/3d2c98d9-1930-4815-86e5-ba8aa78388ca) |

| Delivery Tracking | Print Shop Dashboard | Admin Analytics |
|:---:|:---:|:---:|
| ![Tracking](https://github.com/user-attachments/assets/4575f3e3-4bcd-4026-a273-93597364aabf) | ![Dashboard](https://github.com/user-attachments/assets/46159b7f-40a8-4a3b-8b49-f2762b0155bd) | ![Admin](https://github.com/user-attachments/assets/319b59c4-c3aa-4928-8a7f-b12529719595) |

---

## 🚀 Key Features

- **Algorithm:** Location-based print shop discovery and cost estimation
- **Real-time:** Live status updates (Processing → Printed → Out for Delivery)
- **Security:** Secure file transfer + auto-deletion post printing
- **Logistics:** Dedicated delivery partner app with route optimization

---

## 🔒 Why is there no code here?

Printit is a live startup product.  
To protect our **Intellectual Property (IP)** and business logic, the source code is kept private.

This repository serves as a **technical showcase** of the architecture, UI/UX, and system design.

I’m happy to provide a code walkthrough or discuss the architecture during an interview.

---

## 🗺️ Development Roadmap

I am actively building the MVP for the Davanagere market.

- [x] **Phase 1: Core Marketplace (Completed)** ✅
    - [x] **User App (Flutter):** Full working flow, file upload, searching printers, and Order tracking.
    - [x] **Print Shop Portal (React):** Real-time order reception, status updates, and queue management.
    - [x] **Backend:** Firestore Schema & Auth System (User/Shop).

- [ ] **Phase 2: Logistics Ecosystem (In Progress)** 🚧
    - [ ] **Delivery App:** implementing real-time driver allocation logic.
    - [ ] **Admin Dashboard:** Building system-wide analytics and user management.
    - [ ] Integrating Google Maps Directions API for route optimization.

- [ ] **Phase 3: Beta Launch (Planned)**
    - [ ] Onboarding 5 local print shops for pilot testing.
    - [ ] End-to-end load testing.
