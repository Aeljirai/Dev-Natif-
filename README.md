# 🎮 Flutter Tic Tac Toe Auth App – BDCC Mobile UI Showcase

A simple yet instructive Flutter-based mobile app for the BDCC curriculum. This project started as a basic navigation and animation demo, and evolved into a login-protected Tic Tac Toe game.

---

## ✨ Features Added

- 🔐 **Login & Sign-Up Screens** with local credential storage using `SharedPreferences`
- 💾 **Saved Login**: User stays logged in between sessions
- 🔓 **Logout** functionality from Tic Tac Toe screen
- 🎯 **Tic Tac Toe Game Logic**: Detects winner or draw
- 🪄 **Popup Result Dialog**: Shows the winner or "Égalité"

---

## 🖼️ Screenshots

<table>
  <tr>
    <td><img src="screenshots/Screenshot 2025-06-28 133022.png" width="200"/></td>
    <td><img src="screenshots/Screenshot 2025-06-28 133029.png" width="200"/></td>
    <td><img src="screenshots/Screenshot 2025-06-28 133051.png" width="200"/></td>
    <td><img src="screenshots/Screenshot 2025-06-28 133112.png" width="200"/></td>
  </tr>
  <tr>
    <td align="center"><b>Login</b></td>
    <td align="center"><b>Sign Up</b></td>
    <td align="center"><b>Account Created</b></td>
    <td align="center"><b>Wrong Credentials</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/Screenshot 2025-06-28 133124.png" width="200"/></td>
    <td><img src="screenshots/Screenshot 2025-06-28 133139.png" width="200"/></td>
    <td><img src="screenshots/Screenshot 2025-06-28 133157.png" width="200"/></td>
  </tr>
  <tr>
    <td align="center"><b>Game Screen</b></td>
    <td align="center"><b>Winner Popup</b></td>
    <td align="center"><b>Draw Popup</b></td>
  </tr>
</table>

---

## 🚀 Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/saadbr/flutter_nav_data.git
   cd flutter_nav_data
   ```

2. Install dependencies  
   ```bash
   flutter pub get
   ```

3. Run the app  
   ```bash
   flutter run
   ```

> ✅ Emulator or real device with Android SDK 34+ recommended

---

## 📁 Folder Structure

```
lib/
├── main.dart
├── screen/
    ├──login.screen.dart
    ├── signup.screen.dart
    └── tictactoe.screen.dart
```

---

## 👨‍💻 Author

**Saad El Mabrouk**  
