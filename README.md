# Dashboard Application

A React-based dashboard application with separate User and Admin interfaces.

## Features

- **User Dashboard**
  - Profile information display
  - User statistics
  - Recent activities
  - Quick actions
  - Responsive design

- **Admin Dashboard**
  - Key metrics and system health monitoring
  - User management with table view
  - System logs tracking
  - Admin action controls
  - Tabbed interface for easy navigation

- **Authentication**
  - Simple role-based login (User/Admin)
  - Session persistence with localStorage
  - Role-based routing

## Project Structure

```
src/
├── pages/
│   ├── LoginPage.js
│   ├── UserDashboard.js
│   └── AdminDashboard.js
├── styles/
│   ├── LoginPage.css
│   ├── UserDashboard.css
│   └── AdminDashboard.css
├── App.js
├── App.css
├── index.js
└── index.css
```

## Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## Usage

1. **Login**: Select your role (User or Admin) and click Login
2. **User Dashboard**: View profile info, statistics, activities, and quick actions
3. **Admin Dashboard**: Manage users, view system health, check logs, and perform admin actions
4. **Logout**: Click the Logout button to return to the login page

## Technologies Used

- React 18
- React Router DOM (for navigation)
- CSS3 (for styling and gradients)
- localStorage (for session management)

## Default Credentials

- **User Login**: Select "User" role
- **Admin Login**: Select "Admin" role

## Features Breakdown

### User Dashboard
- Displays user profile information
- Shows statistics (posts, followers, likes, etc.)
- Lists recent user activities
- Quick action buttons for common tasks

### Admin Dashboard
- **Overview Tab**: Key metrics and system health status
- **Users Tab**: Managed user list with edit/delete options
- **System Logs Tab**: Activity log entries
- Admin action buttons for various management tasks

## Responsive Design

- Mobile-friendly layouts
- Grid-based responsive design
- Adaptive navigation and content

## Customization

- Modify colors in CSS files (gradients use #667eea and #764ba2 for user, #e74c3c for admin)
- Update sample data in component state
- Add real API integration by replacing mock data
- Extend with additional pages/features

## Future Enhancements

- Backend API integration
- Real authentication system
- Database for persisting user data
- More advanced analytics
- User permissions and roles
- Dark mode theme
- Export functionality
