# The Chat App

A real-time chat application built with the MERN stack.

## Features

- Real-time messaging
- User authentication
- Responsive design

## Technologies Used

- **MongoDB**: Database
- **Express.js**: Backend framework
- **React.js**: Frontend library
- **Node.js**: Backend runtime environment

## Preview

![image]([https://alyshariff.netlify.app/static/media/conversation.354a931554ce1853c126.png])
![image]([https://alyshariff.netlify.app/static/media/conversation.354a931554ce1853c126.png])

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/alys28/the-chat-app.git
   cd the-chat-app
   ```

2. **Install dependencies**:

   - For the server:

     ```bash
     cd server
     npm install
     ```

   - For the client:

     ```bash
     cd ../client
     npm install
     ```

3. **Set up environment variables**:

   - Create a `.env` file in the `server` directory with the following variables:

     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. **Start the application**:

   - In the `server` directory:

     ```bash
     npm start
     ```

   - In the `client` directory:

     ```bash
     npm start
     ```

   The server will run on `http://localhost:5000` and the client on `http://localhost:3000`.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.






