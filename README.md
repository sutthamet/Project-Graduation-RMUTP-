# 🏫 KARUPAN — University Asset Management App

A mobile application for managing university equipment and assets, built with **Flutter** and **Firebase**. Developed as a graduation project at **RMUTP (Rajamangala University of Technology Phra Nakhon), Computer Engineering Department**.

-----

## 📱 Screenshots

| Dashboard | Asset Management | Asset Detail |
|:---:|:---:|:---:|
| <img src="assets/screenshots/dashboard.png" width="220"> | <img src="assets/screenshots/asset-list.png" width="220"> | <img src="assets/screenshots/asset-detail.png" width="220"> |

| QR Scanner | Repair Request | Repair History |
|:---:|:---:|:---:|
| <img src="assets/screenshots/qr-scanner.png" width="220"> | <img src="assets/screenshots/repair-request.png" width="220"> | <img src="assets/screenshots/repair-history.png" width="220"> |

| Issue Queue | User Approval | CSV Import |
|:---:|:---:|:---:|
| <img src="assets/screenshots/issue-queue.png" width="220"> | <img src="assets/screenshots/user-approval.png" width="220"> | <img src="assets/screenshots/csv-import.png" width="220"> |


-----

## 🎯 About the Project

Universities often struggle to track equipment across buildings — who borrowed what, where things are located, and when something needs repair. **KARUPAN** solves this by providing a centralized digital system for asset tracking, movement logging, and maintenance requests.

-----

## ✨ Features

- 📦 **Asset Management** — Add, edit, and track university equipment with detailed records
- 🔄 **Asset Movement Tracking** — Log and view the movement history of each item across locations
- 🔧 **Repair Request System** — Users can report damaged equipment directly in the app
- 📋 **History & Audit Trail** — Full history of every asset action for accountability
- 🔐 **Role-Based Access Control** — Two roles with different permissions:
  - **Admin** (Lecturers / Technicians) — Full access: manage assets, approve requests, assign/revoke user roles
  - **User** (Students / General Staff) — Can view assets and submit repair reports

-----

## 🛠️ Tech Stack

|Layer         |Technology                |
|--------------|--------------------------|
|Frontend      |Flutter (Dart)            |
|Backend       |Firebase (Cloud Functions)|
|Database      |Cloud Firestore           |
|Authentication|Firebase Auth             |
|Storage       |Firebase Storage          |
|Platform      |Android / iOS             |

-----

## 🗂️ Project Structure

```
lib/
├── models/          # Data models (Asset, User, Request)
├── screens/         # UI screens
├── services/        # Firebase service layers
├── widgets/         # Reusable UI components
backend/
└── ...              # Firebase Cloud Functions
tools/
└── firestore_import/ # Seed data / import scripts
```

-----

## 🚀 Getting Started

### Prerequisites

- Flutter SDK `>=3.0.0`
- Dart SDK
- Firebase project set up

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Rukhub/Project-Graduation-RMUTP-.git
cd Project-Graduation-RMUTP-

# 2. Install dependencies
flutter pub get

# 3. Set up Firebase
# - Create a Firebase project at https://console.firebase.google.com
# - Add your google-services.json (Android) and GoogleService-Info.plist (iOS)
# - Enable Firestore, Authentication, and Storage

# 4. Run the app
flutter run
```

-----

## 👥 User Roles

|Role     |Description              |Permissions                                                      |
|---------|-------------------------|-----------------------------------------------------------------|
|**Admin**|Lecturers or technicians |Add/edit/delete assets, manage repair requests, assign user roles|
|**User** |Students or general staff|View assets, submit repair reports                               |


> Admins can promote or demote any user’s role directly from the app.

-----

## 📚 Built With

- [Flutter](https://flutter.dev/) — Cross-platform mobile framework
- [Firebase](https://firebase.google.com/) — Backend-as-a-Service platform
- [Cloud Firestore](https://firebase.google.com/products/firestore) — NoSQL cloud database

-----

## 🎓 About

This project was developed as a **graduation project** for the Bachelor of Engineering in Computer Engineering program at **RMUTP (Rajamangala University of Technology Phra Nakhon)**.

-----

## 👤 Author

**Rukhub**

- GitHub: [@Rukhub](https://github.com/Rukhub)
