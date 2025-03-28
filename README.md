# Angular User Management System

A modern Angular application for user management with role-based authentication and authorization.

## Features

- **Authentication System**
  - Login with username and password
  - Role-based access control (Admin and General User)
  - Secure route protection with guards

- **Dashboard**
  - User information display
  - Role-specific content visibility
  - Real-time user list updates
  - Modern UI with FontAwesome icons

- **Admin Features**
  - Complete user management
  - Add new users with roles
  - View all users in the system
  - Manage user credentials

- **General User Features**
  - View personal information
  - See other general users
  - Protected from admin-only content

## Demo Credentials

```
Admin User:
- Username: admin
- Password: admin123

General User:
- Username: user
- Password: user123
```

## Technical Stack

- Angular 17.1.0
- TypeScript
- RxJS
- FontAwesome Icons
- Angular Router

## Project Structure

```
src/
├── app/
│   ├── components/
│   │   ├── dashboard/
│   │   │   └── dashboard.component.ts
│   │   └── login/
│   │       └── login.component.ts
│   ├── guards/
│   │   └── auth.guard.ts
│   ├── models/
│   │   └── user.model.ts
│   ├── services/
│   │   └── auth.service.ts
│   └── app.routes.ts
└── main.ts
```

## Getting Started

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Start Development Server**
   ```bash
   npm start
   ```

3. **Access the Application**
   - Open your browser and navigate to `http://localhost:4200`
   - Use the demo credentials to log in

## Development Features

- Standalone components
- Lazy loading
- Route protection
- Service architecture
- Reactive state management
- Modern Angular practices

## Styling

- Custom CSS with modern features
- Responsive design
- Glass morphism effects
- Dynamic color schemes
- Interactive UI elements

## Security Features

- Route guards for protected pages
- Role-based access control
- Secure credential handling
- Protected admin routes

## Best Practices

- Component isolation
- Service abstraction
- Type safety with TypeScript
- Reactive programming patterns
- Modern Angular architecture
