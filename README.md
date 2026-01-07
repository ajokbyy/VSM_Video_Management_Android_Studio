# 🎓 Live Classes & Video Learning App (Android)

An **Unacademy-style Android application** built using **Kotlin** and **MVVM architecture**, designed to deliver a **scalable, high-performance video-based learning experience**.

This project focuses on **modern Android development practices**, including **Media3 (ExoPlayer)** for video playback, **REST API integration**, **pagination**, **local persistence**, and **robust error handling**.

---

## 🚀 Features

- 📚 Course listing with categories  
- 🎥 Video playback using Media3 (modern ExoPlayer)  
- ⏯️ Continue watching from last playback position  
- ⭐ Bookmark lessons  
- 📶 Smooth streaming with caching support  
- 📄 Paginated course & lesson lists  
- ⚠️ Centralized error handling (network, API, empty states)  
- 💾 Watch history stored locally  
- 📊 Firebase Analytics integration (optional)  

---

## 🛠️ Tech Stack

### Language & Architecture
- **Kotlin**
- **MVVM (Model–View–ViewModel)**
- Repository Pattern
- Clean, modular, and maintainable codebase

### Android & Jetpack
- Media3 (ExoPlayer)
- ViewModel
- LiveData / StateFlow
- RecyclerView
- Paging 3
- ViewBinding
- Lifecycle-aware components

### Networking & Data
- Retrofit
- OkHttp
- REST APIs
- JSON parsing
- Room Database (watch history & bookmarks)

### Tools & Services
- Firebase Analytics
- Git & GitHub

---

## 📐 Architecture Overview

The app follows **MVVM architecture** to ensure proper separation of concerns and scalability.

```
com.example.learningapp
│
├── data
│   ├── model
│   ├── remote
│   ├── local
│   └── repository
│
├── ui
│   ├── courses
│   ├── player
│   └── bookmarks
│
├── viewmodel
│
└── utils
```

---

## 🎬 Video Playback (Media3 / ExoPlayer)

- Built using **Android Media3**, Google’s recommended replacement for ExoPlayer
- Lifecycle-aware playback
- Smooth buffering and playback state restoration
- Proper resource management to avoid memory leaks

---

## 💾 Local Storage

- **Room Database** for watch history and bookmarks
- Resume playback from last watched position

---

## 🌐 API Integration & Pagination

- REST APIs integrated using **Retrofit**
- Pagination using **Paging 3**
- Handles loading, error, and empty states gracefully

---

## ⚠️ Error Handling

- Network failures
- API errors
- No-internet scenarios
- Empty data responses

---

## 📱 Screens

- Course List
- Course Categories
- Course Details
- Video Player
- Continue Watching
- Bookmarks

---

## 🧪 Future Enhancements

- Offline video downloads
- Firebase Authentication
- Instructor dashboard
- Quiz & test modules
- Jetpack Compose UI

---

## 🧠 What This Project Demonstrates

- Real-world EdTech app architecture
- Media playback handling
- State management with MVVM
- Pagination and caching
- Performance-aware Android development

---

## ▶️ How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open in Android Studio  
3. Sync Gradle  
4. Run on emulator or device  

---

## 🗣️ Interview Explanation

“I built an Unacademy-style Android learning app using Kotlin and MVVM. It supports video playback with Media3, API pagination, Room-based local storage, and lifecycle-aware state management, focusing on scalability and performance.”

---

## 📄 License

This project is for **learning and demonstration purposes only**.
