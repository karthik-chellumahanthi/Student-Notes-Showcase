# 📚 Student Notes

> Your Academic World, Organized in One Place.

[![Google Play](https://img.shields.io/badge/Google%20Play-Live-brightgreen?logo=googleplay)](https://play.google.com/store/apps/details?id=com.karthik.studentnotes)
![Flutter](https://img.shields.io/badge/Flutter-Framework-02569B?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-Language-0175C2?logo=dart)
![Firebase](https://img.shields.io/badge/Firebase-Backend-FFCA28?logo=firebase)
![Platform](https://img.shields.io/badge/Platform-Android-green?logo=android)

**Student Notes** is an all-in-one academic notes and student productivity application designed to make studying easier and more organized.

The application provides a centralized platform where students can access academic study materials, explore subject-wise and unit-wise PDFs, and use essential academic tools without switching between multiple applications.

📱 **Live on Google Play:** [Download Student Notes](https://play.google.com/store/apps/details?id=com.karthik.studentnotes)

---

## ✨ What is Student Notes?

Student Notes is designed primarily for engineering and college students who struggle to find organized academic study materials.

Instead of searching through multiple websites, Telegram channels, WhatsApp groups, and scattered PDF files, students can access their academic resources through a structured application.

The application combines academic resource management and student productivity utilities in one place.

Its goal is to make academic resources more accessible while simplifying everyday student activities.

---

## 🎯 Key Features

- 📚 Organized academic notes library
- 🎓 University-based resource organization
- 📋 Regulation-wise study materials
- 📅 Year-wise and semester-wise navigation
- 🏫 Branch-specific academic resources
- 📖 Subject-wise notes organization
- 📑 Unit-wise PDF materials
- 📄 In-app PDF viewer
- ⬇️ PDF downloading and offline access
- 🔐 Google Sign-In authentication
- 📧 Email and password authentication
- 👤 User profiles and persistent login
- 🧮 Scientific Calculator
- 🎓 CGPA / SGPA Calculator
- 📊 Percentage Calculator
- 📅 Attendance Tracker
- ☁️ Cloud-based document storage
- 📤 Academic document contributions

---

## 📚 Academic Notes Library

Student Notes organizes academic materials through a structured navigation system.

Students can find relevant resources without manually searching through hundreds of documents.

**Academic Navigation Flow:**

```text
        Student Notes
              |
       University Selection
              |
       Regulation Selection
              |
        Academic Year
              |
       Semester Selection
              |
        Branch Selection
              |
        Subject Selection
              |
         Unit Selection
              |
         PDF Materials
              |
       Read / Download
```

This structure makes academic resource discovery easier and more organized.

---

## 🧮 Student Productivity Tools

Student Notes goes beyond providing study materials.

It also includes useful academic utilities.

**Available Tools:**

- **Scientific Calculator** – Perform scientific and mathematical calculations.
- **CGPA Calculator** – Calculate cumulative academic performance.
- **SGPA Calculator** – Calculate semester grade point averages.
- **Percentage Calculator** – Perform percentage-related calculations.
- **Attendance Tracker** – Track attendance and monitor attendance percentage.

The objective is to provide students with essential academic tools in one application.

---

## 🔐 Authentication System

Student Notes uses Firebase Authentication to provide user authentication.

Supported authentication methods:

- Google Sign-In
- Email and Password Authentication
- Persistent Login Sessions
- User Profile Management

---

## ☁️ Cloud Storage & Backend

Student Notes uses Firebase and Cloudflare infrastructure to manage application data and academic documents.

**Firebase Authentication**
- User authentication and identity management.

**Cloud Firestore**
- Academic document metadata.
- Application-related data.
- Resource organization.

**Cloudflare R2**
- Cloud-based PDF and document storage.
- Academic resource submissions.

**Cloud Storage Bucket:**

`student-notes-submissions`

The application uses a combination of database services and object storage to organize academic resources.

---

## 🛠️ Tech Stack

Student Notes is built using modern mobile application development and cloud technologies.

### Frontend

- Flutter
- Dart
- Material Design

### Backend & Cloud Services

- Firebase
- Firebase Authentication
- Cloud Firestore
- Firebase Cloud Functions
- Firebase Remote Config
- Cloudflare R2

### Additional Technologies

- Google Sign-In
- REST APIs
- Secure Storage
- Hive
- AES-256 encryption

*Technology and implementation details should be verified against the current production code before being treated as an exhaustive implementation inventory.*

---

## 🏗️ Project Architecture

The application follows a mobile-client and cloud-services architecture.

```text
             Student Notes
              Mobile App
                  |
          Flutter Application
                  |
        +---------+---------+
        |         |         |
        v         v         v
     Firebase  Firestore  Cloudflare
       Auth      Database      R2
        |         |         |
        v         v         v
      Users    Metadata   PDF Files
                  |
                  v
          Academic Resources
```

The architecture separates authentication, structured application data, and document storage.

---

## 🔒 Source Code

The production application source code is maintained separately from this public showcase repository.

This repository is intended to showcase the project, its features, architecture, technologies, and development journey without exposing sensitive production implementation details.

This showcase repository does not contain:

- Production application source code.
- Firebase service account credentials.
- API keys or private tokens.
- Cloudflare R2 access credentials.
- Private environment variables.
- Sensitive backend configuration.

This approach allows the project to maintain a public technical presence while protecting its production infrastructure.

---

## 📱 Live Application

<badge>LIVE ON GOOGLE PLAY</badge>

Student Notes is officially published and available on the Google Play Store.

Try the application and explore its academic resources and student productivity features.

### 👉 [Download Student Notes on Google Play](https://play.google.com/store/apps/details?id=com.karthik.studentnotes)

**Package Name:** `com.karthik.studentnotes`

---

## 📸 Screenshots

Application screenshots will be showcased here to demonstrate the actual user interface and application experience.

Planned screenshot gallery:

| Screen | Description |
|---|---|
| Home Screen | Main application dashboard |
| Authentication | Login and registration |
| Notes Library | Organized academic materials |
| Semester Navigation | Year and semester selection |
| Subject Library | Subject-wise resources |
| PDF Viewer | Academic document reading |
| Calculator | Academic calculation tools |
| Attendance | Attendance management |

*Actual application screenshots will be added to this section.*

---

## 🚀 Vision

The vision of Student Notes is to become a convenient academic resource platform for college and university students.

The long-term goal is to build a centralized student ecosystem where learners can:

- Access academic resources easily.
- Find semester-specific study materials.
- Explore resources from different branches and regulations.
- Manage their academic activities.
- Use essential student productivity tools.
- Contribute useful academic resources.

---

## 🗺️ Roadmap

### ✅ Core Application

- [x] Flutter application development
- [x] Firebase authentication integration
- [x] Google Sign-In
- [x] Email and password authentication
- [x] Academic resource organization
- [x] Cloud document storage integration
- [x] PDF access and management
- [x] Student productivity utilities
- [x] Google Play publication

### 🔄 Improvements

- [ ] Expand academic resource coverage.
- [ ] Add more university and regulation support.
- [ ] Improve document availability across semesters.
- [ ] Enhance application performance.
- [ ] Improve student experience.
- [ ] Expand academic productivity features.

*Roadmap items represent development priorities and may change over time.*

---

## 👨‍💻 Creator

**Karthik**

B.Tech – Computer Science & Engineering  
Specialization: Artificial Intelligence & Data Science

Student Notes is an independently developed project focused on combining mobile application development, cloud technologies, and student-centered product design.

The project reflects my interest in building practical applications that solve real-world problems.

---

## ⭐ Support Student Notes

If you find Student Notes useful:

- ⭐ Explore the application on Google Play.
- 📢 Share it with your classmates and friends.
- 💡 Share suggestions for improving the application.
- 📚 Help expand academic resource availability.

### 📲 Get the App

[**Download Student Notes – Google Play Store**](https://play.google.com/store/apps/details?id=com.karthik.studentnotes)

---

## 📄 License

This repository serves as a public showcase for Student Notes.

The production application's source code and implementation remain maintained separately. Publication of this showcase does not grant permission to reproduce or redistribute the application.

