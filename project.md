# Movie Search Site Documentation

## Overview

This is a simple movie search site built with React. It uses the Open Movie Database (OMDB) API to fetch movie data.

## File Structure

- `App.js`: This is the main application file.
- `App.css`: This file contains all the CSS styles for the application.
- `search.svg`: This is an SVG file used as the search icon in the application.
- `movies.js`: This file is not shown in the excerpt but it presumably contains the `Movie` component used in the application.

## App.js

This file contains the main application component. Here's a breakdown of its structure and functionality:

### Imports

- React's `useState` and `useEffect` hooks are imported for state management and side effects handling.
- The application's main CSS file is imported.
- A search icon SVG file is imported.
- A `Movie` component is imported.

### Constants

- `API_url`: This is the base URL for the OMDB API.

### State Variables

- `movies`: This state variable is used to store the list of movies fetched from the OMDB API.
- `searchTerm`: This state variable is used to store the current search term.

### Functions

- `SearchResults(title)`: This is an asynchronous function that fetches movie data from the OMDB API based on the provided title. The fetched data is then set to the `movies` state variable.

### useEffect Hook

- An `useEffect` hook is used to call the `SearchResults` function when the component mounts.

### Return

- The component returns a `div` with a class of `app`. The rest of the return JSX is not shown in the excerpt.
