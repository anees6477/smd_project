# Components Directory

This directory contains reusable React components used throughout the application. These components are designed to be modular, maintainable, and follow consistent styling patterns.

## Available Components

### UI Components
- `AppHeader.tsx` - Common header component used across screens
  - Handles navigation
  - Displays screen title
  - Manages header actions

- `CustomButton.tsx` - Reusable button component
  - Supports different variants (primary, secondary, etc.)
  - Handles loading states
  - Implements proper touch feedback

- `CustomInput.tsx` - Reusable input component
  - Supports different input types
  - Handles validation
  - Manages error states

## Component Structure

Each component follows these guidelines:
- Written in TypeScript
- Implements proper prop types
- Uses consistent styling patterns
- Includes proper documentation
- Handles edge cases and error states

## Best Practices

1. Keep components focused and single-purpose
2. Implement proper TypeScript types
3. Use consistent naming conventions
4. Include proper error handling
5. Follow the established styling patterns
6. Document props and usage

## Adding New Components

When creating a new component:
1. Create a new `.tsx` file in this directory
2. Follow the naming convention: `[ComponentName].tsx`
3. Implement TypeScript interfaces for props
4. Add proper documentation
5. Include necessary styling
6. Test the component thoroughly 