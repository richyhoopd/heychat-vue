# Vue 3 - Realtime Chat App

Live Demo: [Link](https://heychat-1798e.web.app)

## Project setup

```
npm install
```

# Creating firebase db
1.- Go to firebase console
2.- Click on create new project
3.- Click next on all the following steps
4.- Go to authentication and enable Google authentication
5.- Go to firestore database and create a database
6.- go to the project dashboard and click in "create web application"
7.- name your application and add the SDK to /src/components/firebase.js 
It should look like this: 
```
firebase.initializeApp({
  apiKey: "AIzaSyA6lqH7Btg2peGpOasC9nfjJp5DYZx4sN7A",
  authDomain: "heychat-1798e.firebaseapp.com",
  projectId: "heychat-1798e",
  storageBucket: "heychat-1798e.appspot.com",
  messagingSenderId: "924733071260",
  appId: "1:924733071260:web:a70g670357c4ba98gfb259",
  measurementId: "G-2MHM26HSR5"
})
```


### Compiles for development

```
npm run serve
```

### Compiles for production

```
npm run build
```
