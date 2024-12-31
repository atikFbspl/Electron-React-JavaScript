# Electron-React-JavaScript

A simple and easy to use electron + react + javascript boilerplate.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Folder Structure](#folder-structure)
- [License](#license)

## Introduction

This project is a [React](https://reactjs.org/) and [Electron](https://www.electronjs.org/) based application built using JavaScript. It combines the power of React for the frontend and Electron for building cross-platform desktop applications.

## Features

- Cross-platform compatibility (Windows, macOS, Linux)
- Fast development with React
- Simple and customizable Electron integration
- Modular and scalable codebase

## Installation

To get started with this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/atikFbspl/Electron-React-JavaScript.git
   cd https://github.com/atikFbspl/Electron-React-JavaScript.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

To build the React app:

```bash
npm run build
```

To start the development server for Electron and launch the Electron app:

```bash
npm run dev:electron
```

## Scripts

Here are the main scripts defined in the `package.json`:

- `npm run build`: Builds the React project for displaying in electron app.
- `npm run dev:electron`: Starts the development environment for Electron.

## Folder Structure

```
root
├── dist-react/           # Production build of the React app
│   ├── assets/           # Static assets for the built app
│   ├── index.html        # Entry point for the built app
├── src/                  # Source code
│   ├── electron/         # Electron main process files
│   │   └── main.js       # Entry point for the Electron main process
│   ├── ui/               # React UI components
│       ├── assets/       # Static assets for React
│       ├── App.jsx       # Main React component
│       ├── App.css       # Styles for the main React component
│       ├── index.css     # Global styles
│       └── main.jsx      # Entry point for the React app
├── node_modules/         # Node.js dependencies
├── .gitignore            # Git ignore rules
├── eslint.config.js      # ESLint configuration
├── index.html            # Main HTML template for development
├── package.json          # Project metadata and scripts
├── package-lock.json     # Lock file for installed dependencies
├── README.md             # Project README
└── vite.config.js        # Vite configuration for the React app
```

## License

This project is licensed under the [MIT License](LICENSE).
