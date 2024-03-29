# Shorty, URL Shortner App

### Features Implemented:
- Authentication using JWT Token
- Creating new shortened URLs
- Viewing analytics with Linegraph for 5 minutes, 1 hour, and 1 day showing the number of clicks
- Copy button to copy the shortURL automatically

### Backend :
1. Clone the repository: `git clone <repository_url>`
2. Navigate to the backend directory: `cd backend`
3. Install dependencies: `npm install`
4. Set up your MongoDB database and configure the connection in `config.js` or `.env` file.
5. Start the backend server: `npm start` or `node server.js`. This will run the backend server on port 8000.

### Frontend (ReactJS):
1. Navigate to the frontend directory: `cd frontend`
2. Install dependencies: `npm install`
3. Make sure the backend server is running.
4. Start the frontend server: `npm start`. This will run the frontend server on port 3000.
5. Access the application in your browser at `http://localhost:3000`.


### Additional Notes:
- Ensure MongoDB is installed and running before starting the backend server.
- Make sure to handle CORS if the frontend and backend are running on different ports.

