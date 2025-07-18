# StageLink - Music Performance Booking & Fan Monetization Platform

**Founder:** Marquez Edward Ross  
**Platform:** Web & Mobile (Progressive Web App)  
**Repository:** stagelink-platform

---

## ✨ Vision
StageLink is a modern platform built for independent artists to manage performance bookings, monetize fan interactions, and run virtual events all in one place. Whether you're an MC, poet, rock artist, or R&B vocalist, StageLink gives you the tools to control your gig calendar, host listening parties, and accept paid webcam fan requests.

---

## 🚀 Features
- Artist Sign-up and Public Profile
- Genre-Based Booking (Hip-Hop, R&B, Rock, Spoken Word, Blues)
- Fan Booking Page + Custom Calendar
- Webcam Interactions on Artist Terms (Zoom-style)
- Listening Party Scheduling
- Revenue Split (80% Artist / 20% Platform Admin)
- Admin Dashboard for Marquez Edward Ross

---

## 📦 Tech Stack
- **Frontend:** HTML/CSS/JS or React (Acode + F-Droid ready)
- **Backend:** Node.js + Express OR Django REST
- **Database:** PostgreSQL
- **Authentication:** Firebase Auth
- **Payments:** Stripe Connect (for split payouts)
- **Smart Contracts:** Solidity (RemixIDE)
- **Video:** WebRTC or Zoom SDK integration

---

## 📁 Folder Structure
---

## 📱 Mobile Dev Notes (Google Pixel)
- Development Environment:
  - Termux (Node.js, Git, NPM, PostgreSQL)
  - Acode (for editing HTML/CSS/JS/Env files)
  - RemixIDE (browser-based smart contract editing)
  - GitHub Mobile App or Termux Git
- Testing:
  - Run frontend in Termux, test in Chrome
  - Use `localhost` preview extensions or forward with `ngrok` for external test

---

## 📥 Installation
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/stagelink-platform.git

# Navigate to frontend
cd client && npm install

# Navigate to backend
cd ../server && npm install

# Create .env files in /config based on .env.sample

# Run frontend (Dev)
cd client && npm run dev

# Run backend (Dev)
cd ../server && npm run dev

---
