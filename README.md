# TThaoPM Developer Ecosystem

A unified ecosystem of full-stack developer tools, real-time applications, and productivity utilities — built and maintained by **Phạm Minh Thảo** to support learning, experimentation, and scalable product development.

---

## Table of Contents

1. [Overview](#overview)  
2. [Projects](#projects)  
   * [1. Video Meeting App](#video-meeting-app)  
   * [2. API Tester Tool](#api-tester-tool)  
   * [3. Realtime Chat App](#realtime-chat-app)  
   * [4. Ride Booking Application](#ride-booking-application)  
3. [Tech Stack](#tech-stack)  
4. [Contribution & Future Plan](#contribution--future-plan)  
5. [Author](#author)  

---

## Overview

The **TThaoPM Ecosystem** is a suite of open-source projects designed to:

- Enhance real-time communication and interactivity
- Facilitate backend/API development and testing
- Provide hands-on experience with full-stack technologies
- Promote modular, clean, and scalable codebases for production-ready apps

Each project is independent, yet follows shared design principles in UI/UX, architecture, and development workflows.

---

## Projects

### 1. Video Meeting App

A Google Meet–like full-stack video conferencing platform powered by **Next.js**, **Clerk**, and **Stream Video SDK**.

- Instant or scheduled meetings
- Personal meeting rooms
- Real-time mic/cam controls, screen sharing, emoji reactions
- Recording and playback
- Clerk-based secure authentication

**Repository:** [tthaopm-meeting](https://github.com/Trunks-Pham/tthaopm-meeting)  
**Live Demo:** [https://thaopm-rtc-meeting.onrender.com](https://thaopm-rtc-meeting.onrender.com)

---

### 2. API Tester Tool

A lightweight frontend-only app to test HTTP APIs quickly.

- Support for all RESTful methods
- See response time, status, size
- Download response as JSON
- Minimalist UI built with **Vanilla JS**, **Bootstrap**, and **Snowpack**

**Repository:** [tthaopm-api-tester](https://github.com/Trunks-Pham/tthaopm-api-tester)

---

### 3. Realtime Chat App

A MERN-based chat app with WebSocket communication and state management.

- JWT-based authentication
- Socket.IO for live messaging
- User presence detection
- Zustand state management
- Styled with TailwindCSS and DaisyUI

**Repository:** [tthaopm-chat](https://github.com/Trunks-Pham/tthaopm-chat)

---

### 4. Ride Booking Application

A real-time ride booking platform using interactive maps, driver assignment logic, and real-time tracking.

- Click-to-select pickup and destination on map
- Assigns nearest driver automatically
- Tracks driver in real-time via Socket.IO
- Interactive route rendering with Leaflet Routing Machine
- Booking panel with driver info and ride status

**Frontend:** React + Tailwind + Leaflet  
**Backend:** Node.js + Express + Socket.IO  

**Repository:** [ride-booking-application](https://github.com/Trunks-Pham/ride-booking-application)

---

## Tech Stack

The ecosystem adopts a modern, consistent, and scalable technology stack:

- **Frontend:** React, Next.js, Tailwind CSS, DaisyUI, Leaflet, Leaflet Routing Machine  
- **Backend:** Node.js, Express.js, MongoDB  
- **Authentication:** Clerk, JWT  
- **Real-time Communication:** Socket.IO, Stream SDK  
- **Dev Tools & Tooling:** TypeScript, Zustand, Vite, Snowpack, Axios  

---

## Contribution & Future Plan

### Roadmap Highlights

- [ ] Centralized Clerk authentication across all projects  
- [ ] CI/CD pipelines for auto-deployment  
- [ ] Docker support and ecosystem self-hosting  
- [ ] Chat App enhancements (media sharing, message search)  
- [ ] Ride App improvements (multi-rides, traffic-aware routing)  
- [ ] Merge API Tester into a unified Dev Dashboard  

### Contribution

Want to contribute? Feel free to:

1. Fork the repo  
2. Create a feature branch  
3. Open a pull request with your changes and description  

All contributions are reviewed and appreciated.

---

## Author

**Phạm Minh Thảo**  
Full-stack Developer | Technical Writer | Community Contributor  

- [LinkedIn](https://www.linkedin.com/in/mtpe-minhthaopham/)  
- [GitHub](https://github.com/Trunks-Pham)

---

## License

All projects in this ecosystem are open-source and released under the [MIT License](https://opensource.org/licenses/MIT).

---

## Notes

This is the central README file for the **TThaoPM Developer Ecosystem**.  
Each project includes its own detailed documentation in its respective repository.

Future updates will be reflected here as the ecosystem grows.
