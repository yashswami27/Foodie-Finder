🍲 FoodieFinder – Recipe Management App
FoodieFinder is a clean, full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It’s a handy digital cookbook that allows food lovers to add, manage, and organize their favorite recipes. Whether you're experimenting in the kitchen or saving family classics, FoodieFinder keeps it all in one place.

🚀 Core Features
🔐 User Accounts – Sign up and log in securely using JWT tokens and bcrypt-hashed passwords

📝 Add Recipes – Submit detailed recipes with ingredients, steps, and an image link

🗑️ Delete Recipes – Instantly remove recipes from your list

❤️ Favorite Recipes – Like and save preferred dishes

❌ Unsave Any Time – Remove items from favorites easily

📱 Mobile-Responsive UI – Enjoy a seamless interface across all screen sizes

🧰 Tech Stack
Frontend	Backend	Database	Authentication
React.js	Node.js & Express.js	MongoDB	JWT, bcrypt

🔧 Libraries & Tools
Axios – For handling HTTP requests

React Hooks – useState, useEffect for UI logic

React Router DOM – For routing between pages

Mongoose – To define schemas and interact with MongoDB

📁 Folder Overview
bash
Copy
Edit
/client           → React.js frontend  
/server           → Node.js + Express backend  
 ├── /routes      → REST API endpoints  
 └── /models      → Mongoose database schemas  
📌 API Overview
📖 Recipes
GET /api/recipes – Fetch all recipes

POST /api/recipes – Submit a new recipe

DELETE /api/recipes/:id – Delete a recipe by ID

👤 User Auth
POST /api/users/signup – Register a new user

POST /api/users/login – Authenticate user and return JWT

💖 Favorites
POST /api/likedrecipes – Save a recipe to favorites

DELETE /api/likedrecipes/:id – Remove a recipe from favorites

🔄 How It Works
Users register or log in to receive a JWT token

Recipe form inputs are sent to the server via Axios

Backend handles logic and stores data in MongoDB

UI updates dynamically via API calls and state management

Auth-protected routes ensure only logged-in users can manage their content

🔐 Security Measures
Passwords are encrypted using bcrypt before being stored

User sessions are managed with JWT tokens

Routes are protected and accessible only when authorized

🔮 Future Roadmap
⭐ Add recipe rating and review system

🏷️ Categorize recipes with tags or filters

🖼️ Enable file/image uploads

📊 Personalized user dashboard with recipe stats

👨‍💻 Developed By
Yash Swami
BTech CSE, Pandit Deendayal Energy University

🔗 GitHub – Chirag

🔗 GitHub – Your Friend
