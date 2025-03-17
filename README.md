# Movie List App

A React-based web application that allows users to browse popular movies, search for specific movies, and manage their favorite movie list. The app uses The Movie Database (TMDb) API to fetch movie data.

## Demo

To see the app in action, follow the [Installation](#installation) steps to run it locally on your machine.

## Features

- **Browse Popular Movies**: View a list of popular movies fetched from TMDb.
- **Search Movies**: Search for movies by title using the search bar.
- **Favorites Management**: Add movies to your favorites list and view them on a dedicated page.
- **Responsive Design**: Fully responsive layout for seamless usage on different devices.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-list-app.git
   cd movie-list-app/frontend
2. Install dependencies
   ```bash
   npm install
3. Set up your API key:
- Open src/services/api.js.
- Replace "insert your api key here" with your TMDb API key. [Get from The Movie Database](https://www.themoviedb.org/)

4. Start the development server
   ```bash
   npm run dev

## Usage
### 1. Home Page:

- Browse popular movies displayed in a grid layout.
- Use the search bar to find specific movies.
### 2. Favorites Page:

- View your favorite movies.
- Add or remove movies from your favorites list.
### 3. Movie Cards:

- Each movie card displays the movie poster, title, and release year.
- Click the heart icon to add/remove a movie from your favorites.
