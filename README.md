# Business Card Server

This project is a Node.js API built with Express, enabling users to create and manage business cards. It supports various user roles, including regular users, business users, and admin users.
You can read the documentation [here](https://documenter.getpostman.com/view/34926651/2sA3QqesJn).

## Features

- **Secure Authentication**: Utilize JSON Web Tokens (JWT) for secure authentication and authorization of users accessing the system.
- **Flexible Card Management**: Easily create, update, and delete cards representing your business offerings through RESTful API endpoints.
- **Customizable Configuration**: Leverage the flexibility of the config library to manage environment-specific configurations for different deployment environments.
- **Robust Data Validation**: Ensure data integrity and consistency with the help of the joi library for schema validation of incoming requests.
- **Scalable Database Integration**: Seamlessly connect to MongoDB databases using the popular mongoose library, allowing for scalable and efficient data storage.
- **Express Middleware Support**: Enhance the functionality of your backend with middleware like cors for enabling Cross-Origin Resource Sharing and morgan for HTTP request logging.

## dependencies:

- **bcryptjs:** Version 2.4.3
- **chalk:** Version 4.1.1
- **config:** Version 3.3.11
- **cors:** Version 2.8.5
- **dotenv:** Version 16.4.5
- **express:** Version 4.18.3
- **joi:** Version 17.12.2
- **jsonwebtoken:** Version 9.0.2
- **lodash:** Version 4.17.21
- **mongoose:** Version 8.2.4
- **morgan:** Version 1.10.0

### dev-dependencies:

- **nodemon:** Version 3.1.3

## Installation

To run the project:

1. `git clone <repository-link>`
2. `npm i` (to install all the above dependencies),
3. `npm run dev` (to run it locally) or
   `npm run start` (to run it remotely-provide a database)

## Example Users

I added a few types of users to provide fast access.
You can create your own users aswell when signing up.

| User Type     | Email                         | Password   |
| ------------- | ----------------------------- | ---------- |
| Regular User  | RegularExampleUser@gmail.com  | Abc112233! |
| Business User | BusinessExampleUser@gmail.com | Abc112233! |
| Admin User    | AdminExampleUser@gmail.com    | Abc112233! |
