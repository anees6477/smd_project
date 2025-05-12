# Screens Directory

This directory contains all the main screen components of the application. Each screen is implemented as a TypeScript React component and represents a distinct view in the application.

## Available Screens

### Authentication Screens
- `LoginScreen.tsx` - Handles user authentication and login functionality
- `SignupScreen.tsx` - Manages new user registration process
- `AuthLoadingScreen.tsx` - Displays loading state during authentication process
- `SplashScreen.tsx` - Initial loading screen shown when the app starts

### User Management Screens
- `ProfileScreen.tsx` - User profile management and personal settings
- `AdminScreen.tsx` - Administrative interface for system management
- `SuperUserScreen.tsx` - Super user interface with advanced controls

### Transaction Management Screens
- `FinanceScreen.tsx` - Financial management and transaction interface
- `PayeeScreen.tsx` - Payee management and related operations
- `VoucherScreen.tsx` - Voucher generation and management system
- `InitiatorScreen.tsx` - Transaction initiation and workflow management
- `PaymentReleaserScreen.tsx` - Payment release and approval interface
- `CheckerScreen.tsx` - Transaction verification and approval system

### Content Management Screens
- `PublisherScreen.tsx` - Content publishing and document management

## Screen Structure

Each screen component follows a consistent structure:
- TypeScript interfaces for props and state
- Component implementation
- Styling (using StyleSheet)
- Navigation handling
- Business logic implementation

## Best Practices

1. Keep screens focused on a single responsibility
2. Implement proper error handling
3. Use TypeScript for type safety
4. Follow the established styling patterns
5. Implement proper loading states
6. Handle navigation appropriately

## Adding New Screens

When adding a new screen:
1. Create a new `.tsx` file in this directory
2. Follow the existing naming convention: `[ScreenName]Screen.tsx`
3. Implement the necessary TypeScript interfaces
4. Add proper navigation configuration
5. Update the navigation stack if required 