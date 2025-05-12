# Zoom Android

A comprehensive React Native mobile application for financial management and user administration, built with TypeScript and modern development practices.

## 🚀 Features

### Authentication & User Management
- Secure user authentication system
- Role-based access control
- User profile management
- Multi-level user hierarchy (Admin, Super User, Regular Users)

### Financial Management
- Transaction initiation and tracking
- Payment processing and approval workflows
- Voucher generation and management
- Payee management system
- Financial reporting and analytics

### Document Management
- Content publishing system
- Document approval workflows
- File management and tracking

## 📱 Screens

The application includes several specialized screens for different functionalities:

### Authentication Screens
- Login and Registration
- Authentication Loading
- Splash Screen

### User Management Screens
- Profile Management
- Admin Dashboard
- Super User Interface

### Transaction Management Screens
- Finance Management
- Payee Management
- Voucher System
- Transaction Initiation
- Payment Release
- Transaction Verification

### Content Management Screens
- Document Publishing
- Content Management

For detailed information about each screen, see the [Screens Directory README](screens/README.md).

## 🛠️ Technical Stack

- **Framework**: React Native
- **Language**: TypeScript
- **State Management**: React Context API
- **Navigation**: React Navigation
- **Styling**: React Native StyleSheet
- **Authentication**: Firebase Authentication
- **Database**: Firebase Firestore

## 📋 Prerequisites

- Node.js (v14 or higher)
- React Native CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)
- JDK 11 or higher
- Firebase account and configuration

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/anees6477/smd_project.git
   cd ZoomAndroid
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **iOS Setup** (macOS only)
   ```bash
   cd ios
   pod install
   cd ..
   ```

4. **Configure Firebase**
   - Create a Firebase project
   - Add your Firebase configuration in `config/firebaseConfig.ts`
   - Enable Authentication and Firestore services

5. **Start the application**
   ```bash
   # For Android
   npm run android

   # For iOS (macOS only)
   npm run ios
   ```

## 📁 Project Structure

```
├── android/           # Android native code
├── ios/              # iOS native code
├── assets/           # Static assets (images, fonts)
├── components/       # Reusable React components
├── config/           # Configuration files
├── context/          # React Context providers
├── screens/          # Application screens
├── utils/            # Utility functions
└── __tests__/        # Test files
```

## 🧪 Available Scripts

- `npm start` - Starts the Metro bundler
- `npm run android` - Runs the app on Android
- `npm run ios` - Runs the app on iOS
- `npm test` - Runs the test suite
- `npm run lint` - Runs the linter

## 🔒 Security

- Secure authentication using Firebase
- Role-based access control
- Secure data transmission
- Input validation and sanitization
- Protected routes and screens

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- **Anees** - *Initial work* - [anees6477](https://github.com/anees6477)

## 🙏 Acknowledgments

- React Native community
- Firebase team
- All contributors and supporters

## 📞 Support

For support, please open an issue in the GitHub repository or contact the maintainers.
