# Clever Todo App

A modern, feature-rich todo application built with React that helps you manage your tasks efficiently.

## Features

- **Priority Levels**: Organize tasks with low, normal, and high priority
- **Color Themes**: Choose between three beautiful themes (Justin, Dirk, Radhika)
- **Local Storage**: Your todos persist even after closing the browser
- **Interactive UI**: 
  - Add new todos with priority selection
  - Mark todos as complete/incomplete
  - Edit existing todos
  - Delete todos with confirmation
- **Responsive Design**: Works well on both desktop and mobile devices

## Getting Started

### Prerequisites

- Node.js (v12 or higher)
- Yarn package manager

### Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd todo
```

2. Install dependencies:
```bash
yarn install
```

3. Start the development server:
```bash
yarn start
```

The application will open in your default browser at [http://localhost:3000/todo](http://localhost:3000/todo).

## Available Scripts

- `yarn start` - Runs the app in development mode
- `yarn test` - Launches the test runner
- `yarn build` - Builds the app for production
- `yarn eject` - Ejects from Create React App (one-way operation)

## Usage

1. **Adding a Todo**:
   - Enter your task in the input field
   - Select priority level (low, normal, high)
   - Click "Add" or press Enter

2. **Managing Todos**:
   - Click the checkbox to mark a todo as complete
   - Click the edit icon to modify a todo
   - Click the delete icon to remove a todo (with confirmation)

3. **Changing Theme**:
   - Use the theme buttons in the footer to switch between Justin, Dirk, and Radhika themes

## Deployment

The application is configured for deployment to GitHub Pages. To deploy:

```bash
yarn build
yarn deploy
```

The application will be available at [https://justinhorn.name/todo](https://justinhorn.name/todo)

## Built With

- React
- Create React App
- Local Storage for data persistence
- Modern CSS for styling

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
