# 🎓 SceneIt

*A campus event discovery platform built to make student organizations more visible and campus life more connected.*

![Status](https://img.shields.io/badge/Status-In%20Development-success)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-blue)
![Stack](https://img.shields.io/badge/Stack-React%20Native%20%7C%20Firebase-orange)

---

## Overview

SceneIt is a mobile application that helps university students discover campus events, connect with student organizations, and save activities they're interested in.

The idea originated from a common problem on campus: event information is scattered across Instagram pages, emails, Discord servers, and flyers, causing many students to miss opportunities simply because they never knew they existed.

SceneIt centralizes campus events into one platform while providing organizations with a streamlined way to promote and manage their events.

As **Tech Lead**, I designed much of the application's architecture, implemented core product features, coordinated development across teammates, and managed our GitHub workflow.

---

## Features

### Student Experience

* Browse upcoming campus events
* Search by event or organization
* Save favorite events
* Like and bookmark events
* View event details including:

  * Date & time
  * Location
  * Description
  * Registration links
  * Event categories
* Personalized event discovery

---

### Organization Experience

Student organizations can:

* Create new events
* Upload event banners
* Edit existing events
* Manage event information
* Reach students through a centralized platform

---

### Admin Dashboard

The platform includes an administrator interface for managing platform content.

Current capabilities include:

* Create events
* Edit events
* Delete events
* Manage uploaded images
* Control administrator access

---

## Tech Stack

### Frontend

* React Native
* Expo
* TypeScript
* React Navigation

### Backend

* Firebase Authentication
* Cloud Firestore
* Firebase Storage

### Additional Tools

* Expo Image Picker
* Firebase Cloud Storage
* GitHub
* Figma
* Google Analytics (planned)

---

## Architecture

The application uses a modular architecture centered around React Context providers.

### Authentication

* Firebase Authentication
* Protected routes
* Role-based access (Admin/User)

### Data Layer

* Cloud Firestore
* Real-time listeners using `onSnapshot`
* Centralized event state management

### Storage

* Firebase Storage
* Optimized image uploads
* Banner image hosting

---

## Technical Highlights

### Real-Time Updates

Implemented Firestore listeners so newly created or updated events immediately appear throughout the application without requiring refreshes.

---

### Event Management

Built complete CRUD functionality allowing organizations to:

* Create events
* Update event details
* Upload banners
* Modify event information
* Delete outdated events

---

### Image Upload Pipeline

Implemented an optimized upload workflow that:

* Compresses images before upload
* Uploads to Firebase Storage
* Stores download URLs in Firestore
* Dynamically renders banners throughout the app

---

### Search System

Developed search functionality supporting:

* Event search
* Organization search
* Live filtering
* Empty state handling

---

### Favorites System

Designed a scalable favorites architecture allowing students to save events while keeping user preferences synchronized with Firestore.

---

### Role-Based Permissions

Implemented role-based rendering that restricts administrative functionality to authorized users while keeping the student experience simple and secure.

---

## Challenges

Some of the engineering problems solved during development include:

* Designing scalable Firestore data structures
* Managing real-time application state
* Optimizing image uploads for mobile devices
* Synchronizing user data across multiple screens
* Implementing protected admin functionality
* Handling offline/loading states gracefully
* Maintaining clean component architecture as the application scaled

---

## My Contributions

As Tech Lead, I was responsible for:

* Designing the application architecture
* Building core frontend features
* Implementing Firebase integration
* Developing authentication and user management
* Creating event creation and editing workflows
* Building the favorites system
* Implementing image uploads
* Managing GitHub repositories and pull requests
* Planning engineering milestones
* Coordinating work across developers and designers

---

## Roadmap

Future development includes:

* Push notifications
* Event recommendations
* QR code event check-in
* Club dashboards
* Analytics for organizations
* Event attendance tracking
* Calendar integration
* AI-powered event recommendations

---

## Lessons Learned

SceneIt has been my largest full-stack project to date and has taught me how to:

* Design scalable application architecture
* Lead a software engineering team
* Balance product decisions with technical constraints
* Build production-ready mobile applications
* Work effectively with Firebase services
* Manage collaborative development using GitHub

---

## Screenshots

*Screenshots and demos coming soon.*

---

## Contact

Feel free to connect with me on LinkedIn or explore my other repositories to see additional projects involving AI, web development, and full-stack software engineering.
