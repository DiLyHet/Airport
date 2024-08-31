
# Airport-project

## Deployment link
https://kyiv-airport.netlify.app/

## Overview
This project is a web application built with React and TypeScript, leveraging modern development tools and libraries like Vite, ESLint, Prettier, and SASS. The project is a partial copy of an existing airport with the implementation of the functions of a real site for demonstrating skills.

## Table of Contents
- [Installation](#installation)
- [Scripts](#scripts)
- [Dependencies](#dependencies)
- [Development](#development)
- [Contributing](#contributing)
- [Author](#author)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/DiLyHet/Airport.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Airport
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Scripts
The following scripts are available in the project. You can run them using:
```bash
npm run <script>
```

- dev: Starts the development server with Vite.
- build: Compiles TypeScript and builds the project for production using Vite.
- lint: Runs ESLint to analyze the code for potential errors.
- preview: Previews the production build locally using Vite.
- styles: Compiles SASS files to CSS.
- styles --watch: Watches and compiles SASS files to CSS.

Example:
```bash
npm run dev
```

## Dependencies
### Development Dependencies
- **ESLint**: `eslint`, `@eslint/js`, `eslint-plugin-react-hooks`, `eslint-plugin-react-refresh`
- **Types**: `@types/react`, `@types/react-dom`
- **SASS**: `sass`, `sass-loader`
- **Vite**: `vite`, `@vitejs/plugin-react`
- **TypeScript**: `typescript`, `typescript-eslint`
- **Loader**: `ts-loader`, `style-loader`
- **Other**: `globals`

### Dependencies
- **React**: `react`, `react-dom`
- **Redux**: `redux`, `@reduxjs/toolkit`, `react-redux`
- **Routing**: `react-router-dom`
- **Utilities**: `axios`


## Development
To start the development server, run:
```bash
npm run dev
```

To watch and compile SASS files, run:
```bash
npm run styles --watch
```

To lint the code, run:
```bash
npm run lint
```

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## Author
This project was created by Lydia Hetmanova.
