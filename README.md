# Cloud-Based Doctor Appointment System (MediCloud)

A responsive, single-page web application simulating a **Cloud-Based SaaS Doctor Appointment & Telehealth Platform**.

## 🚀 Key Features

1. **Patient Discovery & Search**:
   - Filter doctors by specialty (Cardiology, Dermatology, Pediatrics, Neurology, Orthopedics, General Medicine).
   - Real-time search by doctor name, hospital, or specialty.

2. **Appointment Scheduling & Persistence**:
   - Interactive booking modal with date and time slot pickers.
   - Real-time data persistence using browser `localStorage` (simulating Cloud Database).
   - Dynamic QR Code Digital Check-In Pass generation with downloadable JSON summary.

3. **Doctor & Admin Analytics Dashboard**:
   - Master ledger for tracking all appointments.
   - Dynamic visual analytics charts powered by Chart.js (Specialty distribution and Mode ratio).

4. **Telehealth Virtual Room**:
   - Integrated consultation interface with session timer and P2P video layout simulation.
   - Interactive microphone/camera toggles with local webcam integration capability.
   - Clinical note taking and prescription updates saved directly back to the cloud profile.

## 🛠️ Technology Stack

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript (ES6+)
- **Icons & UI**: FontAwesome 6, Chart.js
- **QR Code Engine**: QRCode.js
- **State & Data**: LocalStorage (Cloud DB Simulation)

## 📦 How to Run

1. Extract `medicloud_project.zip`.
2. Open `index.html` directly in any web browser.
3. No build step or backend installation required!
