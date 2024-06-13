# Voting Application

This is a backend application for a voting system where users can vote for candidates. It provides functionalities for user authentication, candidate management, and voting.

## Features

- User sign up and login with Aadhar Card Number and password
- User can view the list of candidates
- User can vote for a candidate (only once)
- Admin can manage candidates (add, update, delete)
- Admin cannot vote

## Technologies Used

- Node.js
- Express.js
- MongoDB
- JSON Web Tokens (JWT) for authentication

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Prince-1501/voting_app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd voting_app
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Set up environment variables:

    Create a `.env` file in the root directory and add the following variables:

    ```plaintext
    PORT=3000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5. Start the server:

    ```bash
    node server.js
    ```


## Contributing
Contributions are welcome! Please fork the repository and create a pull request.

### Happy voting!

This `README.md` file provides a clear and comprehensive guide for setting up, using, and contributing to the Voting Application.

