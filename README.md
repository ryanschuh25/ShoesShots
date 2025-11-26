ShoesShots/
├── package.json
├── public/
│   └── index.html
├── src/
│   ├── App.js
│   ├── index.js
│   └── index.css
└── README.md


// package.json
{
  "name": "shoesshots",
  "version": "1.0.0",
  "private": true,
  "homepage": "https://ryanschuh25.github.io/ShoesShots",
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.17.0",
    "react-scripts": "5.0.1",
    "gh-pages": "^5.0.0"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }
}


// src/index.js
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';
import './index.css';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<App />);


// public/index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ShoesShots</title>
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>

// src/index.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

// src/App.js
[PASTE YOUR CURRENT App.js CODE HERE]

// README.md
# ShoesShots

Portfolio website for ShoesShots photography.
