# Alarm ESP32 Site

A companion project for the ESP32-based proximity alarm system, providing a user interface to control and monitor the backend.

## Features

- **Remote Control:** Interface to remotely activate/deactivate the alarm.
- **Real-time Monitoring:** View the current state and activation time of the alarm.
- **User-Friendly Design:** Simple and intuitive user interface for easy navigation.

## Components

- **HTML/CSS/JavaScript:** Frontend developed using standard web technologies.
- **Firebase SDK:** Connects to the Firebase database for real-time data updates.

## Setup

1. Clone the repository.
2. Open the `index.html` file in a web browser.

## Configuration

- Modify the Firebase configuration in the `firebase.js` file with your Firebase credentials.

```javascript
const firebaseConfig = {
  apiKey: "your_api_key",
  authDomain: "your_auth_domain",
  databaseURL: "your_database_url"
  projectId: "your_project_id",
  storageBucket: "your_storage_bucket",
  messagingSenderId: "your_messaging_sender_id",
  appId: "your_app_id",
  measurementId: "your_measurement_id"
};
```

## Usage

1. Open the `index.html` file in a web browser.
2. Use the provided interface to activate/deactivate the alarm.
3. Real-time updates will reflect the current state and activation time.
4. Monitor the console for any errors or status messages.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
