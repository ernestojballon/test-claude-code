# React Vite Project Guide

## Commands
- **Dev server**: `npm run dev`
- **Build**: `npm run build`
- **Lint**: `npm run lint`
- **Preview build**: `npm run preview`

## Code Style Guidelines
- **Imports**: Group imports by type (React, external libs, internal components, styles)
- **Formatting**: Use modern JS/JSX syntax with function components and hooks
- **Types**: Prefer TypeScript annotations where possible
- **Naming**: 
  - Components: PascalCase
  - Functions/variables: camelCase
  - Constants: UPPER_SNAKE_CASE
- **Error Handling**: Use try/catch for async operations
- **Component Structure**: Props at top, hooks next, handlers then, JSX last

## Git Workflow
- Commit changes via GitHub Actions on push to main branch for deployment
- GitHub Pages deployment configured to use `dist` folder