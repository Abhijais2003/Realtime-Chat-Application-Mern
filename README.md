# 🚀 Text-LPU
Text-LPU is a real-time chat application built with React, Node.js, Express, MongoDB, and Socket.IO. It allows users to communicate with each other in real-time via individual and group chats.

## 🌟 Features

- **Real-time Messaging**: Chat with other users in real-time.
- **Individual and Group Chats**: Start conversations with individual users or create group chats.
- **Typing Indicators**: See when other users are typing in a chat.
- **User Authentication**: Secure authentication system using JWT tokens.
- **Responsive Design**: User-friendly interface that works well on desktop and mobile devices.

## 🧑‍💻👩‍💻 Technologies Used

- **Frontend**: React.js, Chakra UI, Socket.IO Client
- **Backend**: Node.js, Express, MongoDB, Socket.IO
- **Authentication**: JWT (JSON Web Tokens)
- **Styling**: Chakra UI, CSS 
- **Deployment**: Heroku (for backend), Vercel/Netlify (for frontend)

## 📷 Screenshots

![Screenshot 1](/Text-LPU-Screenshots/1st.png)
![Screenshot 2](/Text-LPU-Screenshots/2nd.png)
![Screenshot 3](/Text-LPU-Screenshots/3rd.png)
![Screenshot 4](/Text-LPU-Screenshots/4th.png)
![Screenshot 5](/Text-LPU-Screenshots/5th.png)
![Screenshot 6](/Text-LPU-Screenshots/6th.png)
![Screenshot 7](/Text-LPU-Screenshots/7th.png)
![Screenshot 8](/Text-LPU-Screenshots/8th.png)

## 🚗 Getting Started

### Prerequisites

- Node.js installed on your local machine
- MongoDB Atlas account (for remote MongoDB database)

### 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Abhijais2003/Realtime-Chat-Application-Mern.git
   ```

2. Navigate to the project directory:

   ```bash
   cd text-LPU
   ```

3. Install server dependencies:

   ```bash
   npm install
   ```

4. Navigate to the `frontend` directory:

   ```bash
   cd frontend
   ```

5. Install client dependencies:

   ```bash
   npm install
   ```

### 📚 Configuration

1. Create a `.env` file in the root directory:

   ```plaintext
   NODE_ENV=development
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

2. Replace `your_mongodb_uri` with your MongoDB connection string and `your_jwt_secret` with a secret key for JWT token generation.

### 🏃 Running the Application

1. Start the server:

   ```bash
   npm start
   ```

2. Start the client (in another terminal):

   ```bash
   cd frontend
   npm start
   ```

3. Access the application in your web browser at `http://localhost:3000`.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.

## 📄 License

This project is licensed under the MIT License.
