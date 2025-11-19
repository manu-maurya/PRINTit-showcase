<h1 align="center">🚀 Manu H — Full Stack Developer</h1>

<p align="center">
  Building scalable, cross-platform ecosystems using 
  <strong>Flutter • React • Firebase</strong><br/>
  Technical Founder of <strong>Printit</strong> — The “Printer on Wheels” or "Zomato for Printers"
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&pause=1200&color=13F7E5&center=true&vCenter=true&width=700&lines=Startup+Founder;Architecting+4-Portal+Ecosystems;Full+Stack+Developer;Always+Learning%2C+Always+Building" />
</p>
# 🖨️ Printit – The “Printer on Wheels”

**Status:** Proprietary Startup (Private Beta)  
**Role:** Technical Founder & Lead Architect

Printit is a hyperlocal service aggregation platform that connects users with local print shops, streamlining the document printing workflow through a digital ecosystem.

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

*(Instruction: Drag and drop your image files directly into the code where it says PLACEHOLDER_LINK)*

| User App (Landing) | Authentication | Shop Listing | Document Upload |
|:---:|:---:|:---:|
| ![UserHome](PLACEHOLDER_LINK) | ![Authentication](PLACEHOLDER_LINK) | ![ShopList](PLACEHOLDER_LINK) | ![Upload](PLACEHOLDER_LINK) |

| Delivery Tracking | Print Shop Dashboard | Admin Analytics |
|:---:|:---:|:---:|
| ![Tracking](PLACEHOLDER_LINK) | ![Dashboard](<img width="1900" height="909" alt="Screenshot 2025-11-19 093639" src="https://github.com/user-attachments/assets/46159b7f-40a8-4a3b-8b49-f2762b0155bd" />
) | ![Admin](PLACEHOLDER_LINK) |

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
