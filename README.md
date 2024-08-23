<div align="center">

# Book Haven

[![License: MIT](https://img.shields.io/badge/License-MIT-ff0000.svg)](https://opensource.org/licenses/MIT)
![HTML5 Badge](https://img.shields.io/badge/html-ffa600?logo=html5&logoColor=000&style=flat)
![CSS3 Badge](https://img.shields.io/badge/css-ffff00?logo=css3&logoColor=000&style=flat)
![JavaScript Badge](https://img.shields.io/badge/js-008000?logo=javascript&logoColor=000&style=flat)
![JSON Badge](https://img.shields.io/badge/json-0000ff?logo=json&logoColor=000&style=flat)
![npm Badge](https://img.shields.io/badge/npm-4a0080?logo=npm&logoColor=000&style=flat)
![Node.JS Badge](https://img.shields.io/badge/node-ee81ee?logo=node.js&logoColor=000&style=flat)

</div>

## Description

Book Haven is a full-stack web application designed for book enthusiasts who want to search for books, save their favorites, and manage their reading collection online. With an intuitive user interface and powerful backend, Book Haven offers users a seamless experience from browsing to saving and managing books. The application is built with modern web technologies, ensuring it is both responsive and scalable.

## Table of Contents

- [Description](#description)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [Tests](#tests)
- [License](#license)

## Technologies

### Front-End

-   **React**: A JavaScript library for building user interfaces.
-   **Vite**: A fast build tool and development server for modern web projects.
-   **JavaScript (ES6+)**: The core programming language used for front-end logic.
-   **HTML5 & CSS3**: The foundation for structuring and styling the web pages.
-   **GraphQL**: For querying data from the server.

### Back-End

-   **Node.js**: A JavaScript runtime built on Chrome's V8 engine, used to build the server.
-   **Express**: A minimal and flexible Node.js web application framework.
-   **MongoDB**: A NoSQL database used to store user data and book collections.
-   **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js.
-   **GraphQL**: Used for defining the API and querying the database.
-   **JWT** (JSON Web Tokens): For securing routes and managing user authentication.

## Installation

### Prerequisites

-   **Node.js** (version 14.x or higher)
-   **MongoDB** (installed and running)

### Clone the Repository

```bash
git clone https://github.com/your-username/book-haven.git
cd book-haven
```

### Install Dependencies

Navigate to the project’s root directory and run the following commands:

**For the server**:

```bash
cd server
npm install
```

**For the client**:

```bash
cd ../client
npm install
```

### Set Up Environment Variables

Create a `.env` file in the `server` directory and add the following variables:

```bash
MONGODB_URI=mongodb://localhost:27017/book-haven
JWT_SECRET=your_secret_key
```

Replace `your_secret_key` with a secure key of your choice.

### Running the Application

**Start the Server**

```bash
cd server
npm start
```

**Start the Client**

In another terminal window:

```bash
cd client
npm run dev
```

The application should now be running at `http://localhost:3000`.

## Usage

1.  **Sign Up**: Create an account to start saving your favorite books.
2.  **Log In**: Access your account to view your saved books or search for new ones.
3.  **Search Books**: Use the search functionality to find books by title or author.
4.  **Save Books**: Add books to your personal collection for easy access later.
5.  **Manage Collection**: View and manage your saved books from your user dashboard.

<div align="center">

[Visit my website](https://book-haven-client-uv6c.onrender.com/)

</div>

## Features

-   **User Authentication**: Secure sign-up and login process with JWT.
-   **Book Search**: Search for books using a third-party API.
-   **Save Books**: Save your favorite books to your personal collection.
-   **Responsive Design**: The application is fully responsive and works on all devices.
-   **GraphQL API**: Efficient data querying with GraphQL.

## Contributing

Contributions to Book Haven are welcome! Here’s how you can contribute:

1. **Fork the repository** on GitHub.
2. **Create a branch** for your feature `git checkout -b new-feature`.
3. **Make changes** and commit them `git commit -m "Add some feature"`.
4. **Push to the branch** `git push origin new-feature`.
5. **Create a new Pull Request** against the main.

Please ensure your code adheres to the existing style of the project to make your changes easy to understand and integrate!

## Tests

To run tests, navigate to the `server` directory and run:

```
npm test
```

(Note: You will need to write the tests based on the endpoints and operations your application performs, as this is not set up by default.)

## License

Book Haven is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute this application according to the terms of the license.