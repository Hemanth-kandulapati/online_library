# Online Library Management System

A modern, responsive library management system built with React, TypeScript, and Tailwind CSS.

## Features

- **User Authentication**: Role-based access (Admin, Librarian, Patron)
- **Book Catalog**: Browse, search, and filter books
- **Book Management**: Borrow and return books
- **User Profiles**: Track borrowed books and reading history
- **Dashboard**: Overview of library statistics and activities
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Demo Accounts

- **Patron**: danny@email.com / password
- **Librarian**: anil@email.com / password  
- **Admin**: sireesha@email.com / password
- **Patron**: samatha@email.com / password

## Live Demo

Visit the live application: [Online Library Management System](https://yourusername.github.io/online-library-management/)

## Technologies Used

- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Deployment**: GitHub Pages

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/online-library-management.git
cd online-library-management
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions. Every push to the main branch will trigger a new deployment.

### Manual Deployment

To deploy manually:

1. Build the project:
```bash
npm run build
```

2. Deploy to GitHub Pages:
```bash
npm run deploy
```

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Books/          # Book-related components
│   ├── Dashboard/      # Dashboard components
│   └── Layout/         # Layout components
├── contexts/           # React contexts for state management
├── pages/              # Page components
├── services/           # API services and mock data
├── types/              # TypeScript type definitions
└── assets/             # Static assets
```

## Features Overview

### Authentication System
- Role-based access control
- Secure login/logout functionality
- User session management

### Book Management
- Comprehensive book catalog
- Advanced search and filtering
- Book borrowing and returning
- Availability tracking

### User Management
- User profiles and preferences
- Borrowing history
- Fine tracking
- Reading statistics

### Dashboard
- Library statistics overview
- Recent activities
- Popular books
- Quick actions

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Icons provided by [Lucide React](https://lucide.dev/)
- Images from [Pexels](https://www.pexels.com/)
- Built with [Vite](https://vitejs.dev/) and [React](https://reactjs.org/)
