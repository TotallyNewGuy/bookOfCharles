# BookOfCharles
A website record stories from different people

This project is my first website after I learn about web development. It was used create-react-app as a frame, and a popular javascript stack MERN(MongoDB, express, react and node.js) from backend to frontend. The frontend deposit on netlify and backend deposit on heroku.

## 1. Quickly set up
### (a). Clone this repository to local folder
```
git clone https://github.com/TotallyNewGuy/BookOfCharles.git
```

### (b). Setup Node.js backend project
- Go to **server** folder, install all dependencies, run this project
```
$ cd BookOfCharles/server
$ npm install
$ npm start
```
- Open .env.example and edit server port and MongoDB URL to configure your database
```
PORT = 'Port'
CONNECTION_URL = 'MongoDB_URL'
```
- Save it, then run your backend project. It will run at your **localhost:"your modified port"**
```
npm start
```
- Done! 👍

### (c). Setup React frontend project
- Go to **client** folder, install all dependencies, run this project
```
$ cd BookOfCharles/client
$ npm install
$ npm start
```
- It will run at localhost:3000 and open in browser automatically! Done! 👍

