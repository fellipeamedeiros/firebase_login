# Firebase Login using flutter

## Credentials

Insert your Firebase credentials in the _index.html_ file

```sh
const firebaseConfig = {
  apiKey: "API-KEY",
  authDomain: "AUTH-DOMAIN",
  projectId: "PROJECT-ID",
  storageBucket: "STORAGE-BUCKET",
  messagingSenderId: "MESSAGINGSENDER-ID",
  appId: "APP-ID"
};
```

## Installation

Application requires [Flutter](https://flutter.dev/) to run.

Install the dependencies and start the application.

```sh
flutter pub add firebase_core
flutter pub add firebase_auth
flutter pub add provider
flutter run -d chrome
```