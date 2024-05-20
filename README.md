# Universal Chat

>   A chatroom website using Socket.io and React

This is real time chatroom made using Express and Socket.io for the server and React with shadcn for client frontend. User can register and login, unresgistered users cannot access chatroom. Authorization and Authentication for same is done via JWT and cookies. Both client and server code is in Typescript. Demo credentials:
- username: demo
- password: password

## Features
- Light and dark mode
- Chat Interface

![alt text](https://github.com/0x0-abd/universal-chat/blob/main/img/light.png)
![alt text](https://github.com/0x0-abd/universal-chat/blob/main/img/dark.png)
![alt text](https://github.com/0x0-abd/universal-chat/blob/main/img/chat.png)

## Installation

Clone the repository
```
git clone https://github.com/0x0-abd/universal-chat.git
```

Install server and install dependencies
```
cd server
npm install
```

In the terminal
- Create a .env file in the root of your server directory.
- Supply the following credentials in the file
```
PORT=3001
DATABASE_URL=""
JWT_SECRET=""
```

In the same server directory, type following in terminal to start the server
```
npm i -D ts-node
npx ts-node src/index.ts
```

Go to the client directory and install dependencies
```
cd ..
cd client
npm install
```

Run the client to view the website
```
npm start
```



