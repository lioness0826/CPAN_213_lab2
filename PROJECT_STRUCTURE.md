Lab2
│
├── tests/ # Jest test files
├── .bundle/ # Metro bundler cache
├── .vscode/ # VS Code debug configs (launch.json, settings.json)
├── .react/ # React Native tools cache
│
├── android/ # Native Android project (Gradle, Java/Kotlin code)
├── ios/ # Native iOS project (Xcode, Swift/Objective-C code)
├── node_modules/ # Dependencies installed by npm
│
├── scripts/ # Utility scripts
│ └── dev-setup.bat # Script to set up development environment
│
├── src/ # Main application source code
│ ├── assets/ # Static assets (images, fonts, etc.)
│ │
│ ├── components/ # Reusable UI components
│ │ ├── common/ # Shared base components (e.g., Button, Header)
│ │ │ └── Header.js
│ │ └── forms/ # Form-related UI components
│ │
│ ├── constants/ # App-wide constants
│ │ └── Colors.js # Color palette
│ │
│ ├── context/ # React Context providers (state management)
│ │
│ ├── hooks/ # Custom React hooks
│ │
│ ├── navigation/ # Navigation setup (React Navigation)
│ │
│ ├── screens/ # App screens
│ │ ├── Auth/ # Authentication-related screens
│ │ ├── Home/ # Home screen
│ │ │ └── HomeScreen.js
│ │ └── Profile/ # Profile-related screens
│ │ └── index.js # Entry point for screen exports
│ │
│ ├── services/ # API calls, configuration files
│ │ └── config.js # Environment-based configuration
│ │
│ ├── styles/ # Global/shared styles
│ │
│ └── utils/ # Helper functions
│ └── helpers.js
│
├── .env # Default environment variables
├── .env.development # Development-specific env vars
├── .env.production # Production-specific env vars
│
├── .eslintrc.js # ESLint configuration
├── .prettierrc.js # Prettier configuration
├── .eslintignore # ESLint ignore rules
├── .prettierignore # Prettier ignore rules
├── PROJECT_STRUCTURE.md
├── app.json # React Native app config
├── app.tsx # Root component
├── index.js # App entry point
├── babel.config.js # Babel configuration
├── jest.config.js # Jest testing config
├── metro.config.js # Metro bundler config
├── tsconfig.json # TypeScript configuration
│
├── package.json # Project dependencies & scripts
├── package-lock.json # Dependency lock file
└── README.md # Project documentation
