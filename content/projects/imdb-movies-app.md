---
title: "IMDb Movies List App"
summary: "An Android app that fetches movies from an IMDb API, caches them locally with Room, and lets users browse, review, and rate titles offline."
dateString: 2022
draft: false
tags: ["Kotlin", "Java", "Groovy", "XML", "Jetpack Compose", "Android", "Room", "SQLite", "REST API"]
showToc: false
weight: 204
cover:
    image: "projects/IMDB-Movies-List.jpg"
--- 

### 🔗 [GitHub Repo – IMDb Movies List App](https://github.com/Rayan-Mansoor/IMDb-Clone-App-Android)

## Description

An **Android movies app** that pulls data from an **IMDb-powered REST API**, stores it in a local **Room** database, and then serves content from the device for fast, offline-friendly browsing.

Users can:

- Explore a list of movies with key details  
- Open movie detail screens for full information  
- Add their own **reviews and ratings**, layered on top of API data  

The app is designed around an **offline-first** approach: the network is used to seed and refresh data, but day-to-day usage works smoothly from local storage.

---

## Key Features

- **Offline-First Movie Catalog**  
  On first launch, the app fetches movies from the IMDb API and stores them in **RoomDB**. Subsequent launches read from the local database, making browsing fast and resilient to network issues.

- **Full CRUD on Movie Data & Reviews**  
  Implemented SQL/Room-based CRUD operations to manage movie records and user reviews, ensuring data integrity and consistent updates.

- **User Ratings & Reviews**  
  Users can rate movies and leave short reviews, adding a basic social layer on top of the API data.

- **Movie Detail Screens**  
  Movie list items lead to a detailed view with richer information (description, meta data, etc.), presented in a clean, readable layout.

- **Performance & Stability**  
  Optimized queries and Room usage for quick data access, plus robust error handling and validation to avoid crashes or corrupt records.

- **User-Friendly UI**  
  A straightforward, scrollable movie list with detail views designed for easy navigation and discovery.

---

## Tech Stack

- **Languages:** Kotlin (core app), Java/Groovy (Gradle and build tooling)  
- **Platform:** Android  
- **UI:** XML layouts and/or Jetpack Compose components (hybrid setup)  
- **Local Storage:** Room (on top of SQLite) for persisting movie and review data  
- **Networking:** REST API integration to fetch movie data from an IMDb-backed endpoint  
- **Architecture:** Separation of concerns between data (Room + API) and UI layers to keep the code maintainable