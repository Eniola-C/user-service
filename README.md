# User-Service

## Overview

This is project is centered on **User-Service** which is a microservice responsible for
managing user-related data and functionality.
It provides a centralized user authentication, authorization, and profile management.

## Features

- **User Authentication** : Handles user login, registration, and password management.
- **User Authorization** : Manages user roles, permissions, and access control.
- **User Profile Management** : Allows users to update their profile.
- **User Data Storage** : Stores user data in a secure and scalable manner.

## API Endpoints

- **POST/users** : Creates a new user account
- **GET/users** : Retrieves a list of all users
- **GET /users/:id** : Retrieves a specific user's profile information
- **PATCH /users/ïd** : Updates a specific user's profile information

## Dependencies

- **Database** : Relies on a database to store user data
- **Authentication Provider** : Integrates with an authentication provider to secure authentication

## Benefits

- **Scalability**
- **Security**
- **Flexibility**

## Use Cases

1. User Registration
2. User Login
3. Profile Update
4. User Deletion
