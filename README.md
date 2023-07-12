Introduction

The MoviesApp ReactJS is a web application built using the React JavaScript library. It allows users to search for movies using the OMDb API and displays detailed information about the movies. The application utilizes various technologies such as Bootstrap, Postman, and React Hooks (specifically useEffect and useState) to provide a seamless user experience.

Installation
To install and run the MoviesApp ReactJS, follow these steps:

Clone the repository from GitHub:


git clone https://github.com/KlimentinaIvanova/MoviesApp_ReactJS.git
Navigate to the project directory:


cd MoviesApp_ReactJS
Install the dependencies:

npm install
Create a .env file in the root directory and add your OMDb API key. The file should have the following format:
makefile

REACT_APP_OMDB_API_KEY=YOUR_API_KEY
Start the application:


npm start
The application should now be running on http://localhost:3000.

Configuration
To configure the MoviesApp ReactJS, you need to set up the OMDb API key. The OMDb API key is required to fetch movie data from the OMDb API.

Obtain an API key from the OMDb website (http://www.omdbapi.com/).

Create a .env file in the root directory of the project.

Add the following line to the .env file, replacing YOUR_API_KEY with your actual API key:


REACT_APP_OMDB_API_KEY=YOUR_API_KEY



Usage

Searching for Movies
On the homepage, you will see a search bar.

Enter the title of the movie you want to search for and click the "Search" button.

The application will make a request to the OMDb API with the provided title and display the search results.

Technologies Used


React
React is a JavaScript library for building user interfaces. The MoviesApp ReactJS is built using React and leverages its component-based architecture and virtual DOM for efficient rendering and state management.

OMDb API
The Open Movie Database (OMDb) API is a RESTful web service to obtain movie information. The MoviesApp ReactJS uses the OMDb API to search for movies and fetch detailed information about them.

Bootstrap
Bootstrap is a popular CSS framework that provides a collection of reusable UI components. The MoviesApp ReactJS utilizes Bootstrap to create a responsive and visually appealing user interface.

Postman
Postman is a collaboration platform for API development and testing. While not directly used in the application, Postman is mentioned as it can be helpful for testing and exploring the OMDb API endpoints during development.

React Hooks (useEffect and useState)
React Hooks are functions that allow functional components to use state and other React features without writing a class. The MoviesApp ReactJS utilizes useEffect to perform side effects, such as fetching data from the OMDb API, and useState to manage state within functional components.

