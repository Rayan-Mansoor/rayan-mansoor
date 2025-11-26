---
title: "Zephyr – E-Commerce App"
summary: "Zephyr is a Firebase-backed e-commerce solution with a customer-facing Android app and an admin panel for managing products, orders, and analytics."
dateString: 2024
draft: false
tags: ["Kotlin", "Android", "Jetpack Compose", "XML", "Firebase", "Realtime Database", "Cloud Storage", "Stripe", "Google Maps", "Google Sign-In"]
showToc: false
weight: 204
cover:
    image: "projects/Android-Ecommerce.jpg"
--- 

### 🔗 [GitHub Repo – Android E-Commerce App](https://github.com/Rayan-Mansoor/Android-Ecommerce-App-With-Admin-Panel)

## Description

**Zephyr** is a full-featured **e-commerce application** built for Android with a companion **admin panel**, all backed by **Firebase**.

The customer app focuses on a smooth shopping experience with secure authentication, modern search (including voice), and seamless checkout via **Stripe**. The admin side gives operators tools to manage catalog data, monitor sales, and respond to customers in real time.

Firebase Realtime Database and Cloud Storage sit at the core, providing live updates across users and efficient image hosting for products and banners.

---

## Key Features

### Customer Experience

- **Secure Authentication & Google Sign-In**  
  Customer login powered by **Firebase Authentication**, with support for email/password and **Google Sign-In** for a faster onboarding flow.

- **Modern Search & Voice Input**  
  Dynamic keyboard search with real-time suggestions plus **voice search**, so users can find products or services hands-free.

- **Promo Codes & Discounts**  
  Support for **promo / discount coupons** at checkout to run campaigns, reward loyal users, and increase conversion.

- **Customer Reviews & Ratings**  
  Built-in rating and review system so customers can leave feedback on products/services, helping build trust and social proof.

- **Real-Time Updates**  
  Powered by **Firebase Realtime Database**, users see live changes such as stock updates, order status changes, or new offers without manual refresh.

### Admin & Operations

- **Admin Authentication**  
  Separate, secure access for admins to manage the platform, backed by Firebase Authentication rules.

- **Admin Panel with Sales Analytics**  
  Admin interface with **sales statistics, charts, and summaries** to monitor performance, track revenue, and understand customer behavior.

- **Catalog & Content Management**  
  Admins can manage products/services, pricing, offers, and coupons without redeploying the app.

### Platform Integrations

- **Stripe Payments**  
  Integrated **Stripe** for secure, in-app payment processing, supporting saved payment methods and real-time confirmation.

- **Google Maps Integration**  
  Embedded **Google Maps** to support location-based features such as showing user location, nearby service providers, and navigation routes.

- **Cloud Storage for Media**  
  Product images and other media are stored in **Firebase Cloud Storage**, optimized for scalability and fast delivery.

---

## Tech Stack

- **Platform:** Android (Kotlin)  
- **UI:** XML layouts and Jetpack Compose components  
- **Backend-as-a-Service:**  
  - Firebase Authentication  
  - Firebase Realtime Database  
  - Firebase Cloud Storage  
- **Payments:** Stripe Android SDK  
- **Maps & Identity:** Google Maps SDK, Google Sign-In  
- **Networking & APIs:** REST-style endpoints layered over Firebase data where needed  