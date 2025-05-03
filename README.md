# GitHub Users API 🚀

A simple REST API built with **Express.js**, deployed on **Vercel**, that serves mock GitHub user data.

## 📌 Features

- **GET `/users`** – Retrieve a list of all users  
- **GET `/users/:id`** – Fetch individual user details by ID  
- CORS enabled  
- JSON response format  
- Easily deployable to Vercel  

## 🛠️ Tech Stack

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Vercel](https://vercel.com/) (for deployment)

## 📂 File Structure

```

.
├── index.js          # Main Express API
└── vercel.json       # Vercel configuration

````

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ajmal92786/backend-users.git
cd backend-users
````

### 2. Install dependencies

```bash
npm install
```

### 3. Run the server locally

```bash
node index.js
```

The server will run at: `http://localhost:3000`

---

## 🌐 API Endpoints

### ✅ Get all users

```
GET /users
```

**Response:**

```json
{
  "users": [
    {
      "id": 1,
      "username": "octocat",
      "name": "The Octocat",
      "repoCount": 8,
      "location": "San Francisco"
    },
    ...
  ]
}
```

### 🔍 Get a user by ID

```
GET /users/:id
```

**Response (Success):**

```json
{
  "user": {
    "id": 2,
    "username": "torvalds",
    "name": "Linus Torvalds",
    "repoCount": 25,
    "location": "Portland"
  }
}
```

**Response (Not Found):**

```json
{
  "message": "User not found."
}
```

---

## 📎 Live Demo

* 🌐 API: [https://backend-users-henna-seven.vercel.app/users](https://backend-users-henna-seven.vercel.app/users)
* 📁 GitHub: [https://github.com/ajmal92786/backend-users.git](https://github.com/ajmal92786/backend-users.git)

---

## 🙌 Contribution

Feel free to fork the repo, raise issues or submit PRs!

---

