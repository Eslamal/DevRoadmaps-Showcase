# DevRoadmaps Application 🚀

An interactive, feature-rich Android application designed to guide developers through various learning roadmaps. This app is built with modern, industry-standard technologies and architectural patterns, making it a robust tool for self-paced learning.

## Screenshots

| A | B | C |
| :---: | :---: | :---: |
| ![Main Screen Dark Mode](./screenshots/photo_2025-09-09_12-28-40.jpg) | ![Roadmap Detail](./screenshots/photo_2025-09-09_12-28-45.jpg) | ![Step Detail](./screenshots/photo_2025-09-09_12-28-47.jpg) |

| D | E |
| :---: | :---: |
| ![Quiz Screen](./screenshots/photo_2025-09-09_12-28-52.jpg) | ![Settings Screen](./screenshots/photo_2025-09-09_12-28-56.jpg) |

| F | G |
| :---: | :---: |
| ![Quiz Screen](./screenshots/photo_2025-09-09_12-28-59.jpg) | ![Settings Screen](./screenshots/photo_2025-09-09_12-29-02.jpg) |

| H | I |
| :---: | :---: |
| ![Quiz Screen](./screenshots/photo_2025-09-09_12-29-05.jpg) | ![Settings Screen](./screenshots/photo_2025-09-09_12-29-08.jpg) |

| J | K |
| :---: | :---: |
| ![Quiz Screen](./screenshots/photo_2025-09-09_12-29-29.jpg) | ![Settings Screen](./screenshots/photo_2025-09-09_12-29-32.jpg) |

## ✨ Features
- **Dynamic Content:** Fetches all roadmap data from a remote API, with a fallback to local data for offline use.
- **Interactive Learning:**
    - **Quizzes:** Test your knowledge at the end of key steps with multiple-choice questions.
    - **Code Examples:** View practical, syntax-highlighted code snippets with a one-tap copy feature.
    - **Personal Notes:** Add, edit, and delete multiple personal notes for each step to create your own learning journal.
- **Progress Tracking:** Mark steps as complete and visually track your progress on the main screen.
- **Resource Tracking:** Links to external resources are marked as visited after you click on them.
- **Advanced UI:**
    - A beautiful timeline view to visualize roadmap steps.
    - Full Light Mode & Dark Mode support.
    - Multi-language support (English & Arabic).
    - Smooth animations and a clean, intuitive interface built with Material Design 3.
- **Personalization:** A dedicated settings screen to control the theme, language, and reset progress.
- **Powerful Search :** Easily search across all roadmaps .

## 🛠 Tech Stack & Architecture
This project is a showcase of modern Android development best practices.
- **Language:** 100% [**Kotlin**](https://kotlinlang.org/)
- **Architecture:** [**MVVM**](https://developer.android.com/topic/architecture) (Model-View-ViewModel) & Repository Pattern
- **Core Components:**
    - [**Jetpack ViewModel**](https://developer.android.com/topic/libraries/architecture/viewmodel): For managing UI-related data in a lifecycle-conscious way.
    - [**Jetpack LiveData**](https://developer.android.com/topic/libraries/architecture/livedata): For building observable, UI-driven data objects.
    - [**Room Database**](https://developer.android.com/training/data-storage/room): For robust local data persistence (progress, notes, etc.).
- **Networking:**
    - [**Retrofit**](https://square.github.io/retrofit/): For type-safe HTTP calls to the remote API.
    - [**Gson**](https://github.com/google/gson): For parsing JSON data.
- **Asynchronous Programming:**
    - [**Kotlin Coroutines**](https://kotlinlang.org/docs/coroutines-overview.html): For managing background threads and asynchronous operations gracefully.
- **UI:**
    - XML Layouts & Material Design 3
    - `RecyclerView` with `ListAdapter` and `DiffUtil` for efficient list management.
    - `WebView` for rendering syntax-highlighted code with `highlight.js`.
- **Localization:** Full support for English and Arabic.
