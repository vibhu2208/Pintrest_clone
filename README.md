# Pinterest Clone

A full-featured Pinterest clone built with modern web technologies, providing a seamless user experience for creating, sharing, and discovering posts. This project includes user authentication, profile management, and an interactive post feed.

## Features

### Authentication Features
- **Login**: Users can log in with a username and password.
- **Registration**: Users can register for an account with a username, email, and date of birth.
- **Password Recovery**: Users can recover their password.
- **Session Management**: Utilizes Passport.js for managing user sessions.

### User Profile Features
- **User Profile Page**: Displays the user's username and posts.
- **Profile Image Upload**: Users can upload a profile image.

### Post Features
- **Post Creation**: Users can create new posts with a title, description, and image.
- **Post Listing**: Users can view a feed of posts, including their own and others'.
- **Post Image Upload**: Users can upload images for their posts.

### Navigation Features
- **Navigation Bar**: Provides easy navigation between pages.
- **Login/Logout**: Users can log in and log out of their accounts.

## Additional Features (Future Enhancements)
- **Search and Discover**: Search functionality and an explore page for discovering popular posts.
- **Comments and Likes**: Users can comment on and like posts, with notifications for interactions.
- **Boards**: Users can create boards to organize their posts and pin posts to boards.
- **Following**: Users can follow others, with posts from followed users appearing in their feed.
- **Enhanced Profile Features**: Adding bio, social links, and follower counts to user profiles.
- **Privacy and Security**: Two-factor authentication and privacy settings.
- **Post Interactions**: Sharing and saving posts for later viewing.
- **User Experience Enhancements**: Infinite scrolling, dark mode, and responsive design.

## Technologies Used
- **Frontend**: React, Redux (for state management), CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: Passport.js
- **Image Upload**: Multer (for handling multipart/form-data)
- **Session Management**: Express-session

## Installation

### Prerequisites
- Node.js
- npm (Node Package Manager)
- MongoDB

### Steps
1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/pinterest-clone.git
    cd pinterest-clone
    ```

2. **Install dependencies**:
    ```sh
    npm install
    cd client
    npm install
    cd ..
    ```

3. **Configure environment variables**:
    Create a `.env` file in the root directory and add the following:
    ```
    PORT=3000
    MONGODB_URI=your_mongodb_uri
    SESSION_SECRET=your_session_secret
    ```

4. **Run the application**:
    ```sh
    npm run dev
    ```

5. **Access the application**:
    Open your browser and navigate to `http://localhost:3000`

## Project Structure
```plaintext
pinterest-clone/
├── client/                # Frontend source code
│   ├── public/            # Public files
│   └── src/               # React components and frontend logic
├── models/                # Mongoose models
├── routes/                # Express routes
├── controllers/           # Route controllers
├── middleware/            # Custom middleware
├── config/                # Configuration files
├── .env                   # Environment variables
├── server.js              # Entry point for the backend
└── README.md              # Project documentation
