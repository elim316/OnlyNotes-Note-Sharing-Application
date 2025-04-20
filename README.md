# OnlyNotes – Android Note-Sharing App

![Project Type](https://img.shields.io/badge/Project-Mobile%20App%20Dev-blue)
![Built With](https://img.shields.io/badge/Built%20With-Kotlin-yellow)
![UI Framework](https://img.shields.io/badge/UI-Jetpack%20Compose-purple)
![Backend](https://img.shields.io/badge/Backend-Firebase-orange)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Android-lightgrey)

**OnlyNotes** is an Android application designed to help students collaborate and share study notes more effectively. The app supports creating and editing notes, joining study groups based on location, and participating in real-time discussions.

---

## Features

- Create, edit, and delete personal notes
- Attach images and files to notes
- Browse/search notes by subject
- Like and bookmark favorite notes
- Create and join study groups (location-based)
- Group chats and discussion boards
- Activity feed showing user interactions
- User profile management and authentication
- Settings and help/support pages

---

## My Role & Contributions

I was responsible for designing and implementing the **Student Settings Page**, a key feature that allows users to manage their personal preferences and account settings. My contributions included:

- Building the `SettingsPage.kt` UI using **Jetpack Compose**
- Integrating **Firebase Authentication** for secure logout and account handling
- Managing app navigation and state persistence tied to user settings
- Applying the **MVVM architecture** with clean separation of concerns
- Ensuring the page was accessible, responsive, and consistent with app theming

Additionally, I contributed to:
- Testing UI components using Jetpack Compose Preview tools
- Participating in GitHub pull requests, code reviews, and version control workflows

---

## Tech Stack

| Layer          | Tech                                               |
|----------------|----------------------------------------------------|
| **Language**   | Kotlin                                             |
| **UI**         | Jetpack Compose, Material Design 3                |
| **Backend**    | Firebase (Auth, Firestore, Storage)               |
| **Location**   | Google Maps SDK                                   |
| **Architecture** | MVVM (Model-View-ViewModel) Pattern             |
| **Tools**      | Android Studio, Git, GitHub                       |

---

## Project Structure Overview

```
├── data/
│   ├── Note.kt, NoteRepository.kt, NoteViewModel.kt
│   ├── User.kt, Group.kt, Activity.kt
│   └── Firebase services (Auth, Database)
├── ui/
│   ├── view/
│   │   ├── NoteDetailsPage.kt, NoteEditPage.kt
│   │   ├── LoginPage.kt, HomePage.kt, GroupsPage.kt
│   │   └── DiscussionPages, ActivityPage, etc.
│   └── theme/
├── MainActivity.kt
├── NavGraph.kt

```

---

## Supporting Media & Documentation

- **Figma Prototype** – [View the UI Prototype](https://www.figma.com/proto/r0Tx8ARbPLCh8U8sTVIErH/MAD-hi-fi-prototype?node-id=2002-362&t=fetugRO0q12XJyfM-1)
- **Project Proposal** – [Read the Proposal on Google Docs](https://docs.google.com/document/d/166Ak3lWIN5_0YhMQozIYFEayZ9GWFfbsJFwN14zTork/edit?usp=sharing)
- **Final Report** – [View the Final Report on Google Docs](https://docs.google.com/document/d/17g03RTRBUBJf28ewV6zraVqrTs5BwE7nGkVNHteXadI/edit?usp=sharing)

> _These resources highlight the planning, design thinking, and final evaluation that went into the OnlyNotes project._

---

## What I Learned

- Clean architecture using **MVVM** in a mobile context
- Firebase integration for real-time updates and secure data handling
- Jetpack Compose UI patterns and state management
- Designing intuitive navigation using Android Navigation Components
- Working in a version-controlled, team-based environment with GitHub

---

## Note

This is a **case study repository**. The original codebase is private under the [INF2007 course](https://github.com/inf2007/inf2007-team23-2024). If you're interested in learning more, feel free to reach out or explore my related public projects.

---

## Let’s Connect

Want to learn more about OnlyNotes or collaborate on similar mobile projects?  
Feel free to [reach out](mailto:eliaslim316@gmail.com) or check out more of my work on [GitHub](https://github.com/elim316).

---

