# V-Comm

V-Comm is a mobile app that lets college students and faculty talk to each other and keep track of academic dates, all in one place.

## Why we built it

In a college, messages and updates usually end up spread across WhatsApp groups, emails and notice boards. That makes it easy to miss something or not know where to look. We built V-Comm to put faculty-student communication in one app instead of many.

## What the app does

- **Log in with your role.** The app knows who you are, and what you can see and do depends on your role. A student account and a faculty account don't see the same things.
- **Chat in real time.** Messages show up on the other person's phone right away, with no refreshing.
- **Academic calendar.** Important academic dates can be scheduled and viewed inside the app.
- **One place for everything.** Students and faculty don't have to switch between different apps to reach each other.

## How it works, in simple terms

The project has two parts:

1. **The app** is what you see and tap on your phone. We built it with Flutter, which lets one codebase run on both Android and iPhone.
2. **The online backend** stores the data and checks who is allowed in. We used Firebase, a service from Google, for this:
   - *Firebase Authentication* handles sign-in and checks who you are.
   - *Cloud Firestore* is the online database that stores messages and calendar entries. It updates every connected phone instantly, which is why chat feels live.

## Built with

| Tool | What it's used for |
|------|--------------------|
| Flutter and Dart | Building the mobile app |
| Firebase Authentication | Login and role-based access |
| Cloud Firestore | Storing and syncing messages and data in real time |

## Screenshots

[Add 3 to 4 screenshots here: the login screen, a chat, and the calendar. Screenshots help people who don't know code understand the project the fastest.]

## Run it on your computer

You'll need [Flutter](https://docs.flutter.dev/get-started/install) installed.

1. Download the code:

git clone https://github.com/hithesh1120/v_comm.git
cd v_comm

2. Install the packages the app needs:

flutter pub get

3. Connect your own Firebase project. Create one at [firebase.google.com](https://firebase.google.com), turn on Authentication and Cloud Firestore, and add your own config files for Android or iOS.
4. Start the app on an emulator or a connected phone:

flutter run


## The team

We were a team of three students at VIT-AP University. We completed this project in 2024.

**My part:** [Write 1 or 2 plain sentences about what you personally built, for example the login and roles, the chat, or the calendar.]

## Ideas for the future

These are things we haven't built yet:
- Push notifications for new messages
- Sharing files or images in chat
- Group chats for classes

## Contact

Arava Hithesh Prem
Email: hitheshprem1120a@gmail.com
LinkedIn: [arava-hithesh-prem](https://www.linkedin.com/in/arava-hithesh-prem-08648b327)
