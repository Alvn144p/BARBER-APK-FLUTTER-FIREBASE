# BARBER-APK-FLUTTER-FIREBASE
# RECIPE-APP-FLUTTER-WITH-ADMIN-PANEL
<div align="center">

  ### <img src="https://avatars.githubusercontent.com/u/76401666?s=400&u=53e72048830573e02e46e62b6fb1123b2ac59562&v=4" height="100px"/> 

  ***2030XMqiu***
</div>

<div align="center">
   Recipe App
</div>


<br>
<table align="center">
    <tr>
<!--         <th style="text-align:center">
            <a href="">
                <img src="https://cdn.svgporn.com/logos/youtube-icon.svg" width="40">
            </a>
        </th> -->
        <th style="text-align:center">
            <a href="https://www.instagram.com/knantaufik">
                <img src="https://github.com/aritraroy/social-icons/blob/master/instagram-icon.png?raw=true" width="40">
            </a>
        </th>
<!--         <th style="text-align:center">
            <a href="#">
                <img src="https://cdn.svgporn.com/logos/google-gmail.svg" width="30">
            </a>
        </th> -->
    </tr>
</table>
<br>

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
- For User -> home: AuthGate()

## Screenshot

<table align="center">
    <tr>
        <th style="text-align:center">
            <a href="">
                <img src="https://github.com/2030XMQiu/RECIPE-APP-FLUTTER-WITH-ADMIN-PANEL/blob/main/Screenshot/Screenshot_20240610-230901.jpg" height="500" width="600" />
            </a>
        </th>
        <th style="text-align:center">
            <a href="#">
                <img src="https://github.com/2030XMQiu/RECIPE-APP-FLUTTER-WITH-ADMIN-PANEL/blob/main/Screenshot/Screenshot_20240610-232055.jpg" height="500" width="600" />
            </a>
        </th>
    </tr>
</table>




---

## DBAD license

```sh
  > Version 1.0, June 2024

  > Copyright (C) [2024] [Mqiu Developers]

  > THANKS
  > Alfianto Faidatul Aldi Yumardiansyah
  > Ardyka Bayu Reovan
  > Indah Khoirun Nisa
  > Nailus Sai'dah Anindia Septiana

  Everyone is permitted to copy and distribute verbatim or modified
  copies of this license document.

```
