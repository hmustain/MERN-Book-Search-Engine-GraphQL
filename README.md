# MERN-Book-Search-Engine-GraphQL
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
        

## Description
This week we put it all together and build a Book Search Engine using MERN. MERN stands for Mongo, express, react, node. We take a fully functioning Google Books API Search engine that was built with RESTful API and refactor it to be a GRAPHQL API built with Apollo Server.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Contributing](#contributing)
- [License](#license)
- [Questions](#questions)

## Installation
Install the following dependencies in root, client, server then run npm install in the root file

### Root
`"scripts": {
    "start": "node server/server.js --ignore client",
    "develop": "concurrently \"cd server && npm run watch\" \"cd client && npm start\"",
    "install": "cd server && npm i && cd ../client && npm i",
    "seed": "cd server && npm run seed",
    "build": "cd client && npm run build"
  },
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "concurrently": "^5.3.0"
  }`
  
### Client
`{
  "name": "client",
  "version": "0.1.0",
  "private": true,
  "proxy": "http://localhost:3001",
  "dependencies": {
    "@apollo/client": "^3.5.8",
    "@testing-library/jest-dom": "^4.2.4",
    "@testing-library/react": "^9.3.2",
    "@testing-library/user-event": "^7.1.2",
    "bootstrap": "^5.2.3",
    "graphql": "^15.4.0",
    "jwt-decode": "^2.2.0",
    "react": "^16.13.1",
    "react-bootstrap": "^2.7.0",
    "react-dom": "^16.13.1",
    "react-router-dom": "^6.9.0",
    "react-scripts": "^5.0.1"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
  "eslintConfig": {
    "extends": "react-app"
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  }
}`

### Server
`{
  "name": "server",
  "version": "1.0.0",
  "description": "",
  "main": "server.js",
  "scripts": {
    "start": "node server.js",
    "seed": "node seeds/seed.js",
    "watch": "nodemon server.js"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "apollo-server-express": "^3.6.2",
    "bcrypt": "^5.1.0",
    "express": "^4.17.2",
    "graphql": "^16.3.0",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^6.9.2"
  },
  "devDependencies": {
    "nodemon": "^2.0.6"
  }
}`

## Usage

### Screenshots
![book-search-not-logged-in](https://user-images.githubusercontent.com/109978698/226711281-7555acb4-e567-4e1c-967f-b05b5889754b.png)
![book-search-not-logged-in-books-searched](https://user-images.githubusercontent.com/109978698/226711445-559a53aa-65d2-4f2a-a8f1-bddcad93dd66.png)
![book-search-logged-in-books-searched](https://user-images.githubusercontent.com/109978698/226711620-33ac2197-1654-42af-add0-d59d9d8fd44d.png)
![books-search-logged-in-book-added](https://user-images.githubusercontent.com/109978698/226711755-209258d1-6a35-4b69-ad81-c534832c26cd.png)
![book-search-logged-in-see-books](https://user-images.githubusercontent.com/109978698/226711775-ed0ef13f-ce57-4486-987c-45fa686a1d0d.png)
![book-search-logged-in-book-deleted](https://user-images.githubusercontent.com/109978698/226711948-2f5f27f0-f320-4245-a85c-47131ec0e985.png)

### Deployed App
https://book-search-hm.herokuapp.com/

## Credits
Tutor, TA's, Instructor, AskBCS and classmates

## Contributing
No contributions allowed <br>


## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
        
Copyright 2022 Hunter Mustain

        Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
        
        The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
        
        THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
https://opensource.org/licenses/MIT
        

## Questions
If you have questions and would like to email me please email me @ hunter@bunkerbranding.com <br>
My GitHub user name and link to my profile can be found by clicking my username <a href="https://github.com/hmustain">hmustain</a>

