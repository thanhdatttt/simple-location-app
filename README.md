# 📍 GGGo – Simple location app (Android App)

A **simple Android location-based application** designed for learning and practicing android development using Java and Android studio.

---

## 📌 Project Overview

**G3 - GGGo** is an Android application that allows users to:

- Detect their current location
- Display the current address on Google Maps
- Select a destination directly on the map
- Find and visualize the shortest route between locations

The project focuses on understanding **Android Location Services**, **Google Maps SDK**, and real-world map-based application workflows.

---

## 🧱 Tech Stack

### Platform
- **Android**
- **Java**

### APIs & Libraries
- **Google Maps SDK for Android**
- **Google Directions API**
- **Fused Location Provider**
- **Geocoder API**

### Tools
- **Android Studio**
- **Gradle**
- **Git & GitHub**

---

## ✨ Core Features

### 📍 Location Services
- Retrieve the device’s current GPS location
- Update location with acceptable accuracy
- Handle runtime permission requests

---

### 🗺️ Map Interaction
- Display Google Maps
- Zoom and pan interactions
- Add markers dynamically

---

### 🎯 Destination Selection
- Select destination by tapping on the map
- Display destination marker
- Show destination address

---

### 🧭 Shortest Route Navigation
- Calculate shortest route from current location to destination
- Draw route using **Polyline**
- Display estimated distance and travel time

---

### 🚶 Movement Detection
- Detect basic movement states:
  - Stationary
  - Moving
- Based on location updates and speed changes

---

## 📁 Project Structure

```text
simple-location-app/
├── app/
│ ├── src/main/java/com/example/simplelocation/
│ │ ├── MapsActivity.java
│ │ ├── model/
│ │ │ └── Place.java
│ │ └── utils/
│ │ │ └── LocationUtil.java
│ ├── src/main/res/
│ │ ├── layout/
│ │ │ └── activity_maps.xml
│ │ └── values/
│ │ └── google_maps_api.xml
├── build.gradle
├── settings.gradle
└── README.md
```

---

## ⚙️ Permissions Used

The application requires the following Android permissions:

ACCESS_FINE_LOCATION
ACCESS_COARSE_LOCATION
INTERNET


These permissions are strictly used for map display and location tracking.

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/simplelocation-android.git
```
2️⃣ Open in Android Studio
- Open Android Studio
- Select Open Existing Project
- Choose the project directory

3️⃣ Configure Google Maps API Key
- Create an API key from Google Cloud Console
- Enable Maps SDK for Android
- Add the key to:
```bash
res/values/google_maps_api.xml
<string name="google_maps_key">YOUR_API_KEY_HERE</string>
```

4️⃣ Run the application
- Run on a physical Android device or emulator
- Enable GPS/location services

---

### 📈 Future Improvements
- Turn-by-turn navigation
- Save favorite locations
- Route history tracking
- Dark mode map support
- Backend integration for user accounts

---

### 🎯 Why This Project Is Useful
- Demonstrates Android core skills
- Practical use of Google Maps & Location APIs
- Clean and understandable project structure
- Easy to extend with advanced navigation features
- Suitable for student projects and portfolios

---

## 👤 Authors
* **Thanh Dat Pham**
Android/Mobile Developer
* **Van Minh Nguyen**
Android/Mobile Developer
* **Khon Chi Tran**
Android/Mobile Developer
* **Thai Bao Giao**
Android/Mobile Developer

---

### 📄 License
This project is developed for educational purposes only.
