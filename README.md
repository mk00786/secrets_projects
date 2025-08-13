# 9.6 Secrets Project

A Secret (Postgres, Express Node.js) mini-project showcasing secure secrets handling with EJS templating.

---

##  Table of Contents

1. [About the Project](#about-the-project)  
2. [Features](#features)  
3. [Prerequisites](#prerequisites)  
4. [Installation & Setup](#installation--setup)  
5. [Usage](#usage)  
6. [Project Structure](#project-structure)  
7. [Environment Variables](#environment-variables)  
8. [License](#license)

---

## About the Project

This project is a demonstration of handling **user secrets securely** in a MERN-stack environment using EJS views. It shows fundamental patterns for routing, templating, and protecting sensitive data.

---

## Features

- User secrets input with secure backend handling  
- Frontend rendering using **EJS** templates  
- Organized static assets (`css`, `partials`, `public`)  
- Environment-based configuration using `.env` files  
- 
---

## Screenshots
Login Page-
<img width="1440" height="464" alt="image" src="https://github.com/user-attachments/assets/278110f9-9a9e-410d-9b36-1c27cb7c3c1d" />

Secret Page-
<img width="1452" height="525" alt="image" src="https://github.com/user-attachments/assets/46286d82-f46a-44f6-8605-3ba60d30d50b" />

Submitting a secret page-
<img width="1449" height="761" alt="image" src="https://github.com/user-attachments/assets/9dfd8c07-080e-4de3-998c-11d82ed8da5b" />


## Prerequisites

Make sure you have installed the following:

- [Node.js](https://nodejs.org/) (version ≥ 14)  
- [npm](https://www.npmjs.com/) (bundled with Node.js)  
- Pg Admin  
- Google OAuth Authentication used here

---

## Installation & Setup

1. Clone this repository:  
   ```bash
   git clone https://github.com/mk00786/secrets_projects.git
   cd secrets_projects

2. Install dependencies
npm install

3. Create .env in project root folder:
Example-
GOOGLE_CLIENT_ID="YOUR GOOGLE CLIENT ID"

GOOGLE_CLIENT_SECRET="YOUR GOOGLE CLIENT SECRET"

SESSION_SECRET="YOUR SECRET STRING"

PG_USER="postgres"

PG_HOST="localhost"

PG_DATABASE=POSTGRES_DATABASE_NAME

PG_PASSWORD=POSTGRES_PASSWORD

PG_PORT=POSTGRES_PORT

5. Start the development server
npm start

## Usage

Add any quick instructions on navigating or testing features:

- Navigate to /register to create a new user

- Navigate to /login to authenticate

- Visit /secrets to view or submit secret posts

- Logout using /logout

## Project Structure
secrets_projects/
├── css/                # Stylesheets
├── partials/           # Header, footer, or reusable templates
├── public/             # Static assets
│   └── css/            # Public-facing CSS
├── views/              # EJS view templates
├── .env                # Environment variables (not committed)
├── .gitignore
├── index.js            # Entry point
├── package.json
└── package-lock.json

## Environment Variables
Here's a breakdown of the .env values used in this project:

GOOGLE_CLIENT_ID="YOUR GOOGLE CLIENT ID"
GOOGLE_CLIENT_SECRET="YOUR GOOGLE CLIENT SECRET"
SESSION_SECRET="YOUR SECRET STRING"
PG_USER="postgres"
PG_HOST="localhost"
PG_DATABASE=POSTGRES_DATABASE_NAME
PG_PASSWORD=POSTGRES_PASSWORD
PG_PORT=POSTGRES_PORT

## License
MIT
