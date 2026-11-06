# V-Comm – Faculty Communication & Management App

V-Comm is a mobile application built exclusively for college faculty members to communicate, coordinate their work, and manage everyday academic activities in one place.

The idea behind V-Comm is simple: make it easier for faculty members to connect with colleagues, communicate without needing their personal contact details, organize work schedules, and keep track of important academic activities.

## Why We Built It

In colleges, faculty members often rely on WhatsApp groups, phone calls, and separate tools to communicate and coordinate their work. Reaching a colleague whose contact information isn't available, keeping track of schedules, and managing daily activities can become inconvenient.

We built V-Comm to bring these activities together in a single platform, making communication and coordination among faculty members easier and more organized.

## Features

- **Faculty Authentication:** Secure login for faculty members with role-based access to the application's features.
- **Faculty Directory:** Find and connect with other faculty members without needing to have their personal contact numbers saved.
- **Real-Time Messaging:** Communicate with colleagues through instant messaging powered by Cloud Firestore.
- **Work Scheduling:** Organize, schedule, and keep track of faculty work and academic responsibilities.
- **Attendance Management:** Mark and manage faculty attendance through the application.
- **Academic Calendar:** Keep track of important academic dates, schedules, and activities.
- **Centralized Communication:** Access faculty communication and work-related information from one application.

## How It Works

V-Comm consists of two main components:

**1. Mobile Application**

The frontend is developed using Flutter and Dart, providing a mobile interface for faculty members to access communication, scheduling, and management features.

**2. Firebase Backend**

We use Firebase services to handle authentication and application data:

- **Firebase Authentication:** Handles faculty sign-in and authentication.
- **Cloud Firestore:** Stores application data and supports real-time synchronization of messages and other information across connected devices.

## Tech Stack

| Technology | Purpose |
|---|---|
| Flutter | Cross-platform mobile development |
| Dart | Application programming language |
| Firebase Authentication | User authentication |
| Cloud Firestore | Database and real-time messaging |
| Firebase | Backend infrastructure |

## Project Screenshots

Screenshots of the application will be added here to demonstrate its interface and functionality.

Suggested screenshots:
- Faculty login screen
- Faculty dashboard
- Faculty directory
- Real-time messaging interface
- Work scheduling interface
- Attendance management
- Academic calendar

## Getting Started

### Prerequisites

- Flutter SDK
- Dart SDK
- Android Studio or VS Code
- A Firebase project

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/hithesh1120/v_comm.git
cd v_comm
```

**2. Install dependencies**

```bash
flutter pub get
```

**3. Configure Firebase**

Create a Firebase project and configure Firebase Authentication and Cloud Firestore.

Add your own Firebase configuration files for the target platform.

**4. Run the application**

```bash
flutter run
```

## Development Team

Developed as a collaborative academic project by a team of three students at **VIT-AP University (2024).**

## Future Improvements

Potential enhancements include:

- Push notifications for new messages and scheduled activities.
- File and image sharing between faculty members.
- Group conversations for departments and faculty teams.
- Improved scheduling and attendance management.
- Additional tools for academic coordination.

## Author

**Arava Hithesh Prem**

- GitHub: [@hithesh1120](https://github.com/hithesh1120)
- LinkedIn: [Arava Hithesh Prem](https://www.linkedin.com/in/arava-hithesh-prem-08648b327/)
- Email: hitheshprem1120a@gmail.com

---

*Built to make faculty communication and academic coordination simpler.*
