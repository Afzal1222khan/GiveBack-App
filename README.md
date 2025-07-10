GiveBack is a **Kotlin-based Android application** designed to connect **donors**, **NGOs**, and **volunteers** on a common platform to facilitate the donation process. 
It allows users to **donate money, clothes, food, and supplements**, track their contributions, and connect with verified charitable organizations.


##  Built With

- **Kotlin** – Main programming language
- **Firebase** – Authentication and real-time database
- **Android Studio** – IDE for development
- **Jetpack Components** – Navigation, ViewModel, LiveData
- **Material UI** – Modern, responsive user interface design



##  Features

###  Donor Module
- Login/Sign Up using Firebase
- Explore active donation campaigns
- Donate (money, clothes, food, supplements)
- Track past donations
- Provide feedback & ratings for NGOs

###  NGO Module
- Login/Sign Up with admin verification
- Create and manage donation events
- View donor lists and their contributions
- View feedback and engagement

###  Volunteer Features
- View nearby donation drives
- Help NGOs by organizing drives
- Participate and track volunteer activity

###  UI Screens
- Splash Screen
- Home Page with event cards
- Donation Form
- NGO Dashboard
- Donor History Page
- Feedback Form



##  Authentication & Storage

- Firebase Authentication used for secure login
- Firebase Realtime Database and Cloud Firestore for storing:
  - User profiles
  - Donations
  - NGO events
  - Feedback



##  How to Run

1. **Clone the repository**
Open in Android Studio
Connect Firebase
Go to Firebase Console
Create a project and connect to the Android app
Replace google-services.json in /app folder
Run the app
On a real device or emulator
Screenshots

Splash Screen	Home Page	Donation Form	Donor History
 Folder Structure

GiveBack-App/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/giveback/
│   │   │   ├── res/layout/
│   │   │   └── AndroidManifest.xml
│   └── build.gradle
├── screenshots/
├── README.md
✨ Future Improvements

Google Maps API for locating nearby donation events
Analytics dashboard for NGOs
Notification system for donation reminders
 NGO verification system
 Multilingual support
