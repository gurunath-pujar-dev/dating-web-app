# Swipe 



About This Project:

-   🔐 Authentication System with JWT
-   🛡️ Route Protection
-   👤 User Profile Creation and Updates
-   🖼️ Image Upload for Profiles
-   🔄 Swipe Right/Left Feature
-   💬 Real-time Chat Messaging
-   🔔 Real-time Notifications
-   🤝 Matching Algorithm
-   📱 Responsive Mobile Design

## Technologies Used

### Frontend

- **React**: Library for building user interfaces.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.
- **Socket.IO Client**: For real-time communication.
- **Zustand**: For state management.
- **Axios**: For making HTTP requests.
- **Radix UI**: For accessible UI components.
- **Vite**: For fast development and build processes.

### Backend

- **Node.js**: JavaScript runtime environment.
- **Express**: Web framework for Node.js.
- **MongoDB**: NoSQL database for data storage.
- **Mongoose**: ODM for MongoDB.
- **JWT**: For secure authentication.
- **Bcrypt**: For password hashing.
- **Socket.IO**: For real-time communication.
- **Cloudinary**: For handling image uploads.
- **Nodemon**: For automatic server restarts during development.

### Setup .env file

```bash
PORT=5000
MONGO_URI=<your_mongo_uri>

JWT_SECRET=<your_very_strong_secret>

NODE_ENV=development
CLIENT_URL=http://localhost:5173

CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>

```


### Clone the Repository

```bash
git clone https://github.com/gurunath-pujar-dev/dating-web-app.git
```

### Setup Backend

- Navigate to the server directory:

```bash
cd server
```

- Install dependencies:

```bash
npm install
```

- Start the server:

```bash
npm run dev
```

### Setup Frontend

- Navigate to the client directory:

```bash
cd client
```

- Install dependencies:

```bash
npm install
```

- Start the development server:

```bash
npm run dev
```

## Usage

- Visit http://localhost:5173 to access the application locally.
