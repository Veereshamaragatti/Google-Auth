# Google Authentication with Supabase and React

This project demonstrates how to implement Google OAuth authentication in a React application using Supabase as the backend service.

## Features

- User authentication with Google OAuth
- Session management
- Protected routes based on authentication status
- Responsive UI built with React

## Prerequisites

Before you begin, ensure you have:

- Node.js (v14.0.0 or later)
- npm or yarn package manager
- A Supabase account and project set up
- Google OAuth credentials configured in your Supabase project

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Veereshamaragatti/Google-Auth.git
cd google-auth-supabase
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Setting up Google OAuth with Supabase

1. Sign in to your [Supabase Dashboard](https://app.supabase.io/)
2. Navigate to your project's Authentication settings
3. Under 'Auth Providers', enable Google provider
4. Follow the instructions to set up a Google Cloud Platform OAuth 2.0 client
5. Enter your Google Client ID and Secret in the Supabase dashboard
6. Add the callback URL from Supabase to your Google OAuth settings

## Project Structure

```
google-auth-supabase/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .env
├── .gitignore
├── index.html
├── package.json
├── README.md
├── supabaseClient.js
└── vite.config.js
```

## Usage

The application provides a simple interface for users to:

- Sign in with Google
- View their authenticated session information
- Sign out

## Building for Production

To build the project for production, run:

```bash
npm run build
# or
yarn build
```

The built application will be available in the `dist` directory.

## Technologies Used

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Supabase](https://supabase.com/)
- [Tailwind CSS](https://tailwindcss.com/)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Youtube reference
-https://youtu.be/2SEz6SK_ekE?si=RHRApWxoxlIwRvg7

