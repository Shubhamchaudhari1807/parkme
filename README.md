# 🚗 Smart Parking Mobile Application

A **Flutter-based Smart Parking App** that simplifies urban parking with real-time availability, seamless payments, and Google Maps navigation. Developed as a final semester project, this application addresses daily parking challenges by offering smart booking and slot management.

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue)  
![Firebase](https://img.shields.io/badge/Firebase-Backend-yellow)  
![Razorpay](https://img.shields.io/badge/Payments-Razorpay-informational)  
![Google Maps](https://img.shields.io/badge/Maps-Google%20Maps-lightgrey)

---

## 🔥 Features

✅ **User Authentication**  
- Register and login securely via Firebase Authentication

📍 **Nearby Parking Stations on Map**  
- Integrated Google Maps API to show real-time nearby parking locations  
  ![Maps](https://github.com/Shubhamchaudhari1807/parkme/assets/images/maps.png)  
  *The map view showing available parking spots in real-time.*

📅 **Book Slots**  
- Select, view, and reserve available parking slots  
  ![App Home](https://github.com/Shubhamchaudhari1807/parkme/assets/images/app-home.png)  
  *The app’s home screen showing the main dashboard with navigation options.*

💸 **Online Payments**  
- Complete booking via Razorpay API for a secure and fast transaction  
  ![Payment Mode Selection](https://github.com/Shubhamchaudhari1807/parkme/assets/images/payment-mode-selection.png)  
  *The payment mode selection screen, allowing users to choose their preferred method.*

📊 **Real-Time Updates**  
- Firebase Firestore ensures real-time data handling for slot availability and bookings

---

## 💡 Tech Stack

| Technology        | Purpose                          |
|-------------------|----------------------------------|
| **Flutter & Dart**| UI Development (Cross-Platform)  |
| **Firebase**      | Authentication & Database        |
| **Google Maps API**| Location Integration            |
| **Razorpay API**  | Payment Gateway Integration      |

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (3.x recommended)
- Android Studio / VS Code
- Firebase Project Setup
- Google Maps API Key
- Razorpay Account for API keys

### Installation Steps

```bash
git clone https://github.com/Shubhamchaudhari1807/parkme.git

cd parkme

flutter pub get
