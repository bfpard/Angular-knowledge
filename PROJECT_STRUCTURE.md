# Angular Project Structure

## Overview
This repository contains a newly created Angular 21 project with a clean, organized structure ready for development.

## Project Information
- **Project Name**: project
- **Angular Version**: 21.0.0
- **CLI Version**: 21.0.3
- **Node Version**: 20.19.6
- **Package Manager**: npm 10.8.2

## Directory Structure

```
project/
├── src/
│   ├── app/
│   │   ├── components/          # Reusable UI components
│   │   │   ├── header/         # Header component
│   │   │   └── footer/         # Footer component
│   │   ├── pages/              # Page components
│   │   │   ├── home/           # Home page
│   │   │   └── about/          # About page
│   │   ├── app.ts              # Root component
│   │   ├── app.html            # Root template
│   │   ├── app.css             # Root styles
│   │   ├── app.config.ts       # Application configuration
│   │   ├── app.routes.ts       # Routing configuration
│   │   └── app.spec.ts         # Root component tests
│   ├── index.html              # Main HTML file
│   ├── main.ts                 # Application entry point
│   └── styles.css              # Global styles
├── public/                     # Static assets
├── angular.json                # Angular CLI configuration
├── package.json                # Dependencies
├── tsconfig.json               # TypeScript configuration
└── README.md                   # Project documentation
```

## Generated Components

### 1. Header Component
- **Path**: `src/app/components/header/`
- **Selector**: `app-header`
- **Purpose**: Reusable header component for navigation

### 2. Footer Component
- **Path**: `src/app/components/footer/`
- **Selector**: `app-footer`
- **Purpose**: Reusable footer component for site information

### 3. Home Page
- **Path**: `src/app/pages/home/`
- **Selector**: `app-home`
- **Route**: `/home` (default route)
- **Purpose**: Main landing page

### 4. About Page
- **Path**: `src/app/pages/about/`
- **Selector**: `app-about`
- **Route**: `/about`
- **Purpose**: About page for site information

## Routing Configuration

The project includes a basic routing setup:

```typescript
- '/' → redirects to '/home'
- '/home' → Home component
- '/about' → About component
```

## Available Commands

```bash
# Navigate to project directory
cd project

# Install dependencies (already done)
npm install

# Start development server
npm start
# or
ng serve

# Build for production
npm run build
# or
ng build

# Run tests
npm test
# or
ng test

# Watch mode for development
npm run watch
```

## Development Server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Building

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Next Steps

From this base project, you can:

1. **Customize components**: Edit the generated components in `src/app/components/` and `src/app/pages/`
2. **Add more components**: Use `ng generate component <name>` to create new components
3. **Add services**: Use `ng generate service <name>` to create services
4. **Add routing**: Extend `app.routes.ts` with more routes
5. **Add forms**: Use Angular Forms module for user input
6. **Add HTTP**: Use HttpClient for API calls
7. **Style the app**: Modify CSS files or add a UI library like Angular Material

## Project Features

- ✅ Standalone components architecture
- ✅ Angular Router configured
- ✅ TypeScript support
- ✅ Vitest testing framework
- ✅ Development and production build configurations
- ✅ Clean project structure with components and pages separated
- ✅ Ready for immediate development

## Security

- No security vulnerabilities detected by CodeQL analysis
- Project uses the latest stable Angular version
- All dependencies are up to date
