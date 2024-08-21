# Universal Chat

>   A chatroom website using Socket.io and React

This is real time chatroom made using Express and Socket.io for the server and React with shadcn for client frontend. User can register and login, unresgistered users cannot access chatroom. Authorization and Authentication for same is done via JWT, OAuth2 and cookies. Postgres database and storage bucket used from Supabase. Both client and server code is in Typescript. Demo website: [Click Here!](https://uc-frontend-five.vercel.app/) 

Demo credentials:
- Username: demo
- Password: password

> [!NOTE]
> The website has been upgraded with many new features such as sending images and changing username.

> [!IMPORTANT]  
> Please try again after 5 minutes from initial login attempt, the server shuts down after 90 minutes of inactivity. Kindly wait 5 minutes after first login attempt and try again.

## Features
- Light and dark mode
- Responsive chat Interface
- Google OAuth Login (NEW)
- Image Uploads (NEW)
- Customize Profile (NEW)

![alt text](https://github.com/0x0-abd/universal-chat/blob/main/img/light.png)
![alt text](https://github.com/0x0-abd/universal-chat/blob/main/img/dark.png)
![alt text](https://github.com/0x0-abd/universal-chat/blob/main/img/chat2.png)

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



