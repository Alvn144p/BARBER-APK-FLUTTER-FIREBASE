# BARBER-APK-FLUTTER-FIREBASE
<div align="center">

   Barber App
</div>


## Requirements

### TOOLS
- Flutter
- Node JS
- Firebase

### FIRST
```
  Create new flutter project
```
```
  Copy and paste file into your project
```
### Edit pubspec.yaml
```
  dependencies:
  flutter:
    sdk: flutter
  firebase_core: 
  cloud_firestore: 
  firebase_auth: 
  random_string: ^2.3.1
  shared_preferences: ^2.2.3
  cupertino_icons: ^1.0.6
```
```
  assets:
    - images/
```

### Install Flutter Package
```
flutter pub get
```

### Install Firebasetools
``` 
  npm install -g firebase-tools
```

### Login Firebase in your VS Code
``` 
  firebase login
```

## Setting Firebase Console
- Go to [Firebase Console](https://firebase.google.com)
- Add new Project
- Create Authenthication -> Email/Password
  <img src="https://raw.githubusercontent.com/2030XMQiu/RECIPE-APP-FLUTTER-WITH-ADMIN-PANEL/main/Screenshot/Screenshot%202024-06-11%20104740.png"/>
- Create Firestore Database -> set rules ->  allow read, write: if true;
- Create Firestore Storage -> set rules ->  allow read, write: if true;
- <img src="https://raw.githubusercontent.com/2030XMQiu/RECIPE-APP-FLUTTER-WITH-ADMIN-PANEL/main/Screenshot/Screenshot%202024-06-11%20105106.png"/>
- Create Collection Firestore Database
- <img src="https://raw.githubusercontent.com/2030XMQiu/RECIPE-APP-FLUTTER-WITH-ADMIN-PANEL/main/Screenshot/Screenshot%202024-06-11%20213441.png" />
- <img src="https://raw.githubusercontent.com/2030XMQiu/RECIPE-APP-FLUTTER-WITH-ADMIN-PANEL/main/Screenshot/Screenshot%202024-06-11%20213555.png" />

### Add Firebase Project to Flutter
``` 
  flutter pub global activate flutterfire_cli
```
``` 
  flutterfire configure
```
- Select your Firebase Project

### Run Your Flutter Project
``` 
  flutter run
```
## Admin Panel Or User
- Go to lib/main.dart
- For Admin Panel -> home: AdminLogin()
- For User -> home: Onboarding()

## Screenshot

<table align="center">
    <tr>
        <th style="text-align:center">
            <a href="">
                <img src="https://github.com/Alvn144p/BARBER-APK-FLUTTER-FIREBASE/blob/main/screenshot/WhatsApp%20Image%202024-06-13%20at%2021.28.23_7fa20caf.jpg" height="500" width="600" />
            </a>
        </th>
        <th style="text-align:center">
            <a href="#">
                <img src="https://github.com/Alvn144p/BARBER-APK-FLUTTER-FIREBASE/blob/main/screenshot/WhatsApp%20Image%202024-06-13%20at%2021.28.24_4e0065aa.jpg" height="500" width="600" />
            </a>
        </th>
    </tr>
</table>




---

## DBAD license

```sh
  > Version 1.0, June 2024

  > Copyright (C) [2024] [Alvn144p Developers]

  > THANKS
  > Alfianto Faidatul Aldi Yumardiansyah
  > Ardyka Bayu Reovan
  > Indah Khoirun Nisa
  > Nailus Saidah Anindia Septiana
```
