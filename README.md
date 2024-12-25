# Android-Laptop Sync Project

This project enables users to securely link their Android phone to their laptop for remote access and data synchronization. It provides features like secure device pairing, cloud-based data backup, remote access, and device tracking.


## Features
- **Device Pairing and Authentication**:  
  Pair Android devices and laptops securely using QR code scanning or device ID registration with OAuth2 authentication.
  
- **Data Synchronization**:  
  Sync contacts, messages, files, and media to cloud storage (e.g., Firebase Firestore).

- **Remote Access**:  
  Access synchronized data when the phone is disconnected or lost. Locate the phone via GPS or erase data remotely.

- **Encryption**:  
  Ensure secure transmission and storage of sensitive data using encryption.

- **User Interface**:  
  Simple command-line or graphical interface using `tkinter` for managing synchronization and remote access.

- **Alerts and Logs**:  
  Notifications for remote access attempts and activity logs for security.

---

## Requirements
- Python 3.8 or later
- Firebase project setup with credentials JSON file
- Installed dependencies from `requirements.txt`

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wajoel/AndroidLaptopSync.git
   cd AndroidLaptopSync
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up Firebase credentials:
   - Place the Firebase credentials JSON file in the project directory.
   - Update the script to reference the path to the credentials.

4. Run the application:
   ```bash
   python android_laptop_sync.py
   ```

---

## Usage

### 1. Device Pairing
- Open the app on both the laptop and the phone.
- Scan the QR code displayed on the laptop with the phone to establish a secure link.

### 2. Synchronization
- Use the "Sync" feature in the app to back up contacts, messages, and media to the cloud.

### 3. Remote Access
- Log in to the app on your laptop to access synced data when your phone is disconnected.
- Use the "Locate Device" option to track the phone's GPS location or the "Erase Data" option for security.

---

## Security Features
- OAuth2 for secure authentication.
- End-to-end encryption for all data transfers.
- Logs of remote access attempts for audit purposes.

---

## Development Setup

### Firebase Setup
1. Go to the [Firebase Console](https://console.firebase.google.com/).
2. Create a new project.
3. Enable Firestore and download the credentials JSON file.
4. Replace `path/to/firebase/credentials.json` in the code with your file's path.

---

## Contributing
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Author
[Joel Wanjala](https://github.com/wajoel)  
Feel free to reach out for questions or collaboration.

---

## Acknowledgements
- [Firebase](https://firebase.google.com/) for cloud services.
- Python libraries like `pyqrcode`, `firebase-admin`, and `tkinter` for seamless implementation.
```

### Steps to Use:
1. Save this file as `README.md` in the root of your project directory.
2. Commit and push it to your GitHub repository:
   ```bash
   git add README.md
   git commit -m "Add README"
   git push
   ```

Let me know if you'd like to customize this further!
