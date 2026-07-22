# 🍽️ Recipe Book - Full Stack MERN Application

A modern **Recipe Book Web Application** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** that allows users to discover recipes, search recipes, view detailed cooking instructions, bookmark their favorite recipes, and manage their personal profile through secure authentication.

The application integrates the **Spoonacular API** to fetch thousands of recipes while maintaining user authentication and saved recipes inside **MongoDB**.

> 🚀 Future versions will support creating, editing, deleting, and sharing user-created recipes stored in MongoDB.

---

# 🌐 Live Demo

**client:** https://recipebookjk.netlify.app/
**server:** on render

---

# 📖 Overview

Recipe Book is a full-stack recipe discovery platform where users can register, log in securely, browse recipes from the Spoonacular API, save favorite recipes, and access them anytime from their profile.

The project demonstrates complete authentication, JWT authorization, Redux state management, MongoDB integration, REST APIs, API consumption, and responsive UI development.

---

# ✨ Features

## Authentication

- User Registration
- User Login
- JWT Authentication
- Password Hashing using bcrypt
- Persistent Login using Redux Persist
- Logout functionality

---

## User Profile

- Upload Profile Picture
- View User Information
- Personalized Profile Page
- View Saved Recipes

---

## Recipe Features

- Browse Random Recipes
- Search Recipes
- View Recipe Details
- Cooking Time
- Ingredients
- Complete Instructions
- Recipe Summary
- Save/Bookmark Recipes
- Remove Saved Recipes

---

## Responsive UI

- Dark Theme
- Mobile Friendly
- Modern Card Layout
- Responsive Search Bar
- Interactive Recipe Details

---

# 🛠 Tech Stack

## Frontend

- React.js
- Redux Toolkit
- Redux Persist
- React Router DOM
- Axios
- Formik
- Yup
- SCSS
- FontAwesome

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt
- Multer
- Helmet
- CORS
- dotenv

---

## Database

MongoDB Atlas

---

## External API

Spoonacular API

---

# 📂 Project Structure

```
Recipe-Book
│
├── client
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── redux
│   │   ├── assets
│   │   ├── styles
│   │   └── App.js
│   │
│   └── package.json
│
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── uploads
│   ├── index.js
│   └── package.json
│
└── README.md
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Recipe-Book.git
```

```bash
cd Recipe-Book
```

---

## Install Frontend

```bash
cd client
```

```bash
npm install
```

Create a `.env` file inside the **client** folder.

```env
REACT_APP_RECIPE_APP_API_KEY=YOUR_SPOONACULAR_API_KEY
REACT_APP_API_KEY=your_render_api
```

> Replace `YOUR_SPOONACULAR_API_KEY` with your Spoonacular API key.
> Replace `your_render_api` with your render API key for loacally runing use localhost:8080 .

Start the frontend

```bash
npm start
```

---

## Install Backend

Open another terminal

```bash
cd server
```

Install dependencies

```bash
npm install
```

Create a `.env` file inside the **server** folder.

```env
PORT=5000
MONGODB_URI=YOUR_MONGODB_URI
JWT_SECRET=YOUR_SECRET_KEY
```

Start backend

```bash
npm start
```

---

# 🔐 Environment Variables

## Client (.env)

```env
REACT_APP_RECIPE_APP_API_KEY=YOUR_SPOONACULAR_API_KEY
```

---

## Server (.env)

```env
PORT=5000

MONGODB_URI=YOUR_MONGODB_URI

JWT_SECRET=YOUR_SECRET_KEY
```

---

# 🗄 Database Collections

## Users

Stores

- Name
- Email
- Password (Encrypted)
- Profile Picture

---

## Saved Recipes

Stores

- User ID
- Saved Recipe IDs

---

# 🔑 Authentication Flow

```
Register
      │
      ▼
Password Encryption
      │
      ▼
MongoDB
      │
      ▼
Login
      │
      ▼
JWT Token
      │
      ▼
Protected Routes
```

---

# 🔄 Application Workflow

```
User

↓

Register/Login

↓

JWT Authentication

↓

Search Recipes

↓

Spoonacular API

↓

Recipe Details

↓

Save Recipe

↓

MongoDB

↓

Profile Page
```

---

# 📸 Screenshots

## Register Page

<img width="100%" src="screenshots/register.png"/>

---

## Login Page

<img width="100%" src="screenshots/login.png"/>

---

## Home Page

<img width="100%" src="screenshots/home.png"/>

---

## Recipe Detail

<img width="100%" src="screenshots/details.png"/>

---

## Ingredients

<img width="100%" src="screenshots/ingredients.png"/>

---

## Profile Page

<img width="100%" src="screenshots/profile.png"/>

---

# 🚀 Upcoming Features

The following features are planned for future releases:

### Community Recipes

- Create New Recipe
- Edit Own Recipe
- Delete Own Recipe
- Store User Recipes in MongoDB
- Upload Recipe Images
- Rich Text Recipe Instructions

---

### Social Features

- Like Recipes
- Recipe Ratings
- Comments
- Share Recipes
- Follow Favorite Chefs
- User Recipe Feed

---

### Search & Discovery

- Filter by Category
- Filter by Cuisine
- Vegetarian / Vegan Filters
- Cooking Time Filters
- Difficulty Level
- Trending Recipes
- Pagination

---

### User Dashboard

- My Recipes
- My Saved Recipes
- Recently Viewed Recipes
- Most Liked Recipes
- Profile Editing

---

# 📚 Learning Outcomes

This project demonstrates practical experience with:

- Full Stack MERN Development
- REST API Development
- MongoDB CRUD Operations
- JWT Authentication
- Password Encryption
- File Uploads
- API Integration
- Redux State Management
- Protected Routes
- Responsive UI Design
