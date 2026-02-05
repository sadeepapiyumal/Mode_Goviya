# 🌾 Mode Goviya – Paddy Cultivation Assistant

**Mode Goviya** is an Android mobile application designed to empower Sri Lankan farmers with scientifically backed paddy cultivation guidance. By selecting their specific district and rice variety, users receive a tailored, step-by-step roadmap for a successful harvest.

The application bridges the gap between traditional knowledge and modern agricultural science, delivering localized instructions for every stage of the farming lifecycle.

---

## 📱 Features

### 🧭 Onboarding
* **Sinhala Language First:** A localized onboarding experience designed for ease of use.
* **Smart Detection:** Uses `SharedPreferences` to detect first-launch and guide new users.

### 📍 Personalized Selection
* **District-Based Logic:** Dropdown selection for Sri Lankan districts to provide region-specific advice.
* **Variety Filtering:** Support for various paddy varieties with filtered cultivation schedules.

### 🏠 Interactive Dashboard
Access seven critical cultivation stages through an intuitive icon-based grid:
1. **බිම් සැකසීම** (Soil Preparation)
2. **බීජ වැපිරීම** (Seed Planting)
3. **පොහොර යෙදීම** (Fertilizing)
4. **පලිබෝධ පාලනය** (Pest Control)
5. **ජලය යෙදීම** (Irrigation)
6. **අස්වනු නෙලීම** (Harvesting)
7. **අස්වනු ගබඩා කිරීම** (Storage)

### 📚 Data & Offline Support
* **Structured Guidance:** District + variety-based filtering for precise recommendations.
* **Offline Access:** All core cultivation content is stored locally for use in areas with poor connectivity.

---

## 🛠️ Technologies Used

- **Language:** Kotlin
- **UI Framework:** Jetpack Compose
- **Architecture:** MVVM (Model-View-ViewModel)
- **Database:** Room Persistence Library
- **Navigation:** Navigation Compose
- **State Management:** ViewModel + StateFlow
- **UI Design:** Material 3

---

## 📂 Project Structure

```text
com.example.mode_goviya
│
├── data
│   ├── entity      # Room Database Entities
│   ├── dao         # Data Access Objects
│   ├── database    # Room Database Configuration
│   └── repository  # Single source of truth for data
│
├── ui
│   ├── screens     # Compose UI Screen functions
│   └── viewmodel   # Logic and State handling
│
├── util            # Helper classes (e.g., Prefs.kt)
│
└── navigation      # Navigation graph and destinations
```

🗄️ Database SchemaTableFieldsDistrictid: Int, name: StringPaddy Varietyid: Int, name: String, districtId: Int
🌍 Localization & Future Roadmap
Current Support: 🇱🇰 Sinhala (Primary)
Planned Updates:
🌐 Multilingual: Adding Tamil and English support.
🔊 Text-To-Speech: Audio guidance for better accessibility.
📅 Smart Reminders: Push notifications for fertilization and irrigation windows.
🤖 AI Insights: Crop disease detection and AI-based recommendations.🌦 Weather: Real-time local weather integration.

👨‍💻 Developed BySadeepa PiyumalFinal Year UndergraduateSri Lanka Institute of Information Technology (SLIIT)Specialization: Interactive Media

📄 License :This project is developed for academic and research purposes.
