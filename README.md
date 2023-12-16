# Flutter-Auction-Marketplace-App

## Features
- **Google One-Time Sign In**
- **Interactive UI**
- **Auction Item Listing**
- **Place Bidding on a item**
- **Dashboard for Results and reports**
- **Winner Announcement**
- **Profile Page with Posted & Owned Item**

## Installation
App requires [Flutter & Dart](hhttps://docs.flutter.dev/get-started/install) v3.0+ to run.

Install the dependencies and devDependencies and start the server.

`flutter pub get`

you also need to setup a firebase Account and generate `google-service.json` file and add sha-1 and sha-2 key to the firebase to run.

Code to generate Sha-1 and Sha-2
```
keytool -list -v -keystore "C:\Users\Mykhailo\.android\debug.keystore" -alias androiddebugkey -storepass android -keypass android
```

then run the project
```
flutter run
```

## Packages/Library used

```
  curved_navigation_bar: ^1.0.3
  image_picker: ^1.0.1
  firebase_core: ^2.15.0
  firebase_auth: ^4.7.1
  google_sign_in: ^6.1.4
  shared_preferences: ^2.2.0
  cloud_firestore: ^4.8.3
  firebase_storage: ^11.2.5
  fluttertoast: ^8.2.2
  slide_countdown: ^0.6.0
  intl: ^0.17.0
  fl_chart: ^0.63.0
```

    


