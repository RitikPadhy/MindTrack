# MindTrack – Monorepo Overview

MindTrack is an integrated mental-wellness ecosystem designed to help doctors, therapists, and caregivers monitor and support patients’ mental health in real time. This monorepo provides a structured home for all major components of the system.

---

## 1. MindTrack Flutter (Mobile App)
**Location:** `mindtrack-flutter/`  
**Original Repo:** https://github.com/RitikPadhy/MindTrack---Flutter  

This is the **patient-facing mobile application**, built with Flutter.  
It provides the primary user experience for individuals whose mental health is being monitored.

### Key Features
- Daily mood tracking & emotional check-ins  
- Wellness tasks, journaling & activity reminders  
- Insightful analytics: trends, patterns, alerts  
- Cloud sync with offline support  
- Secure authentication and encrypted data storage  

---

## 2. MindTrack Backend (Node.js)
**Location:** `mindtrack-backend/`  
**Original Repo:** https://github.com/RitikPadhy/MindTrack---Backend  

This serves as the **central backend system** that connects all platforms.

### Key Responsibilities
- User, patient & therapist management  
- REST API for mobile & web platforms  
- Mental-health analytics & trend scoring  
- Alerts & automated notification system  
- Role-based access & permission handling  
- Ready for ML model integration (future expansion)  

---

## 3. MindTrack Web Interface (Monitoring Dashboard)
**Location:** `mindtrack-web-interface/`  
**Original Repo:** https://github.com/RitikPadhy/MindTrack---Web-Interface  

This is the **doctor/therapist-facing dashboard** used to monitor and manage patients.

### Key Features
- Real-time patient health dashboard  
- Mood trends, activity logs & risk scoring  
- Patient list, search & status overview  
- Intervention tools: notes, recommendations, feedback  
- Secure admin panel for clinics/organizations  

---

## 4. MindTrack Monorepo (This Repository)
This repository functions as the **meta project** that organizes all components.

### Purpose of This Monorepo
- Provide unified structure for Flutter, Backend & Web  
- Centralize documentation & architecture decisions  
- Maintain setup guides and shared configs  
- Track development roadmaps across all platforms  
- Make contribution easier with one consolidated codebase  

---

## Future Additions (Planned)
- **MindTrack ML Models:** Predictive analytics & anomaly detection  
- **MindTrack Admin Console:** Organization-wide controls  
- **MindTrack Design System:** Shared UI/UX components for web & mobile  

---

Feel free to customize or expand this based on your roadmap!