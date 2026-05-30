# JavaScript Calculator (with Firebase History)

A web-based calculator built with HTML, CSS and JavaScript, featuring a clean user interface and basic arithmetic operations. It integrates Firebase Firestore to store and retrieve calculation history in the cloud. Users can view their past calculations from the last seven days via a modal window.
---

## 🎥 Live Demo
GitHub Pages:
Available at [here](https://shoheik12.github.io/)
Click on Calculator.
---

## ✨ Features

- Basic arithmetic operations (+, −, ×, ÷)
- Decimal input support
- Percentage calculation
- Clear (C / AC) functionality
- Cloud-based calculation history
- View past calculations from the last 7 days
- Modal UI for history display
- Real-time data storage using Firebase Firestore

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- Modern JS
- Firebase Firestore
- GitHub Pages

---

## 📱 Firebase Integration

This project uses **Firebase Firestore** as a backend database to store calculation history.

### Stored Data Structure

history (collection)
├── document
│ ├── expression: "3+5"
│ ├── result: 8
│ ├── createdAt: timestamp

---

## Key Learning Points

- DOM manipulation with JavaScript
- Event-driven programming
- Asynchronous operations (`async/await`)
- Firebase Firestore integration
- UI/UX design using modal windows

---

## Setup / Installation
0. Prerequisites
Modern web browser (Chrome, Edge, Safari, etc.)
Firebase account (free tier Spark Plan)

1. Clone the repository
git clone https://github.com/your-username/JSCalculator.git

2. Move into the project directory
cd JSCalculator

3. Open the project in a browser
You can run the project locally by simply opening: index.html
---

## 📝 Notes

- Firestore is configured in test mode for development purposes
- Data is automatically stored in cloud database
- No authentication required for demo version

---

## 🔐 Security Notice

The Firebase API key is intentionally exposed in this repository as GitHub Pages does not support server-side environment variables, making it impossible to fully conceal frontend credentials.

The following security measures have been implemented to prevent unauthorised use:

- **Authorised domain restriction** – Firebase is configured to accept requests only from the authorised domain. Connections originating from any other origin are blocked at the Firebase level.
- **API key referrer restriction** – The API key is restricted via Google Cloud Console to permit requests solely from the designated domain. Any request from an unrecognised referrer is rejected at the Google level.

Whilst the key is visible, these measures ensure it cannot be exploited from outside the authorised domain.

---

## 📈 Future Improvements

- Add delete history feature
- Add user authentication (Firebase Auth)
- Improve UI animations
- Support keyboard input
- Dark mode toggle

---

## 👨‍💻 Author
Shohei Kotera
