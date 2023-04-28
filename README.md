Countries Info App

A React and Node.js web application that allows users to input a country name and retrieves information about that country using the REST Countries API. The application is built using a React frontend and a NodeJS backend running Express.

Table of Contents
Overview
Features
Technologies Used
Installation
Usage
Credits

Overview
The challenge required building a web application that allows users to view information about countries. The information is retrieved from the REST Countries API. Users can search for countries by name, region, and subregion. The application also allows users to view detailed information about each country, including its flag, population, languages spoken, and neighboring countries.

Features
Users can search for countries by name, region, and subregion.
Users can view detailed information about each country.
Users can see neighboring countries for each country.
Users can view the flag, population, languages spoken, and other information about each country.
Technologies Used
React: A JavaScript library for building user interfaces.
NodeJS: An open-source, cross-platform, back-end JavaScript runtime environment.
Express: A fast, unopinionated, minimalist web framework for Node.js.
REST Countries API: A public API that provides information about countries.
Axios: A promise-based HTTP client for the browser and Node.js.
Bootstrap: A popular front-end component library.

Installation
To install the project, follow these steps:

1-Clone the repository to your local machine.

2-Install the dependencies by running npm install in both the client and server directories.

3-Rename the .env.example file in the server directory to .env and add your own API key for the REST Countries API.

Usage
To start the application, follow these steps:

1-In the server directory, run npm start to start the backend server.

2-In the client directory, run npm start to start the React frontend.

3-Open http://localhost:3000 in your browser to view the application.

Credits
This project was built as a coding challenge for a software engineering internship. The REST Countries API was used to retrieve country information. React was used for the frontend and NodeJS running Express was used for the backend. The Axios library was used for HTTP requests, and Bootstrap was used for styling.
