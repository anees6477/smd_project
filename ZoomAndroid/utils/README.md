# Utils Directory

This directory contains utility functions, constants, and helper modules used throughout the application. These utilities are designed to be reusable and maintain consistent functionality across the app.

## Available Utilities

### Theme and Styling
- `theme.ts` - Application-wide theming configuration
  - Color palette
  - Typography settings
  - Spacing constants
  - Common styles

## Best Practices

1. Keep utility functions pure and stateless
2. Implement proper TypeScript types
3. Document function parameters and return types
4. Include usage examples in comments
5. Follow consistent naming conventions
6. Keep functions focused and single-purpose

## Adding New Utilities

When adding new utilities:
1. Create a new `.ts` file in this directory
2. Follow the naming convention: `[utilityName].ts`
3. Implement proper TypeScript types
4. Add comprehensive documentation
5. Include usage examples
6. Test the utility functions thoroughly

## Usage Guidelines

1. Import utilities as needed:
```typescript
import { theme } from '../utils/theme';
```

2. Use consistent naming for imports
3. Avoid circular dependencies
4. Keep utility functions pure and predictable 