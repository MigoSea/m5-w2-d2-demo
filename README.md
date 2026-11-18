# Module 5 - Week 2 Day 2 In-Class Demo: React Router

## Overview
This repository contains the completed **Module 5 Week 2 Day 2 In-Class Exercise/Demo** for **WEB 403/603 Full Stack Web Development** at Westcliff University.

It demonstrates client-side routing in React using `react-router-dom` across two examples:

1. **In-Class Demo #1 (`src/routerexample1.js`)**:
   - Basic navigation using `BrowserRouter as Router`, `Switch`, `Route`, and `Link`.
   - Routes for `/`, `/about`, and `/users`.
2. **In-Class Demo #2 (`src/routerexample2.js`)**:
   - Nested routing and URL parameters using `useRouteMatch` and `useParams`.
   - Dynamic `/topics/:topicId` routes for `Cats` and `Dogs`, displaying `Requested topic ID: {topicId}`.

## Directory Structure
```
m5-w2-d2-demo/
├── demo-app/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── index.css
│   │   ├── index.js
│   │   ├── routerexample1.js
│   │   └── routerexample2.js
│   └── package.json
├── .gitignore
└── README.md
```

## How to Run Locally
1. Navigate to the app folder:
   ```bash
   cd demo-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the app:
   ```bash
   npm start
   ```
   Open `http://localhost:3000/` in your browser.
   *(To switch between Demo #1 and Demo #2, toggle the import in `src/index.js`.)*
