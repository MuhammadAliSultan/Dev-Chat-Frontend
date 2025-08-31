# Dev-Chat Frontend

This is the frontend application for the Dev-Chat real-time chat platform, built with React and Vite. It provides a modern, responsive user interface for chatting, user profiles, group chats, and more.

## 🚀 Features

- User authentication and registration
- Real-time personal and group messaging with Socket.io
- User profile management and public profiles
- Responsive design with Tailwind CSS
- Emoji picker and message reactions
- Notifications and message status indicators

## 🛠️ Tech Stack

- React 19
- Vite (build tool)
- React Router DOM for routing
- Tailwind CSS for styling
- Axios for API requests
- Socket.io-client for real-time communication
- ESLint for code linting

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd dev-chat-mern/frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

The app will be available at `http://localhost:3000` by default.

## 📜 Available Scripts

- `npm run dev` - Start the development server with hot module replacement
- `npm run build` - Build the app for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## 📁 Project Structure

```
frontend/
├── public/                 # Static assets
├── src/
│   ├── api/                # API service modules
│   ├── assets/             # Images, logos, icons
│   ├── components/         # Reusable React components
│   ├── context/            # React context providers
│   ├── hooks/              # Custom React hooks
│   ├── pages/              # Page components for routes
│   ├── App.jsx             # Main app component
│   ├── main.jsx            # Entry point
│   └── index.css           # Global styles
├── package.json
├── vite.config.js
└── README.md
```

## ⚙️ Configuration

- Environment variables can be set in `.env` files as needed for API endpoints or other settings.

## 🤝 Contributing

Contributions are welcome! Please fork the repo and submit pull requests.

## 📝 License

This project is licensed under the ISC License.

---

This frontend works in conjunction with the Dev-Chat backend API to provide a full chat application experience.
