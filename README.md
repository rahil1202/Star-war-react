# Star Wars Planets Directory

## Overview

Welcome to the Star Wars Planets Directory web application! This project utilizes the Star Wars API (SWAPI) to showcase information about planets in the Star Wars universe. The application not only displays details about each planet but also provides information about their notable residents.

## Table of Contents

- [Live Demo](#live-demo)
- [Getting Started](#getting-started)
- [Features](#features)
- [Frameworks and Libraries](#frameworks-and-libraries)
- [Project Structure](#project-structure)
- [License](#license)


## Live Demo

This project is deployed using Vercel.Visit the live demo [Live here](https://star-wars-rahil1202.vercel.app).

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/rahil1202/star-wars-planets-directory.git`
2. Navigate to the project directory: `cd star-wars-planets-directory`
3. Install dependencies: `npm install` (or `yarn install` if you use Yarn)
4. Run the development server: `npm start` (or `yarn start`)

The application will be accessible at `http://localhost:3000` in your web browser.

## Features

1. **Planets Directory:**
   - Information about planets fetched from SWAPI is displayed in distinct cards.
   - Each card includes details such as the planet's name, climate, population, and terrain.

2. **Residents Display:**
   - Within each planet's card, a list of residents is provided.
   - Resident details include the resident's name, height, mass, and gender.

3. **Pagination Mechanism:**
   - Pagination functionality allows users to navigate through the list of planets.
   - User-friendly controls make it easy to move between pages.

4. **Styling and Responsiveness:**
   - The application is styled using CSS for a clean and engaging layout.
   - Responsive design ensures a consistent and appealing user experience across devices and screen sizes.
   - Modern layout techniques such as Flexbox or Grid are employed.

## Frameworks and Libraries

- This project was built using:-
- [React](https://reactjs.org/) as the JavaScript library for building user interfaces.
- [axios](https://axios-http.com/) is used for making HTTP requests to the SWAPI.
- [React Router](https://reactrouter.com/) is utilized for handling navigation and implementing pagination.

## Project Structure

```
star-wars-planets-directory/
|-- src/
|   |-- |-- App.css
|   |   |-- App.js
|   |   |-- CharactersCard.js
|   |   |-- Films.js
|   |   |-- Home.js
|   |   |-- index.js
|   |   |-- Particless.js
|   |   |-- reportWebVitals.js
|-- public/
|   |-- |-- index.html
|-- README.md
|-- package.json
```


## License

This project is licensed under the [MIT License](LICENSE).