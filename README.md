# XTwiiter 
### demo link deployed on render
https://twitter-original.onrender.com/
## Project structures
### ./client 
contains frontend code created using react, redux-toolkit, redux-persist, firebase, tailwindcss
### ./server
contains backend code created using node, express, mongoDB

## Steps to run

```sh
git clone https://github.com/sukhpreet-singh1/Xtweet.git
cd server
npm i
```
add mongodb url in .env file
```sh 
MONGO_URL = "add mongdb url"
```
starting server
```sh
node index.js
```
starting react application 
```sh
cd client
npm i
npm start
```
