## Secrets Project##

A Postgres + Express + Node.js mini-project showcasing secure secrets handling with EJS templating and environment-based configuration.

## 📑 Table of Contents

About the Project

Features

Screenshots

Prerequisites

Installation & Setup

Usage

Project Structure

Environment Variables

License

## 📌 About the Project

This project demonstrates how to handle user secrets securely in a Node.js + Express application using Postgres for storage and EJS for rendering views.

It covers:
Secure storage of sensitive information
Google OAuth authentication
Proper project structuring for maintainability


## ✨ Features

🔑 User authentication via Google OAuth

🗝️ Secure storage and retrieval of user-submitted secrets

🎨 Frontend rendering with EJS templates

📂 Organized static assets (css, partials, public)

⚙️ .env-based configuration for sensitive credentials


## 🖼️ Screenshots

Login Page


<img width="1440" height="464" alt="image" src="https://github.com/user-attachments/assets/278110f9-9a9e-410d-9b36-1c27cb7c3c1d" />

Secrets Page


<img width="1452" height="525" alt="image" src="https://github.com/user-attachments/assets/46286d82-f46a-44f6-8605-3ba60d30d50b" />

Submit Secret Page


<img width="1449" height="761" alt="image" src="https://github.com/user-attachments/assets/9dfd8c07-080e-4de3-998c-11d82ed8da5b" />

## 🛠 Prerequisites

Make sure you have the following installed:

Node.js (v14 or higher)

npm (comes with Node.js)

PostgreSQL + PgAdmin

Google Cloud Project with OAuth credentials


## ⚡ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/mk00786/secrets_projects.git
cd secrets_projects

2️⃣ Install dependencies

npm install

3️⃣ Create .env file in the root folder

GOOGLE_CLIENT_ID="YOUR GOOGLE CLIENT ID"

GOOGLE_CLIENT_SECRET="YOUR GOOGLE CLIENT SECRET"

SESSION_SECRET="YOUR SECRET STRING"

PG_USER="postgres"

PG_HOST="localhost"

PG_DATABASE=POSTGRES_DATABASE_NAME

PG_PASSWORD=POSTGRES_PASSWORD

PG_PORT=POSTGRES_PORT


4️⃣ Start the development server

npm start

## 🚀 Usage

Go to /register → Create a new user

Go to /login → Authenticate

Go to /secrets → View or submit secrets

Go to /logout → End the session


## 📂 Project Structure

secrets_projects/
├── css/                # Stylesheets

├── partials/           # Header, footer, or reusable EJS templates

├── public/             # Static assets

│   └── css/            # Public-facing CSS

├── views/              # EJS templates

├── .env                # Environment variables (ignored by git)

├── .gitignore

├── index.js            # Entry point

├── package.json

└── package-lock.json

## 🔐 Environment Variables

-----------------------------------------------------------------
| Variable               | Description                          |
| ---------------------- | ------------------------------------ |
| `GOOGLE_CLIENT_ID`     | Google OAuth Client ID               |
| `GOOGLE_CLIENT_SECRET` | Google OAuth Client Secret           |
| `SESSION_SECRET`       | Secret string for session encryption |
| `PG_USER`              | PostgreSQL username                  |
| `PG_HOST`              | Database host                        |
| `PG_DATABASE`          | Database name                        |
| `PG_PASSWORD`          | Database password                    |
| `PG_PORT`              | Database port                        |
-----------------------------------------------------------------

## 📄 License
This project is licensed under the MIT License.
