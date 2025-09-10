# DevRoadmaps Application 🚀

An interactive, feature-rich Android application designed to guide developers through various learning roadmaps. This app is built with modern, industry-standard technologies and architectural patterns, making it a robust tool for self-paced learning.

## Screenshots

| | | | |
| :---: | :---: | :---: | :---: |
| ![A](https://github.com/user-attachments/assets/b3e63e29-6e00-4989-824b-a25c7cb19ee1) | ![B](https://github.com/user-attachments/assets/1ee38750-db1d-49d6-82a3-ecef0976b5a2) | ![C](https://github.com/user-attachments/assets/247b1875-4bcd-48f3-8112-ee508c8c5979) | ![D](https://github.com/user-attachments/assets/8e6d7092-86d1-40e0-b3df-63d03010ae88) |
| ![E](https://github.com/user-attachments/assets/eef6a509-76f9-4fd7-a23a-f0f5244aa78f) | ![F](https://github.com/user-attachments/assets/dc6767b0-4f13-43f4-94ae-fd7203043124) | ![G](https://github.com/user-attachments/assets/3d4264cc-9851-4477-bce4-abc020e27a22) | ![H](https://github.com/user-attachments/assets/2363559c-667a-4751-8add-54bf466a9101) |
| ![I](https://github.com/user-attachments/assets/fc97c3bf-d108-4a4c-9430-228d8aa3c7a3) | ![J](https://github.com/user-attachments/assets/a72bc9e6-3a62-4de2-ac86-9a52d5f83ca9) | ![K](https://github.com/user-attachments/assets/92038be3-a09d-4a70-88eb-50852e74fe79) | |

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
