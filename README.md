<h1>AI-Powered Chat App using MERN Stack 🚀</h1><BR>
## Installation

### Backend

1. Navigate to the `backend` directory:
    ```sh
    cd backend
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file in the [backend](http://_vscodecontentref_/38) directory and add the following environment variables:
    ```
    MONGODB_URI=<your_mongodb_uri>
    JWT_SECRET=<your_jwt_secret>
    GOOGLE_AI_KEY=<your_google_ai_key>
    REDIS_HOST=<your_redis_host>
    REDIS_PORT=<your_redis_port>
    REDIS_PASSWORD=<your_redis_password>
    ```

4. Start the backend server:
    ```sh
    npm start
    ```

### Frontend

1. Navigate to the [frontend](http://_vscodecontentref_/39) directory:
    ```sh
    cd frontend
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file in the [frontend](http://_vscodecontentref_/40) directory and add the following environment variables:
    ```
    VITE_API_URL=<your_backend_api_url>
    ```

4. Start the frontend development server:
    ```sh
    npm run dev
    ```

## Usage

1. Open your browser and navigate to `http://localhost:3000` to access the application.
2. Register a new user or login with an existing account.
3. Create a new project or join an existing project.
4. Use the chat interface to communicate with other collaborators and the AI.

## License

This project is licensed under the ISC License.
