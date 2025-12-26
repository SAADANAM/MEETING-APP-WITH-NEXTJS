# Meeting App with Next.js

## Prerequisites
- Node.js (v18 or higher recommended)
- NPM

## Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Configure Environment Variables
Create a `.env.local` file in the root directory. You will need credentials from [Clerk](https://clerk.com/) and [GetStream](https://getstream.io/).

**Copy and paste this into `.env.local` and fill in the values:**

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_...
CLERK_SECRET_KEY=sk_test_...

# Clerk Routes
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Stream Video/Chat
NEXT_PUBLIC_STREAM_API_KEY=...
STREAM_SECRET_KEY=...
```

### 3. Run the Development Server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Scripts
- `npm run dev`: Runs the app in development mode.
- `npm run build`: Builds the app for production.
- `npm start`: Starts the production server.
- `npm run lint`: Runs linter.
