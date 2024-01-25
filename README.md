# ProjectU

![ProjectU Logo](/src/Images/ProjectU.png)

By [Ana Paredes](https://github.com/anagparedes)

Web application with MERN Stack (MongoDB, Express, React, and Node.js) for Technical Test workshop in [Solvex Dominicana](https://solvex.com.do/). The goal was to build a project management site where users can create new projects, add tasks, and update their progress as they work.

## Screenshots

![Landing Page](/src/Images/landing.png)

![Dashboard](/src/Images//dashboard.png)

![Profile Page](/src/Images//profile.png)

![Sign Up Page](/src/Images/register.png)

![Login Page](/src/Images/login.png)

## How to Start

Download or clone this repository. Then in main ProjectU-frontend folder use:

```js
npm install
```

In order to get the MongoDB working, create a ".env" file in your project folder. Create variables in the .env file called MONGO_URL and SESSION_SECRET and set it equal to your Mongo connection string and secret phrase respectively. To run this program open up terminal to the backend folder and another terminal window with the frontend folder.

In backend use:

```js
npm test
```

In frontend use:

```js
npm start
```

## Folders
- frontend: contains all frontend material
  - public: houses index.js
  - src: contains javascript files and corresponding stylesheets used to build the site pages (organized by page/component)
