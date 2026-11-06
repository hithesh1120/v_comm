# V-Comm – Faculty Communication & Management App

V-Comm is a mobile application designed exclusively for college faculty members. It provides a common platform where faculty can connect with colleagues, exchange messages, manage their work schedules, mark attendance, and keep track of important academic activities.

The main goal of the project is to reduce the need for multiple communication tools and make everyday coordination between faculty members easier.

## 💡 Why V-Comm?

In a college environment, faculty members regularly need to communicate with colleagues, coordinate academic responsibilities, arrange meetings, and stay updated about schedules.

However, this information is often spread across WhatsApp groups, phone calls, emails, and other platforms. Reaching another faculty member can also be difficult when their contact details are not available.

V-Comm brings these activities together in one application, giving faculty members a convenient way to communicate and organize their daily work.

## ✨ Features

- **Faculty Login:** Secure authentication for faculty members to access the application.
- **Faculty Directory:** Find and connect with other faculty members without needing to save their personal contact numbers.
- **Real-Time Chat:** Send and receive messages instantly using Firebase Cloud Firestore.
- **Work Scheduling:** Organize work schedules and coordinate academic responsibilities with colleagues.
- **Attendance Management:** Mark and manage faculty attendance through the application.
- **Academic Calendar:** View and keep track of important academic dates and scheduled activities.
- **Centralized Platform:** Access communication and work-related features from a single mobile application.

## ⚙️ How It Works

V-Comm uses Flutter for the mobile application and Firebase for its backend services.

### 1. Mobile Application – Flutter

The application is developed using Flutter and Dart. Faculty members interact with the platform through a mobile interface where they can access messaging, scheduling, attendance, and other available features.

### 2. Backend – Firebase

Firebase handles authentication and data storage, allowing the application to manage faculty accounts and synchronize information across devices.

The project uses:

- **Firebase Authentication:** Manages faculty sign-in and authentication.
- **Cloud Firestore:** Stores application data, including messages and academic information. Its real-time synchronization keeps connected devices updated when data changes.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Flutter | Cross-platform mobile application development |
| Dart | Application programming language |
| Firebase Authentication | Faculty authentication |
| Cloud Firestore | Database and real-time message synchronization |
| Firebase | Backend services and infrastructure |

## 📱 Application Screenshots

Screenshots of the application can be added below to show how its different features work.

| Screen | Description |
|---|---|
| Login Screen | Faculty authentication |
| Dashboard | Main application interface |
| Faculty Directory | Finding and connecting with colleagues |
| Chat Screen | Real-time faculty communication |
| Scheduling | Managing work and academic schedules |
| Attendance | Faculty attendance management |
| Academic Calendar | Viewing important academic dates |

## 🚀 Getting Started

Follow these steps to download and run the project locally.

### Prerequisites

Make sure you have the following installed:

- Flutter SDK
- Dart SDK
- Android Studio or Visual Studio Code
- A Firebase account and project

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/hithesh1120/v_comm.git
cd v_comm
```

**2. Install project dependencies**

```bash
flutter pub get
```

**3. Configure Firebase**

Create a Firebase project and enable:

- Firebase Authentication
- Cloud Firestore

Add your own Firebase configuration files for the Android or iOS platform.

**4. Run the application**

Connect an emulator or physical device and execute:

```bash
flutter run
```

The application should now be available on your connected device.

## 🔮 Future Improvements

There are several ways the application could be extended:

- Push notifications for new messages and scheduled activities.
- File and image sharing between faculty members.
- Group conversations for departments and faculty teams.
- More advanced scheduling and attendance management.
- Additional tools to support day-to-day academic coordination.

## 👥 Development Team

V-Comm was developed as a collaborative academic project by a team of three students at **VIT-AP University in 2024**.

## 👨‍💻 Author

**Arava Hithesh Prem**

- GitHub: [@hithesh1120](https://github.com/hithesh1120)
- LinkedIn: [Arava Hithesh Prem](https://www.linkedin.com/in/arava-hithesh-prem-08648b327/)
- Email: hitheshprem1120a@gmail.com

---

*V-Comm – Bringing faculty communication and academic coordination together in one place.*
