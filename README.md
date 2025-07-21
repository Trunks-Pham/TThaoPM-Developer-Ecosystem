# TThaoPM Developer Ecosystem

A unified ecosystem of full-stack developer tools, real-time applications, and productivity utilities — built and maintained by **Minh Thảo Phạm** to support learning, experimentation, and scalable product development.

---

## Table of Contents

1. [Overview](#overview)
2. [Projects](#projects)

   * [1. Video Meeting App](#video-meeting-app)
   * [2. API Tester Tool](#api-tester-tool)
   * [3. Realtime Chat App](#realtime-chat-app)
3. [Tech Stack](#tech-stack)
4. [Contribution & Future Plan](#contribution--future-plan)
5. [Author](#author)

---

## Overview

The **TThaoPM Ecosystem** is a suite of projects aimed at empowering developers and learners with:

* Real-time communication capabilities
* Backend service testing
* Hands-on experience with modern web stacks (Next.js, TypeScript, MongoDB, WebSocket, and more)
* Clean UI/UX with scalable code architecture

It includes self-contained, open-source apps that are modular yet share design philosophy and best practices.

---

## Projects

### 1. Video Meeting App

A Google Meet–like full-stack video conferencing platform powered by **Next.js**, **Clerk**, and **Stream Video SDK**.

* Start instant or scheduled meetings
* Personal meeting rooms
* Real-time controls: mic/cam, screen share, reactions
* Recordings and past meeting history
* Secure login (Clerk) and real-time data (GetStream)

**Repository:** [tthaopm-meeting](https://github.com/Trunks-Pham/tthaopm-meeting)
**Production:** [https://thaopm-rtc-meeting.onrender.com](https://thaopm-rtc-meeting.onrender.com)

---

### 2. API Tester Tool

A lightweight frontend-only app that helps developers test APIs directly from the browser.

* Supports all major HTTP methods: GET, POST, PUT, PATCH, DELETE
* View status code, response time, size
* Download JSON response
* Built using **Vanilla JS**, **Bootstrap**, and **Snowpack**

**Repository:** [tthaopm-api-tester](https://github.com/Trunks-Pham/tthaopm-api-tester)

---

### 3. Realtime Chat App

A MERN-based chat application with modern state management and WebSocket communication.

* Authentication via JWT
* Real-time messaging (Socket.io)
* Online user status
* Zustand for state management
* Clean UI with **TailwindCSS** + **DaisyUI**

**Repository:** [tthaopm-chat](https://github.com/Trunks-Pham/tthaopm-chat)

---

## Tech Stack

The ecosystem adopts a modern, consistent, and scalable stack:

* **Frontend:** Next.js, React, Tailwind CSS, DaisyUI
* **Backend:** Node.js, Express.js, MongoDB
* **Authentication:** Clerk, JWT
* **Real-time:** Socket.IO, GetStream SDK
* **Dev Tools:** TypeScript, Zustand, Snowpack, Vite

---

## Contribution & Future Plan

### Roadmap Highlights:

* [ ] Centralized user authentication via Clerk across projects
* [ ] CI/CD setup for all repositories
* [ ] Dockerize and self-host entire ecosystem
* [ ] Extend Chat App with file sharing, image preview
* [ ] Integrate API Tester into developer dashboard

### Contribution

If you'd like to contribute, clone any repo, create a new branch, and submit a pull request with detailed description.

---

## Author

**Pham Minh Thao**
Full-stack developer | Technical Writer | Community Contributor
[LinkedIn Profile](https://www.linkedin.com/in/mtpe-minhthaopham/)
[GitHub](https://github.com/Trunks-Pham)

---

## License

All projects in this ecosystem are open-source and released under the [MIT License](https://opensource.org/licenses/MIT).

---

### Notes

This README is the unified entry point for all individual project READMEs. Each sub-project contains detailed instructions in its own repository. Future updates to this document will reflect changes across all TThaoPM ecosystem apps.
