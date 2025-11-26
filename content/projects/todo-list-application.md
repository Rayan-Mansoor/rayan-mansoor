---
title: "Todo List Application"
summary: "A cross-platform desktop Todo app with deadline tracking, search, local persistence, and email export, built with Java and JavaFX."
dateString: 2022
draft: false
tags: ["Java", "JavaFX", "FXML", "Maven", "JavaMail", "Desktop App", "Todo", "Productivity", "CRUD"]
showToc: false
weight: 206
cover:
    image: "projects/TODO-List.jpg"
--- 

### 🔗 [GitHub Repo – Todo List Application](https://github.com/Rayan-Mansoor/To-do-List-Java-FXML)

## Description

A **desktop Todo list application** built with **Java** and **JavaFX**, designed to run on **Windows, macOS, and Linux**.

The app focuses on practical task management: users can create detailed tasks with deadlines, search and update them easily, and even **email their entire Todo list** directly from the app. It combines a clean UI with persistent local storage so tasks are always restored on the next launch.

---

## Key Features

- **Rich Task Details & Deadlines**  
  Create tasks with subject, description, location, date, and time (with AM/PM) for proper schedule-style usage.

- **Search, Update & Delete**  
  Quickly search tasks by subject, load them back into the form, update details, or delete completed items.

- **Persistent Local Storage**  
  Todos are saved automatically to a local data file and restored on startup, so nothing is lost between sessions.

- **Email Your Todo List**  
  Send the current Todo list via email using SMTP, handy for backing up tasks or sharing plans.

- **Modern JavaFX UI**  
  Clean, styled interface with dialogs and form-based workflows, designed for clarity and ease of use.

- **Cross-Platform Desktop App**  
  Built and run via Maven, working across **Windows, macOS, and Linux** with the same codebase.

---

## Tech Stack

- **Language:** Java  
- **UI:** JavaFX + FXML  
- **Build & Dependencies:** Maven  
- **Email:** JavaMail API with environment-based SMTP configuration (`dotenv`)  
- **Persistence:** Local file storage using Java serialization  