# 🔐 Secrets Web App

A secure full-stack authentication app where users can register, log in, and anonymously share their secrets. Built using **Node.js**, **Express.js**, **PostgreSQL**, **Passport.js**, and **EJS**.

## ✨ Features

- 🔐 **User Authentication**
  - Local username & password login (with bcrypt hashing)
  - Google OAuth 2.0 login

- 📝 **Secret Submission**
  - Authenticated users can submit a "secret"
  - Secrets are displayed anonymously on a shared page

- 💾 **PostgreSQL Database**
  - Stores user credentials and secrets
  - Uses environment variables for secure configuration

## 🛠️ Tech Stack

| Category         | Technology                        |
|------------------|------------------------------------|
| Backend          | Node.js, Express.js               |
| Frontend         | EJS, Bootstrap                    |
| Authentication   | Passport.js, bcrypt, Google OAuth |
| Database         | PostgreSQL                        |
| Deployment Ready | Render / Railway (with env vars)  |

## 🔐 Authentication Methods

1. **Local Strategy**
   - Username (email) and password (hashed using bcrypt)
2. **Google OAuth 2.0**
   - Users can sign up or log in with their Google account

## Create .env file which has:
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
SESSION_SECRET=your_secret_key
PG_USER=your_db_user
PG_HOST=localhost
PG_DATABASE=secrets
PG_PASSWORD=your_password
PG_PORT=5432


## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/Thirumani-Akshitha/secrets.git
cd secrets

# Install dependencies
npm install

# Create a PostgreSQL database named 'secrets'
# Update your .env file with your database credentials

# Run the app
node index.js

```
## 🌐 Deployment
This project is ready to deploy on:
-Render
-Railway

Connect your GitHub repo, add environment variables, and deploy.

## 👩‍💻 Author
Thirumani Akshitha
GitHub: @Thirumani-Akshitha




