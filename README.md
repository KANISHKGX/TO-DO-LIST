# TO-DO LIST

A modern React-based task management application with project organization and time tracking capabilities.

## Features

- **Project Management**: Create and organize tasks within projects
- **Task Board**: Intuitive task management with status tracking
- **Time Tracking**: Built-in timer functionality for tasks
- **Dashboard**: Analytics and overview of tasks and time spent
- **Responsive Design**: Clean, modern interface

## Tech Stack

- **React 19** - Frontend framework
- **Vite** - Build tool and development server
- **CSS3** - Styling
- **ESLint** - Code linting

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd TO-DO-LIST-main
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

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
src/
├── components/          # React components
│   ├── Dashboard.jsx    # Analytics dashboard
│   ├── Navbar.jsx       # Navigation bar
│   ├── ProjectList.jsx  # Project management
│   ├── TaskBoard.jsx    # Task management board
│   └── TaskItem.jsx     # Individual task component
├── context/             # React context providers
│   └── ProjectContext.jsx
├── hooks/               # Custom React hooks
│   ├── useProjects.js   # Project management logic
│   ├── useTasks.js      # Task management logic
│   └── useTimer.js      # Timer functionality
├── styles/              # CSS styles
├── utils/               # Utility functions
└── App.jsx              # Main application component
```

## Usage

1. **Create a Project**: Click the "+" button in the navbar to create a new project
2. **Add Tasks**: Within a project, add tasks to organize your work
3. **Track Time**: Use the built-in timer to track time spent on tasks
4. **View Analytics**: Check the dashboard for task and time statistics

## Contributors

- [@Ranjith00005](https://github.com/Ranjith00005)
- [@Vishwa-V25](https://github.com/Vishwa-V25)
- [@Shy-006](https://github.com/Shy-006)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run linting: `npm run lint`
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).
