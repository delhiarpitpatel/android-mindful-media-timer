# Project Brief: Mindful Media Timer (Android App)

This repository contains the initial planning and project brief for a new Android application I am designing.

---

### ## The Problem

Recently, I experienced a common frustration: I fell asleep while listening to a media app on my phone. The app continued to run all night, consuming my entire 1.5GB daily mobile data plan. This is a real-world annoyance with no simple, app-specific solution.

### ## The Proposed Solution

The "Mindful Media Timer" will be a lightweight background utility for Android that allows users to set a global or per-app "usage timer."

**Core Features (MVP):**
*   Run a persistent background service to monitor the foreground application.
*   Allow the user to set a specific time limit (e.g., 60 minutes).
*   When the timer for a specific media app expires, the utility will trigger a user-configurable action (e.g., a loud notification, pausing the media, or turning off WiFi/Mobile Data).

### ## Tech Stack & Learning Goals

This project will serve as my practical deep dive into native Android development.
*   **Language:** Java / Kotlin
*   **Key Android Concepts:** Background Services, System Notifications, App Usage API.

### ## Current Status

**Ideation & Planning Phase.** This repository currently serves as the project brief and a placeholder for future development.
