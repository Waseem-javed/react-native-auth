# 💻 Tech Stack:
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
### Installation

If you don't have React-Native installed on your computer, run the following:

```
npm install -g react-native-cli
```

Go in the `frontend` directory, and run the following:

```
npm install
```

### Run

```npm start

```
Android:

You will need to follow a few steps to run the client:

- Open the file `frontend/src/config.js`
- Modify `localhost` if is not working with it into your local machine ip address e:g http://000.000.00.0:port

## Server

### Installation

If you don't have nodejs installed on your computer, run the following:

```
npm install -g nodejs
```

Go in the `backend` directory, then run the following:

```
npm install
```

### Run

Run the following in the terminal:

```
npm start
```

This will create a server listening on port 8000, you can access it from http://localhost:8000/ or http://yourip:port. The server needs to run at all time when you use the client.

### API Endpoint:

The non-protected entry-points allow authentication and registration:

- `POST /create-user`: Create a new user
- `POST /sign-in`: Authenticate and retrieve the access and refresh tokens in exchange of email/password
- `POST /sign-out`: Log out, revoke access by destroying the user tokens

### Add JWT_SCRET into .env 
I'm using string there change it to .env for jwt-scret
JWT_SECRET= mine is 'meesaw' and
Info..
![image](https://github.com/Waseem-javed/react-native-auth/assets/65248360/034bd3e0-ade8-4b84-ba66-bf4c888c0578)

### Add MONGO_URL into .env
mongodb+srv://[username:password@]host[/[defaultauthdb][?options]]


## Technologies
- React Native
- Node js
- Express js
- jsonwebtoken
- mongodb

- [@waseem-javed](https://github.com/Waseem-javed)
