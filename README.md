# ⚡ EV Charging Finder and Booking App

A Flutter-based mobile application designed to help electric vehicle (EV) users find nearby charging stations, view station details, book charging slots, and make payments using UPI.

The application integrates Open Charge Map API for EV charging station data and Firebase Authentication for secure user authentication.



## 📱 Features

* User Authentication (Login / Signup)
* EV Vehicle Registration
* Nearby Charging Station Finder
* Slot Booking System
* Live Slot Availability
* UPI Payment Integration
* Booking History
* User Profile Management
* Vehicle Management
* Firebase Firestore Database



## 🛠️ Technologies Used

* Flutter
* Dart
* Firebase Authentication
* Cloud Firestore
* Google Maps / Flutter Map
* UPI Payment Integration
* Android Studio



## 📂 Project Structure

```bash
lib/
 ├── auth/
 ├── screens/
 ├── widgets/
 ├── services/
 ├── main.dart
```



## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/Anjali-Pandit-code/EV-Charging-Station-Finder-and-Slot-Booking.git
```

2. Open project in Android Studio

3. Run commands

```bash
flutter pub get
flutter run
```



## ⚙️ Configuration

Before running the application, make sure all required services and APIs are properly configured.



### 🔥 Firebase Configuration

This project uses Firebase Authentication for user registration and login.

#### Step 1: Create a Firebase Project

1. Open the Firebase Console.
2. Create a new Firebase project.
3. Add an Android application to the Firebase project.
4. Enter your Flutter Android package name.
5. Download the Firebase configuration file.
6. Place the configuration file in the appropriate Android directory.

#### Step 2: Enable Firebase Authentication

Go to:

```text
Firebase Console
        ↓
Authentication
        ↓
Sign-in method
        ↓
Email/Password
```

### 🌐 Open Charge Map API Configuration

This application uses the Open Charge Map API to retrieve EV charging station information.

An API key is required, add it using a secure configuration method.




## 📌 Future Scope

* Push notifications for booking reminders
* AI-based charging station recommendations
* Support for multiple languages

