# User Authentication with Express and Passport.js

This project sets up user authentication using Express and Passport.js with a local strategy. It securely manages authentication secrets with environment variables. Users can log in with a username and password, which are validated using Passport's local strategy. Session management is handled by Express-Session, and passwords are securely hashed.

## Features

- User authentication with username and password.
- Password hashing for secure storage.
- Session management using Express-Session.
- Secure management of authentication secrets with environment variables.

## Prerequisites

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repo-name
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Create a `.env` file in the root of the project and add the following environment variables:

    ```
    PORT=3000
    SESSION_SECRET=your-session-secret
    ```

## Usage

1. Start the server:

    ```bash
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000`.

## Project Structure

