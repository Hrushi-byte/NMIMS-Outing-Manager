# 🛡️ OutingManager – NMIMS Shirpur Outing Management Application

## Overview
OutingManager is an Android application built for NMIMS Shirpur to simplify and digitize the entire campus outing permission process for students and wardens. The app enables quick outing requests, real-time approval tracking, chatbot assistance, QR-based verification, and warden-side decision management — all powered by Firebase with modern UI/UX.

## Features
- **Student Outing Requests:** Students can submit outing requests with details such as date, destination, and return time.
- **Real-Time Status Tracking:** Live updates for request status including Pending, Approved, and Rejected via Firebase sync.
- **ChatBot Assistance:** AI-powered chatbot guiding students on outing rules, curfew timings, bus schedules, documents required, and general FAQs.
- **Voice Input & Quick Replies:** Allows students to speak queries and use preloaded quick-reply buttons for instant assistance.
- **Outing History & Analytics:** Monthly and yearly analytics showing outing count, approval trends, and travel patterns.
- **QR Code for Approved Outings:** Automatically generates a unique QR code for approved outings to be scanned at the campus gate.
- **Warden Dashboard:** Wardens can view, approve, or reject student requests instantly from their dashboard.
- **Announcements:** Wardens can broadcast important alerts or notifications to all students.
- **Eligibility Selection:** Wardens can filter and select eligible students for outings based on hostel and institutional rules.

## Tech Stack
- **Language:** Java
- **UI:** XML
- **Database:** Firebase Firestore & Realtime Database
- **Authentication:** Firebase Authentication
- **Other Technologies:** FCM (Firebase Cloud Messaging), QR Code Generator, Voice-to-Text, RecyclerView, ViewModels, Custom Adapters

## Architecture
- Modular package design with folders like: `activities/`, `adapters/`, `models/`, `viewmodels/`, `utils/`, `firebase/`
- Dedicated components for outing management, chatbot, and QR code generation
- Clear separation of UI, logic, and data layers for better maintainability
- Real-time Firestore updates across outing requests, announcements, and warden decisions

## Workflow Examples
- **Student Outing Flow:**
  1. Student fills an outing request form.
  2. Request is saved in Firestore under `/outings/requests`.
  3. Warden receives the request in real-time.
  4. Warden approves or rejects the request.
  5. Student gets an instant update via notifications.
  6. Approved requests generate a QR code for gate verification.

- **Warden Decision Flow:**
  1. Warden logs into the dashboard.
  2. Views all pending student requests.
  3. Approves or rejects with a single tap.
  4. Students receive real-time updates on their status.
  5. Gate staff scan QR codes for approved students.


## 📍 Exhibition Highlight

> 📆 **Presented at App Development Exhibition – NMIMS Shirpur on April 14th, 2024**  
> Received appreciation for innovation, chatbot integration & institutional utility.

---

## 🤝 Let's Connect!

If you'd like to collaborate, try out the app, or contribute, feel free to connect with me here:

LinkedIn (www.linkedin.com/in/
hrushikumbhare
)

---
<img width="346" height="770" alt="b" src="https://github.com/user-attachments/assets/2bd9d9db-b45b-4bd7-9867-8f075cf7cca5" />

<img width="342" height="767" alt="c" src="https://github.com/user-attachments/assets/c562ac6f-d2ed-477e-9c28-72a0cc29a409" />

<img width="346" height="772" alt="d" src="https://github.com/user-attachments/assets/353bc598-ba8f-4217-889d-bb68b8c1ae8c" />

<img width="342" height="761" alt="e" src="https://github.com/user-attachments/assets/73f705f3-4669-4b35-8f47-ba6a23f59926" />

<img width="340" height="771" alt="f" src="https://github.com/user-attachments/assets/0e192e2b-745b-4531-b2bf-9f7867d8a7ff" />

<img width="342" height="768" alt="g" src="https://github.com/user-attachments/assets/395c6c9c-012b-4f21-8acf-f313f8e62a9c" />

<img width="348" height="776" alt="h" src="https://github.com/user-attachments/assets/1a570d45-9abd-48e1-aaee-9bd8b09188d1" />

<img width="342" height="771" alt="i" src="https://github.com/user-attachments/assets/5b0638e1-816e-4503-b1db-13a11930a1f5" />

<img width="340" height="771" alt="j" src="https://github.com/user-attachments/assets/bb2340e0-0dbd-4c24-92c1-18cc299bf4db" />

<img width="342" height="772" alt="k" src="https://github.com/user-attachments/assets/3461bff0-96b5-4d77-8a33-f6524a9ee02d" />

<img width="347" height="770" alt="l" src="https://github.com/user-attachments/assets/8bd55cd0-44b3-4a83-8fd8-ad5ed1855dd3" />

<img width="350" height="767" alt="n" src="https://github.com/user-attachments/assets/6fd1cef8-f2b9-4244-9feb-c8a836a144bc" />

<img width="352" height="772" alt="m" src="https://github.com/user-attachments/assets/8918856f-bcbd-4d5a-b31e-6abd3d2ccd33" />

<img width="343" height="776" alt="o" src="https://github.com/user-attachments/assets/8fd81646-b72b-4564-b815-107753fa38b4" />

<img width="340" height="770" alt="q" src="https://github.com/user-attachments/assets/c9b74305-bfcd-45a3-8991-c5dcbd54f07a" />

<img width="348" height="773" alt="s" src="https://github.com/user-attachments/assets/d87d91b3-fef1-4fe0-925a-b88cadd693ea" />

<img width="347" height="768" alt="r" src="https://github.com/user-attachments/assets/03d09eac-e62c-4460-8cb8-21fbe176e14f" />

<img width="346" height="771" alt="t" src="https://github.com/user-attachments/assets/faa75292-b25f-4dc1-9d5f-59bfb06e30fe" />



















## 📦 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/NMIMS-Outing-Manager.git
