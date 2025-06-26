# 🕵️‍♀️ SQL Noir – Crime Scene Data Analysis Game

Welcome to my local deployment of **SQL Noir**, an open-source crime-solving game that sharpens your SQL skills. I set up and customized this project to practice real-world querying, Supabase integration, and Vite app deployment — while also showcasing a bit of fun data storytelling.

## 🔍 About the Game

SQL Noir puts you in the shoes of a data detective. Each case presents a different crime — from theft to murder — and your job is to solve it by writing SQL queries against a relational database.

---

## 🛠️ Tech Stack

- **SQL** – Core query language used for all challenges
- **Supabase** – Open-source backend-as-a-service (PostgreSQL + API)
- **Vite + React** – Lightweight frontend for the game UI
- **TypeScript** – Ensures better structure and maintainability
- **Node.js + NPM** – Environment management

---

## 🚀 My Setup Steps

1. **Cloned the repository locally**
2. Created a **Supabase project** and connected it to this repo using the CLI
3. Set up the `.env` file with my project’s API details
4. Ran database migrations with:
   ```bash
   supabase db push
