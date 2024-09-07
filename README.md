# Chatting App
A real-time chatting application built with technology stack, e.g., Node.js, Express, Socket.io, MongoDB, React, Javascript, Redux etc.
A fully-featured real-time chatting application built using modern web technologies. This app provides a seamless communication experience with real-time updates, user-friendly interfaces, and secure data handling. 

## Features 
+ Real-time Messaging: Chat with friends in real-time.
+ User Authentication: Secure login and registration with JWT (JSON Web Tokens).
+ Group Chats: Create groups and chat with multiple people.
+ Media Sharing: Share images and files.
+ Notifications: Get notified for new messages.
+ Responsive Design: Mobile-first design for a seamless experience on any device.
+ Cloud Storage: Integrated with Cloudinary for storing movie images securely.


## Tech Stack
+ Frontend: [React, Redux, etc.]
+ Backend: [Node.js, Express.js, etc.]
+ Real-time Communication: [Socket.io, WebSockets]
+ Database: [MongoDB,Cloudanary, etc.]
+ Authentication: [JWT, OAuth, etc.]


## Getting Started
To get a local copy up and running follow these simple steps.

### Prerequisites
+ Node.js and npm installed on your machine.
+ MongoDB Atlas account for the database (replace MONGO_URI in server/.env with your MongoDB URI).
+ Cloudinary account for media storage (replace CLOUD_NAME, CLOUD_API_KEY, CLOUDINARY_API_SECRET in server/.env with your Cloudinary credentials).

### Installation
1. Clone the repository
	```
	git clone https://github.com/MayankSingh0402/chatting-app.git
	```

2. Navigate to the backend directory and install dependencies
	```
	cd server
	npm install
	```
 3. Navigate to the Frontend directory and install dependencies
 	```
	cd server
	npm install
	```
4. Set up environment variables by creating a .env file in the backend directory and add the following:
	```
 	MONGO_URI=mongodb+srv://your_username:your_password@cluster0.your_host.mongodb.net/your_database?				retryWrites=true&w=majority
	PORT=3000
	JWT_SECRET=djgjkdshbgjkhfnjksdfhbnsjkdfsdhjfk
	ADMIN_SECRET_KEY= Your Secret key
	NODE_ENV = for deploying purpose
	CLIENT_URL = frontend url
	CLOUDINARY_CLOUD_NAME= Your cloudinary name
	CLOUDINARY_API_KEY = Your cloudinary API key
	CLOUDINARY_API_SECRET =  Your cloudinary API_SECRET
	```
 5. start the development server
	```
 	npm start
 	```
6. Navigate to the frontend directory and create a .env.local file for client-side environment variables:
	```
	VITE_SERVER = http://localhost:3000
 	```
7. Install frontend dependencies and start the app.
	```
	cd ../client
	npm run dev
```
