🌾 Mode Goviya – Paddy Cultivation Assistant

Mode Goviya is an Android mobile application developed to support Sri Lankan farmers by providing scientifically recommended paddy cultivation guidance based on district and rice variety selection.

The application delivers step-by-step farming instructions including soil preparation, fertilization, pest control, irrigation scheduling, harvesting guidance, and storage recommendations.

📱 Features
🧭 Onboarding

Sinhala language onboarding experience

User-friendly introduction to application usage

First-launch detection using Shared Preferences

📍 District Selection

Dropdown selection of Sri Lankan districts

Stored locally for personalized recommendations

🌱 Paddy Variety Selection

Farmers can select paddy varieties

Data stored and used to filter cultivation instructions

🏠 Home Dashboard

Seven cultivation sections with visual icons:

බිම් සැකසීම (Soil Preparation)

බීජ වැපිරීම (Seed Planting)

පොහොර යෙදීම (Fertilizing)

පලිබෝධ පාලනය (Pest Control)

ජලය යෙදීම (Irrigation)

අස්වනු නෙලීම (Harvesting)

අස්වනු ගබඩා කිරීම (Storage)

📚 Cultivation Guidance

District + variety based filtering

Offline content support

Structured agricultural recommendations

💾 Local Database

Room database integration

Stores:

Districts

Paddy varieties

Cultivation instructions

🛠️ Technologies Used

Language: Kotlin

UI Framework: Jetpack Compose

Architecture: MVVM (Model View ViewModel)

Database: Room Persistence Library

Navigation: Navigation Compose

State Management: ViewModel + StateFlow

Data Storage: SharedPreferences

Design: Material 3

📂 Project Structure
com.example.mode_goviya
│
├── data
│   ├── entity
│   ├── dao
│   ├── database
│   └── repository
│
├── ui
│   ├── screens
│   └── viewmodel
│
├── util
│   └── Prefs.kt
│
└── navigation
⚙️ Installation Guide
✅ Requirements

Android Studio Hedgehog or later

Android SDK 34+

Kotlin 1.9+

Gradle 8+

🚀 Steps to Run

Clone repository

git clone https://github.com/YOUR_USERNAME/mode-goviya.git

Open project in Android Studio

Sync Gradle

Run on Emulator or Physical Device

🗄️ Database Schema
District Table
Field	Type
id	Int
name	String
Paddy Variety Table
Field	Type
id	Int
name	String
districtId	Int
🎯 Target Users

Paddy farmers in Sri Lanka

Agricultural extension officers

Farming students and researchers

🌍 Localization

Primary Language: Sinhala

Future support planned for:

Tamil

English

🔮 Future Improvements

🔊 Text-To-Speech farming guidance

☁️ Cloud database synchronization

📅 Smart cultivation reminders

🤖 AI-based crop recommendations

🌦 Weather integration

👨‍💻 Developed By

Sadeepa Piyumal
Final Year Undergraduate
Sri Lanka Institute of Information Technology (SLIIT)
Specialization: Interactive Media & Game Development

📄 License

This project is developed for academic and research purposes.
