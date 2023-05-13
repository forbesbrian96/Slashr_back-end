# SLASHR - Backend

SLASHR is a web-based app that allows users to log their favorite horror films. The app uses the TMDB (the movie database) API to provide users with information about different horror movies, and allows them to search for specific movies and add them to their watchlist. The backend of the app was built using Express, MongoDB, Mongoose, and the TMDB API.

## Getting Started

To get started, you will need to have Node.js and npm installed on your machine. Then, follow these steps:

1. Clone the repository to your local machine: `git clone https://github.com/YOUR-USERNAME/slashr-backend.git`
2. Install dependencies: `npm install`
3. Create a `.env` file in the root directory of the project and add the following environment variables:
    - `PORT`: the port number for the server to listen on (default is 5000)
    - `MONGODB_URI`: the URI for your MongoDB database
    - `TMDB_API_KEY`: your API key for the TMDB API
4. Start the server: `npm start`

## API Endpoints

The backend provides the following API endpoints:

- `GET /api/movies/search/:query`: search for movies by query
- `GET /api/movies/:id`: get a movie by id
- `GET /api/watchlist/:userId`: get a user's watchlist
- `POST /api/watchlist`: add a movie to a user's watchlist
- `DELETE /api/watchlist/:userId/:movieId`: remove a movie from a user's watchlist

## Built With

- Node.js
- Express
- MongoDB
- Mongoose
- TMDB (API)
- GitHub
- Heroku

## License

SLASHR is released under standard open source license.
