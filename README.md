# Smart Queueing System (QuickServe Canteen)

A web-based smart canteen ordering platform that eliminates physical queues by enabling digital food ordering, cashless payment simulation, and QR-code–based order verification for fast, contactless food collection.

---

## 📌 Overview

The **Smart Queueing System (QuickServe Canteen)** is a frontend-driven web application designed to modernize food ordering in institutional and corporate canteens. The system allows users to browse a digital menu, place orders online, complete a simulated cashless payment, and receive a QR code that serves as a digital receipt for order verification and collection.

This project demonstrates the application of **modern frontend technologies, object-oriented design concepts, and client-side state management** to solve real-world queue management problems.

---

## 🎯 Problem Statement

Traditional canteen systems rely on manual ordering and cash payments, leading to:
- Long queues during peak hours
- Increased order inaccuracies
- Inefficient crowd management
- Poor user experience

The Smart Queueing System addresses these issues by providing a **contactless, automated, and queue-free ordering workflow**.

---

## ✅ Key Features

- Digital and interactive food menu
- Dynamic cart management with real-time billing
- Cashless payment simulation (UPI, wallets, cards)
- Automatic QR code generation after payment
- QR-based order verification and receipt generation
- Responsive and mobile-friendly UI
- Fully client-side implementation (no backend dependency)

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** – Page structure and layout
- **CSS3** – Styling and visual presentation
- **Tailwind CSS** – Utility-first responsive design
- **JavaScript (Vanilla)** – Application logic and state handling

### Libraries & Tools
- **QRCode.js** – QR code generation
- **Visual Studio Code** – Development environment
- **Google Chrome** – Testing and debugging

---

## 🧩 System Architecture

The application follows a **modular, frontend-oriented architecture**:

- **Presentation Layer**  
  Handles user interaction, menu display, cart updates, and payment UI.

- **Business Logic Layer (Client-Side)**  
  Manages cart state, order processing, payment simulation, QR generation, and receipt rendering using JavaScript.

The architecture is designed to be easily extendable for backend and database integration in future versions.

---

## 🔄 Application Workflow

1. User browses the digital menu
2. Selected items are added to a virtual cart
3. Total amount is calculated dynamically
4. User proceeds to simulated digital payment
5. On successful payment, a unique Order ID is generated
6. QR code is created as a digital receipt
7. QR code is scanned at the counter for verification
8. Food is collected without standing in queue

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge)
