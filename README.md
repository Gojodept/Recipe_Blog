🍳 Recipe_Blog

License: MIT
Tech Stack: Node.js · Express.js · MongoDB · EJS · CSS

A fullstack recipe blogging platform where users can upload, browse, edit, and discover recipes. Built with Node.js, Express, and MongoDB, it demonstrates CRUD operations, server-side rendering (EJS), and database persistence.

🎯 Project Overview

Recipe_Blog simulates a real-world blogging application tailored for food lovers. It allows recipe creation, retrieval, updating, and deletion (CRUD), with a simple yet scalable architecture. The project is designed for students, developers, and hobbyists learning fullstack concepts.

🚀 Use Cases

👨‍🍳 Cooks & Foodies: Share and discover recipes

💻 Developers: Learn CRUD operations with Node.js & MongoDB

🎓 Students: Mini-project or portfolio showcase

🏗 Hackathons: Base project to extend with features like auth, images, etc.

✨ Features

📝 Add new recipes with ingredients & instructions

📂 Browse and search recipes

🔍 View recipe details

✏️ Edit and delete recipes (CRUD support)

🎨 Clean UI with EJS templating

📊 MongoDB persistence for recipe data

📁 Project Structure
Recipe_Blog/
├── MongoDB Data/          # Sample DB dump / data
├── public/                # Static assets (CSS, JS, images)
├── server/                # Express server logic
├── views/                 # EJS templates
├── app.js                 # Main application entry point
├── package.json           # Dependencies
├── package-lock.json
├── README.md              # Documentation
├── LICENSE                # MIT License
└── .gitignore

🛠️ Setup & Installation
Prerequisites

Node.js v18+

MongoDB (local or Atlas cluster)

Git

Steps

Clone the repository

git clone https://github.com/Gojodept/Recipe_Blog.git
cd Recipe_Blog


Install dependencies

npm install


Set up environment variables
Create a .env file in the root directory:

MONGO_URI=your_mongodb_connection_string
PORT=5000


Run the application

Development mode (with auto-restart using nodemon if installed):

npm run dev


Production mode:

npm start


Access the app
Open http://localhost:5000
 in your browser.

🔧 Example Commands

Seed initial data (if provided):

node MongoDB\ Data/seed.js


Clear recipe collection:

node MongoDB\ Data/clear.js

🌐 Deployment

You can deploy Recipe_Blog to services like:

Render (for Node.js backend + MongoDB Atlas)

Vercel/Netlify + Backend host

Heroku (legacy but still usable)

Steps to deploy:

Push code to GitHub

Connect deployment platform to repo

Add environment variables (MONGO_URI, PORT) in dashboard

Deploy & get live link

🔒 Security Notes

Never commit .env to GitHub

Use MongoDB Atlas IP whitelisting for database security

Sanitize inputs to prevent injection attacks

⚡ Future Enhancements

🔐 User authentication (login & register)

❤️ Like & save favorite recipes

🖼️ Image upload with Cloudinary or Multer

📱 Responsive mobile-first design

🔎 Advanced filtering & search

🤝 Contributing

Fork the repo

Create a branch:

git checkout -b feature/new-feature


Commit changes:

git commit -m "Add new feature"


Push branch:

git push origin feature/new-feature


Open a Pull Request

📝 License

This project is licensed under the MIT License. See the LICENSE file for details.

🙏 Acknowledgments

Inspired by recipe-sharing platforms like Tasty & AllRecipes

Built for learning fullstack web development with Node.js & MongoDB

Thanks to the open-source community for resources and libraries
