📘 Users List App

A simple React application that fetches user data from a public API and displays it in a clean, responsive UI using Tailwind CSS.

🚀 Features

Fetches data from a public REST API

Uses async/await for API calls

Loading and error handling

Clean and responsive UI with Tailwind CSS

Modern React Hooks (useState, useEffect)

Simple and beginner-friendly structure

🛠️ Tech Stack

React

Tailwind CSS

JavaScript (ES6+)

Fetch API


🌐 API Used
Public API: https://jsonplaceholder.typicode.com/users

📂 Project Structure
users-list-app/
│
├── src/
│   ├── user.jsx
    ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
└── README.md

⚙️ Installation & Setup

1️⃣ Clone the repository
git clone <https://github.com/prasadrprabhu77/UserList>
cd users-list-app
2️⃣ Install dependencies
npm install
3️⃣ Setup Tailwind CSS 
npm install tailwindcss @tailwindcss/vite
Add this to vite.config.js: import tailwindcss from '@tailwindcss/vite'
add this in plugin: tailwindcss(),
Replace CSS file with tailwindcss(),
4️⃣ Run the project
npm run dev

🧠 How It Works

useEffect runs when the component mounts.

An async function fetches user data.

Data is stored using useState.

Conditional rendering handles:

Loading state

Error state

Displaying users

Tailwind utility classes provide styling.

📸 UI Preview (Description)

Clean white cards

Responsive grid layout

Smooth hover effect

Mobile-friendly design

