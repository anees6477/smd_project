# Zoom Android

A React Native mobile application for managing financial transactions and user management.

## Project Overview

This project is a React Native application built with TypeScript, providing a robust mobile solution for financial management and user administration. The application features multiple screens for different user roles and functionalities.

## Directory Structure

```
├── android/           # Android native code and configurations
├── ios/              # iOS native code and configurations
├── assets/           # Static assets (images, fonts, etc.)
├── components/       # Reusable React components
├── config/           # Application configuration files
├── screens/          # Main application screens
├── utils/            # Utility functions and helpers
├── __tests__/        # Test files
└── .bundle/          # Bundle configuration
```

## Prerequisites

- Node.js (v14 or higher)
- React Native CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)
- JDK 11 or higher

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd ZoomAndroid
```

2. Install dependencies:
```bash
npm install
```

3. For iOS (macOS only):
```bash
cd ios
pod install
cd ..
```

## Running the Application

### Android
```bash
npm run android
```

### iOS (macOS only)
```bash
npm run ios
```

## Available Scripts

- `npm start` - Starts the Metro bundler
- `npm run android` - Runs the app on Android
- `npm run ios` - Runs the app on iOS
- `npm test` - Runs the test suite
- `npm run lint` - Runs the linter

## Project Structure Details

### Screens
- `LoginScreen`: User authentication
- `SignupScreen`: New user registration
- `SplashScreen`: Initial loading screen
- `SuperUserScreen`: Administrative interface
- `FinanceScreen`: Financial management interface
- `PayeeScreen`: Payee management interface

### Components
- `AppHeader`: Common header component
- `CustomButton`: Reusable button component
- `CustomInput`: Reusable input component

### Utils
- `theme.ts`: Application theming and styling utilities

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or support, please contact the project maintainers.
