# Movies-Site

Movies-Site is a web application for rating movie videos. This project is built using HTML, CSS, and JavaScript for the frontend, and Node.js and MongoDB for the backend.

## Features

- View a list of movies
- Rate movies
- View average ratings for each movie
- Backend using Node.js and MongoDB to store movie data and ratings

## Technologies Used

### Frontend

- HTML
- CSS
- JavaScript

### Backend

- Node.js
- Express.js
- MongoDB

## Installation

### Prerequisites

- Node.js (latest version)
- MongoDB (installed and running)

### Installation Steps

1. Clone this repository:

    ```sh
    git clone https://github.com/username/Movies-Site.git
    ```

2. Navigate to the project directory:

    ```sh
    cd Movies-Site
    ```

3. Install dependencies for the backend:

    ```sh
    npm install
    ```

4. Create a `.env` file in the root directory of the project and add MongoDB configuration:

    ```env
    MONGODB_URI=your_mongodb_connection_string
    PORT=5000
    ```

5. Start the backend server:

    ```sh
    npm start
    ```

6. Open `index.html` in a browser to view the application.

<!-- ## Project Structure

```sh
Movies-Site/
├── backend/
│   ├── models/
│   │   └── movie.js
│   ├── routes/
│   │   └── movies.js
│   ├── .env
│   ├── server.js
├── public/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── main.js
│   ├── index.html
├── package.json
├── README.md
```

`backend/models/`: Contains the model for MongoDB.
`backend/routes/`: Contains the API routes.
`backend/server.js`: Main file to set up the Node.js server.
`public/css/`: Contains CSS files.
`public/js/`: Contains JavaScript files.
`public/index.html`: Main HTML file. -->

## Usage

1. Open the application in a browser.
2. View the available list of movies.
3. Click on a movie to rate it.
4. View the average rating for each movie.