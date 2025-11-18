# ⚡ Flash Group Chat App

A real-time group chat application built using **Flutter** and **Firebase**, designed with clean architecture and robust features. Flash Group Chat App enables users to join group conversations instantly, send and receive messages in real time, and enjoy seamless chat experiences across devices.

---

## 📌 Overview

Flash Group Chat App is a fully functional chat platform that supports:

- **Real-time messaging** using Firebase Realtime Database or Firestore  
- **User authentication** with email/password  
- **Group chat functionality** with scalable data structure  
- **Dynamic UI**, respecting modern chat-app design  

The app is built with production-quality practices and modular architecture, making it easy to expand as your user base grows.

---

## ✨ Key Features

- **Authentication** — Users can sign up, log in, and log out securely  
- **Real-Time Messaging** — Messages are sent and retrieved in real time  
- **Group Chats** — Multiple users can chat in defined groups  
- **User Profiles** — Basic user profile information (e.g., name, email)  
- **Chat UI** — Custom message bubbles, scrollable chat history  
- **Error Handling** — Handles login failures, connectivity issues, and more  

---

## 🧩 Project Structure

```text
lib/
├── screens/
│   ├── login_screen.dart  
│   ├── register_screen.dart  
│   ├── chat_screen.dart  
│
├── services/
│   ├── auth_service.dart     # Firebase Authentication logic  
│   └── chat_service.dart     # Fetch & send messages  
│
├── models/
│   └── message.dart          # Message data model  
│
├── utilities/
│   ├── constants.dart        # Firebase keys, styling constants  
│   └── widget_helpers.dart   # Reusable UI components  
│
└── main.dart                  # App entry point  
