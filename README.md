# 📦 TrackPro – Modern Delivery Tracking & Courier Management System

TrackPro is a complete, feature-rich, single-file frontend web application for tracking packages, managing couriers, visualising delivery routes, and viewing logistics analytics. Built with **HTML5, Tailwind CSS, JavaScript (ES6+), and Chart.js**, it operates seamlessly in any browser without complex build setups or backend dependencies.

---

## 🌐 Live Demo & Repository

*   *Live Website:* [ https://asmabanahatti687-lab.github.io/Delivery-Tracking-System/]( https://asmabanahatti687-lab.github.io/Delivery-Tracking-System/) *(Replace with your Netlify, Vercel, or GitHub Pages link)*
*   *GitHub Repository:* `https://github.com/your-username/trackpro-delivery-system.git`

---

## ✨ Key Features & Functionality

*   **1. Public Package Tracking:**
    *   Instant tracking by unique Tracking ID (e.g., `TRK-1001`).
    *   Interactive step-by-step delivery progress timeline (Pending ➔ In Transit ➔ Out for Delivery ➔ Delivered / Failed).
    *   Privacy protection masking sender/recipient sensitive data for unauthenticated users.
    *   Printable package receipt & status summary generator.

*   **2. Interactive Admin & Logistics Dashboard:**
    *   Live metrics counters for Total Packages, Pending, In Transit, Out for Delivery, Delivered, and Failed shipments.
    *   **Chart.js** status distribution chart and weekly shipment volume trends.
    *   Quick actions for package entry, courier assignment, and status updates.

*   **3. Package Management (Full CRUD):**
    *   Add new packages with auto-generated unique tracking numbers.
    *   Filter packages by status or search by sender, receiver, destination, or tracking code.
    *   Edit details, update statuses with real-time timestamping, and delete packages with confirmation modals.

*   **4. Courier Management & Workload Overview:**
    *   Courier profiles with active delivery counts, vehicle types, contact details, and performance metrics.
    *   One-click package assignment to available couriers.

*   **5. Animated Route Visualizer:**
    *   SVG map visualizer with animated delivery vehicles traveling between route waypoints.
    *   Interactive waypoint nodes showing package drop-offs and assigned couriers.

*   **6. Role-Based Access Control (RBAC):**
    *   Seamless switching between **Customer**, **Courier / Staff**, and **Admin** roles.
    *   Restricted UI elements and access-denied safeguards for unauthorized routes.

*   **7. Reports & Data Export:**
    *   Delivery statistics and performance summaries.
    *   One-click CSV data export for offline reporting.

*   **8. LocalStorage Persistence & Toast System:**
    *   Pre-loaded realistic mock dataset with a live "Reset Demo Data" option.
    *   Dynamic success and error toast notifications for all user actions.

---

## 🎨 Color Palette & Design System

*   **Primary Accent:** Amber (`#F59E0B`)
*   **Secondary Background:** Light Yellow (`#FEF3C7`)
*   **Base Neutral:** Slate / Dark Gray (`#1F2937`)
*   **Background:** Clean White (`#FFFFFF`) / Off-White (`#F9FAFB`)

---

## 🛠️ Technology Stack

*   **HTML5 & CSS3** (Semantic structure and layout styling)
*   **Tailwind CSS (v3 via CDN)** (Utility-first styling and theme customization)
*   **JavaScript (ES6+)** (State management, SPA tab routing, and dynamic DOM manipulation)
*   **Font Awesome (v6.4.0)** (Vector icons)
*   **Chart.js (v4.4.0)** (Interactive dashboard charts and data analytics)
*   **LocalStorage API** (Browser data persistence for packages, couriers, routes, and roles)

---

## 🚀 Quick Start & Installation

Because TrackPro is built as a self-contained single-file web application (`index.html`), no build tools, Node.js server, or database setups are required to run it locally.

1. **Clone or Download** the repository:
   ```bash
   git clone [https://github.com/your-username/trackpro-delivery-system.git](https://github.com/your-username/trackpro-delivery-system.git)
   cd trackpro-delivery-system
