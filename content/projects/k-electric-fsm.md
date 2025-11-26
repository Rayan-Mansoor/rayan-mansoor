---
title: "K-Electric Field Service Management"
summary: "A web & mobile field service solution for K-Electric, enabling 2,000+ meter readers to manage daily assignments with AI-powered meter reading, maps, and offline sync."
dateString: 2024
draft: false
tags: ["Kotlin", "Android", "Jetpack Compose", "Field Service", "OCR", "Computer Vision", "Maps", "Offline First", "REST APIs"]
showToc: false
weight: 200
cover:
    image: "projects/K-Electric-FSM.png"
---

## Description

This project was delivered to **K-Electric**, the largest electric utility company in Pakistan, as a **field service management solution** consisting of:

- A **web application** for admins and supervisors to manage assignments, users, and reporting  
- A **mobile app** for meter readers in the field to execute and record their daily tasks

I worked on the **Android mobile app** used by **2,000+ meter readers** to efficiently complete their assigned orders. The app focuses on:

- Clear progress visibility  
- Location-aware task execution  
- Fast and accurate meter reading with AI/OCR  
- Reliable operation in low-connectivity environments

---

## My Role

- Developed core features of the **meter reader Android app** using **Kotlin** and **Jetpack Compose**
- Integrated **AI-powered meter reading** using OCR from captured images
- Helped design **offline-first flows** with background synchronization to the central backend and web portal
- Collaborated with backend and web teams to align APIs, data models, and status flows between field and admin sides

---

## Key Features (Mobile App – Meter Readers)

1. **Home Dashboard for Daily Progress**  
   - At-a-glance stats for assigned, completed, and remaining meters  
   - Visual indicators to help meter readers track productivity throughout the day

2. **Map-Based Meter Tracking**  
   - View assigned meters directly on a **map**  
   - Support for **heatmaps** and counts to highlight dense areas and remaining workload  
   - Location-aware navigation to each meter’s coordinates

3. **Guided Meter Reading Workflow**  
   - For each meter, the app shows an **easy-to-fill form** with dropdowns and constrained inputs  
   - Capture **meter images** using the device camera  
   - Integrated **OCR/computer vision** to automatically extract meter readings  
   - Achieved around **93% accuracy**, significantly reducing manual entry errors

4. **Issue Reporting & Copoints**  
   - Meter readers can submit “copoints” directly from the app  
   - Report broken/missing meters, tampering, access issues, and other meter-related problems  
   - Attach notes and photos for better follow-up by supervisors

5. **Offline-First with Seamless Sync**  
   - Full workflow support in **low or no connectivity** areas  
   - Orders, readings, images, and issues are stored locally on the device  
   - Automatic synchronization to the central server and **admin web portal** once connectivity is restored

---

## Tech Stack (Mobile)

- **Language:** Kotlin  
- **UI:** Android Jetpack Compose  
- **Architecture:** ViewModel, repository pattern, dependency injection  
- **Data & Sync:** Local caching with background sync to REST APIs  
- **Maps & Location:** Android location services, map-based visualization of assigned meters  
- **AI & OCR:** Computer vision/OCR pipeline to read meter dials from captured images  