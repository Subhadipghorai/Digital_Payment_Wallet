# Digital Wallet Application

A modern digital payment wallet application built with React, TypeScript, and Supabase, featuring real-time transactions and secure user authentication.

![Digital Wallet Demo](https://images.unsplash.com/photo-1580048915913-4f8f5cb481c4?auto=format&fit=crop&q=80&w=2000)

## Features

- 💳 Secure digital wallet management
- 🔒 User authentication and authorization
- 💸 Real-time money transfers
- 📊 Transaction history tracking
- 💰 Balance management
- 🔐 Row-level security for data protection

## Tech Stack

- **Frontend**: React + TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Database**: Supabase
- **Icons**: Lucide React
- **Build Tool**: Vite

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Supabase account

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd digital-wallet
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up Supabase:
   - Click the "Connect to Supabase" button in your project
   - Copy the environment variables to a new `.env` file:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

```
digital-wallet/
├── src/
│   ├── components/         # React components
│   │   ├── dashboard/     # Dashboard-related components
│   │   └── layout/        # Layout components
│   ├── lib/               # Library configurations
│   ├── store/             # State management
│   └── types/             # TypeScript type definitions
├── supabase/
│   └── migrations/        # Database migrations
└── public/                # Static assets
```

## Core Features

### Authentication
- Email and password authentication
- User profile management
- Secure session handling

### Wallet Operations
- View current balance
- Send money to other users
- Deposit funds
- Withdraw funds
- View transaction history

### Security Features
- Row-level security (RLS)
- Secure password handling
- Protected API endpoints
- Transaction validation

## Development Guidelines

1. **State Management**
   - Use Zustand stores for global state
   - Keep state updates atomic and predictable
   - Implement proper error handling

2. **Component Structure**
   - Create small, reusable components
   - Follow single responsibility principle
   - Implement proper TypeScript types

3. **Database Operations**
   - Use Supabase RLS policies
   - Implement proper error handling
   - Validate data before transactions

4. **Styling**
   - Use Tailwind CSS for styling
   - Follow responsive design principles
   - Maintain consistent UI components

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Lint code
