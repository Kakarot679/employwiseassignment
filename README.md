# EmployWise Assignment

A React application that integrates with the Reqres API to perform user management functions.

## GitHub Repository

The source code is available at: [https://github.com/yourusername/employwise-assignment](https://github.com/yourusername/employwise-assignment)

## Features

- User Authentication
- Paginated User List
- User Management (Edit/Delete)
- Responsive Design
- Error Handling
- Form Validation
- Dark Mode Support
- Client-side Search and Filtering

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Vercel account (for deployment)

## Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm start
# or
yarn start
```

The application will open in your default browser at `http://localhost:3000`

## API Endpoints Used

- Authentication: POST https://reqres.in/api/login
- Get Users: GET https://reqres.in/api/users
- Update User: PUT https://reqres.in/api/users/{id}
- Delete User: DELETE https://reqres.in/api/users/{id}

## Test Credentials

- Email: eve.holt@reqres.in
- Password: cityslicka

## Technologies Used

- React
- TypeScript
- Material-UI
- React Router
- Axios
- Context API for State Management

## Project Structure

```
src/
  ├── components/     # Reusable components
  ├── pages/         # Page components
  ├── services/      # API services
  ├── context/       # Context providers
  ├── types/         # TypeScript types
  └── utils/         # Utility functions
```

## Features Implementation

1. **Authentication**
   - Login form with validation
   - Token storage in localStorage
   - Protected routes

2. **User List**
   - Paginated display of users
   - Responsive grid layout
   - Loading states
   - Client-side search and filtering

3. **User Management**
   - Edit user details
   - Delete user confirmation
   - Success/Error notifications

## Deployment

### Deploying to Vercel

1. Install Vercel CLI (optional):
```bash
npm install -g vercel
```

2. Build the application:
```bash
npm run build
```

3. Deploy to Vercel:
```bash
vercel
```

Or deploy directly through Vercel's website:

1. Push your code to GitHub
2. Go to [Vercel](https://vercel.com)
3. Import your repository
4. Configure the build settings:
   - Build Command: `npm run build`
   - Output Directory: `build`
5. Click Deploy

## Live Demo

The application is deployed at: [https://employwise-five.vercel.app](https://employwise-five.vercel.app)

Alternative URL: [https://employwise-dj1h7ljxd-hardiks-projects-9ec662da.vercel.app](https://employwise-dj1h7ljxd-hardiks-projects-9ec662da.vercel.app)

## Bonus Features

- Client-side search and filtering
- Responsive design for mobile and desktop
- Form validation
- Error handling
- Loading states
- Dark mode support
- Modern UI with Material-UI
- Smooth animations and transitions 