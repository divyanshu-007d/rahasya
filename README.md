# Rahasya - Anonymous Messaging Platform

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)

## Project Overview

Rahasya is a modern anonymous messaging platform that enables users to receive anonymous messages through secure, unique links. Built with privacy and security in mind, it offers a seamless experience across mobile and web platforms.

## ✨ Features

- 📱 Cross-platform mobile app (iOS & Android)
- 🔒 Secure anonymous messaging
- 🔗 Unique shareable user links
- ⚡ Real-time message delivery
- 🌐 Responsive web interface
- 🔄 Seamless synchronization across devices

## 🛠️ Tech Stack

### Frontend
- Mobile App: React Native (Expo)
- Web Landing Page: React.js
- UI Components: React Native Paper
- State Management: Redux

### Backend
- Runtime: Node.js
- Framework: Express.js
- Authentication: Firebase Auth
- Database: Firebase Realtime Database

### Infrastructure
- Hosting: Firebase Hosting
- Storage: Firebase Cloud Storage
- Functions: Firebase Cloud Functions

## 📁 Project Structure

```
rahasya/
├── app/
│   ├── src/
│   ├── assets/
│   └── App.js
├── server/
│   ├── src/
│   ├── routes/
│   └── index.js
├── web/
│   ├── src/
│   ├── public/
│   └── package.json
├── link/
│   ├── public/
│   └── firebase.json
└── README.md
```

## 🚀 Setup Instructions

### Prerequisites

```bash
# Install Node.js (v14 or later)
# Install Firebase CLI
npm install -g firebase-tools

# Install Expo CLI
npm install -g expo-cli
```

### Installation Steps

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/rahasya.git
cd rahasya
```

2. **Mobile App Setup**
```bash
cd app
npm install
expo start
```

3. **Server Setup**
```bash
cd server
npm install
npm run dev
```

4. **Web Setup**
```bash
cd web
npm install
npm start
```

5. **Firebase Configuration**
```bash
firebase login
firebase init
```

## 📦 Deployment

### Deploy Mobile App
```bash
cd app
expo build:android
expo build:ios
```

### Deploy Web
```bash
cd web
npm run build
firebase deploy --only hosting:web
```

### Deploy Server
```bash
cd server
firebase deploy --only functions
```

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create your feature branch:
```bash
git checkout -b feature/AmazingFeature
```
3. Commit your changes:
```bash
git commit -m 'Add some AmazingFeature'
```
4. Push to the branch:
```bash
git push origin feature/AmazingFeature
```
5. Open a Pull Request

## 📝 Environment Variables

Create a `.env` file in each project directory:

```env
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_auth_domain
FIREBASE_DATABASE_URL=your_database_url
FIREBASE_PROJECT_ID=your_project_id
```

## 🔑 Firebase Configuration

Add your Firebase configuration in `app/src/config/firebase.js`:

```javascript
const firebaseConfig = {
  apiKey: process.env.FIREBASE_API_KEY,
  authDomain: process.env.FIREBASE_AUTH_DOMAIN,
  databaseURL: process.env.FIREBASE_DATABASE_URL,
  projectId: process.env.FIREBASE_PROJECT_ID,
};
```

## 📞 Contact

Project Maintainer: Your Name
- Email: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🔍 Additional Resources

- [API Documentation](docs/API.md)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)

## 🙏 Acknowledgments

- React Native Community
- Firebase Team
- All contributors who have helped this project grow

---

**Note:** Replace placeholder values (your_api_key, yourusername, etc.) with actual values before using this README.
