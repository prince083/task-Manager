# Task Manager App

A modern task management application built with React, Firebase, and Material-UI. This application helps users organize their tasks with a beautiful interface and real-time updates.

## Features

### Authentication
- Secure user authentication with Firebase
- Email/Password login and registration
- Protected routes for authenticated users

### Task Management
- Create, Read, Update, Delete (CRUD) operations
- Real-time updates using Firebase Firestore
- Search functionality
- Infinite carousel for task navigation
- Task categories and priority levels

### User Interface
- Fully responsive design (Mobile, Tablet, Desktop)
- Material Design components
- Loading states and animations

## Getting Started

### Prerequisites
1. Node.js (v14 or higher)
2. npm or yarn package manager
3. Firebase account

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd task-manager
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Firebase Setup**
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com)
   - Enable Authentication (Email/Password)
   - Create a Firestore Database
   - Get your Firebase configuration

4. **Environment Setup**
   - Create a `.env` file in the root directory
   - Add your Firebase configuration:
     ```env
     REACT_APP_FIREBASE_API_KEY=your_api_key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
     REACT_APP_FIREBASE_PROJECT_ID=your_project_id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
     REACT_APP_FIREBASE_APP_ID=your_app_id
     ```

5. **Start Development Server**
   ```bash
   npm start
   ```
   The application will open at [http://localhost:3000](http://localhost:3000)

## Tech Stack

### Frontend
- React 18
- Material-UI v5
- Redux Toolkit
- React Router v6

### Backend Services
- Firebase Authentication
- Firebase Firestore

## Available Scripts

- `npm start` - Run development server
- `npm test` - Run tests
- `npm run build` - Build for production

## Project Structure
```
task-manager/
├── src/
│   ├── components/
│   │   ├── auth/          # Authentication components
│   │   ├── layout/        # Layout components
│   │   └── tasks/         # Task-related components
│   ├── firebase/          # Firebase configuration
│   ├── redux/             # Redux store and slices
│   ├── theme.js           # Material-UI theme
│   ├── App.js
│   └── index.js
├── .env                   # Environment variables
└── package.json
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the Pawnesh kumar License.

---
 Star this repo if you find it helpful!
