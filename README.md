# User Service

Authentication and user management service. Part of a microservice e-commerce platform: [shop-user-service](https://github.com/olegcntu/shop-user-service), [shop-product-service](https://github.com/olegcntu/shop-product-service), [shop-blog-service](https://github.com/olegcntu/shop-blog-service), [shop-ai-service](https://github.com/olegcntu/shop-ai-service) and the React client [shop-ui-react](https://github.com/olegcntu/shop-ui-react).

## Features

- Registration, login and logout with JWT access and refresh tokens
- Password reset by e-mail
- Roles and admin endpoints: block and unblock users
- Cart and orders
- Docker image

## Tech stack

Node.js, Express, MongoDB, Mongoose, JWT, Nodemailer, Docker

## Getting started

Copy `.env.example` to `.env` and fill in your MongoDB connection string, JWT secret, SMTP and Cloudinary credentials.

```bash
npm install
npm start
```
