# Mini IAM System

A student-friendly **mini Identity and Access Management (IAM) system** inspired by platforms like Okta. This project demonstrates how authentication works from the frontend to the backend using **Node.js**, **Express**, **PostgreSQL**, **Docker**, and a simple static frontend.

## Project Overview

This project was built as a practical learning exercise to help students understand how modern login systems work. It covers:

- user registration
- user login
- password hashing
- JWT token generation
- PostgreSQL integration
- Dockerized local development
- frontend to backend communication

The project is designed to be simple enough for students to follow while still teaching real backend and DevOps concepts.

## Features

- Register users with email and password
- Securely hash passwords with `bcrypt`
- Log users in and issue JWT access tokens
- Store user records in PostgreSQL
- Run PostgreSQL and Redis with Docker Compose
- Simple frontend for register and login
- Presentation-style static website for teaching the project

## Tech Stack

### Backend
- Node.js
- Express
- PostgreSQL
- bcrypt
- jsonwebtoken
- dotenv
- cors

### Frontend
- HTML
- CSS
- JavaScript

### DevOps / Local Environment
- Docker
- Docker Compose
- VS Code
- Thunder Client or Postman

## Project Structure

```text
mini-iam/
  auth-server/
    index.js
    db.js
    .env
    package.json
    routes/
      auth.js
  docker-compose.yml
  schema.sql
  frontend/
    index.html
