# Code Review 

This project is a full-stack web application for code review, featuring an AI-powered backend and a modern React frontend. The app allows users to submit code and receive automated reviews and suggestions.

## Features
- **Frontend**: Built with React and Vite for fast, modern UI.
- **Backend**: Node.js/Express server with AI integration for code analysis.
- **Code Submission**: Users can submit code for review.
- **Automated Feedback**: AI provides suggestions and improvements.

## Project Structure
```
BackEnd/
  package.json
  server.js
  src/
    app.js
    controllers/
      ai.controller.js
    routes/
      ai.routes.js
    services/
      ai.service.js
Frontend/
  package.json
  vite.config.js
  index.html
  src/
    App.jsx
    App.css
    main.jsx
    ...
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm or yarn

### Setup

#### 1. Backend
```
cd BackEnd
npm install
npm start
```
The backend server will start on the configured port (default: 5000).

#### 2. Frontend
```
cd Frontend
npm install
npm run dev
```
The frontend will be available at `http://localhost:5173` by default.

## Usage
1. Open the frontend in your browser.
2. Paste or write code in the editor area.
3. Click the **Review** button to get AI-powered feedback.
4. View suggestions and improvements in the right panel.

## Folder Details
- **BackEnd/**: Express server, AI logic, API endpoints.
- **Frontend/**: React app, UI components, styles.

## Customization
- Update AI logic in `BackEnd/src/services/ai.service.js`.
- Modify UI in `Frontend/src/App.jsx` and styles in `App.css`.

## License
MIT
