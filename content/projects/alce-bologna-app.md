---
title: "ALCE – Study Italian in Bologna"
summary: "Official student app for ALCE Bologna, bringing lessons, activities, accommodation, food ordering, language tests, and documents into one mobile experience."
dateString: 2025
draft: false
tags: ["Flutter", "Dart", "Android", "iOS", "Firebase", "Firestore", "Firebase Auth", "Stripe", "Google Maps", "Riverpod", "Provider", "Education"]
showToc: false
weight: 201
cover:
    image: "projects/ALCE-Bologna.png"
---

### 🔗 [Available on Google Play Store](https://play.google.com/store/apps/details?id=com.alce.studyitalian)

## Description

**ALCE** is the official mobile app for students at **ALCE Bologna** (Academic Language Centre of Europe). It centralizes all the key services students need while studying Italian in Bologna — from class schedules and activities to accommodation details, food ordering, and language tests.

The goal is to give students a **single, intuitive place** to manage their life at ALCE, so they can spend less time dealing with admin and more time learning Italian and enjoying the city.

---

## My Role

- Designed and developed the **Flutter mobile app** for both **Android & iOS**
- Integrated **Firebase** for authentication, data storage, and app stability
- Implemented **Stripe payments** and a token-based wallet for food ordering
- Built **Google Maps experiences** for accommodation and school locations
- Structured the app with **Provider + Riverpod** for predictable state management

---

## Key Features

1. **Student Profile & Onboarding**  
   - View and update personal details, contact information, and emergency contacts  
   - Keep student data consistent with ALCE's internal systems via Firebase-backed models

2. **Lessons & Activities**  
   - Access the **weekly lesson schedule** and daily programme directly in the app  
   - Browse upcoming school activities and cultural events around Bologna  
   - See rich details for each item: time, location, descriptions, and other metadata

3. **Food, Cart & Wallet**  
   - Explore the food menu with detailed item information  
   - Add items to a cart and complete **secure checkout via Stripe**  
   - Use a built-in **wallet/token system** and review order history

4. **Documents & Reports**  
   - Access and download important documents, reports, and certificates  
   - Centralized, digital-first way for students to retrieve official school paperwork

5. **Accommodation & Arrival**  
   - See accommodation details and arrival instructions in one place  
   - Open **interactive maps** showing both accommodation and school locations  
   - Help new students navigate Bologna with less friction on day one

6. **Language Tests & Progress**  
   - Complete language tests directly inside the app  
   - Track results over time to understand progress and current level  
   - Give ALCE a digital touchpoint for assessment and continuous improvement

7. **Stay Connected**  
   - Meet the team via the "Meet Us" section  
   - Quickly reach the school through **Contact Us** and **Emergency Contact** screens  
   - Receive important promos and announcements so students don't miss key updates

---

## Tech Stack

- **Framework:** Flutter (Dart)  
- **Platforms:** Android & iOS  
- **Backend & Infra:** Firebase (Auth, Firestore, Storage, Crashlytics, App Check)  
- **Payments:** Stripe integration via Flutter Stripe  
- **Maps & Location:** Google Maps  
- **State Management:** Provider & Riverpod  
- **Architecture:** Modular screens, shared components, and a services layer for Firebase, Stripe, documents, and orders

---

ALCE combines school operations, student services, and payments into a single mobile experience — tailored specifically for international students learning Italian in Bologna.