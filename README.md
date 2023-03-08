# react-movie-search-app

The provided React application is a movie search app that allows users to search for movies using a search input field. The app uses the OMDB API to fetch movie data and displays the results as a list of movie cards. The user can click on a movie card to see more details about the movie.

The app uses the useState hook to manage the movies and searchName state variables, which keep track of the search results and the user's search query, respectively. It also uses the useEffect hook to trigger a search for movies when the component mounts.

The searchMovies function is responsible for fetching movie data from the OMDB API using the fetch method, and setting the movies state variable with the search results. The MovieCard component is used to display each movie in the list, and the app shows a message if no movies were found.

Overall, this app demonstrates how to use hooks in React to manage state and fetch data from an API, as well as how to display data using reusable components. It can be expanded and customized to include additional features, such as pagination, filtering, and sorting.
