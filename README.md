# SOCIAL GO

**SOCIAL GO** is a full-stack social media application built with a React frontend and an Express backend. The application allows users to create posts, like and comment on posts, follow other users, and receive notifications.

## Features

- User authentication (signup, login, logout)
- Create, read, update, and delete posts
- Like and comment on posts
- Follow and unfollow users
- View notifications for likes and follows
- View suggested users to follow
- Responsive design

## Tech Stack

### Frontend

- React
- React Router
- React Query
- Tailwind CSS
- DaisyUI
- Vite

### Backend

- Node.js
- Express
- MongoDB
- Mongoose
- Cloudinary (for image uploads)
- JWT (for authentication)
- bcryptjs (for password hashing)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- Cloudinary account (for image uploads)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/hg9336099029/social_go.git
   cd social-go
   ```

2. **Install dependencies for both frontend and backend:**

   ```sh
   npm install
   npm install --prefix frontend
   ```

3. **Create a ************`.env`************ file in the root directory** and add the following environment variables:

   ```sh
   NODE_ENV=development
   PORT=5000
   MONGO_URL=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

## Running the Application

1. **Start the backend server:**

   ```sh
   npm run dev
   ```

2. **Start the frontend development server:**

   ```sh
   npm run dev --prefix frontend
   ```

3. **Open your browser and navigate to:**

   ```sh
   http://localhost:3000
   ```

## Folder Structure

### Backend

```
social_go/
├── controllers/
│   └── ...
├── db/
│   └── ...
├── lib/
│   └── utils/
│       └── ...
├── middleware/
│   └── ...
├── models/
│   └── ...
├── routes/
│   └── ...
├── server.js
└── .env
```

### Frontend

```
social_go/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   └── ...
│   │   ├── hooks/
│   │   │   └── ...
│   │   ├── pages/
│   │   │   └── ...
│   │   ├── utils/
│   │   │   └── ...
│   │   ├── index.css
│   │   ├── index.html
│   │   └── main.jsx
│   ├── public/
│   │   └── ...
│   ├── package.json
└── package.json
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

