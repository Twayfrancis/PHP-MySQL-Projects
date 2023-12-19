# Short-URLs

Short-URLs is a simple URL shortening service built with PHP and MySQL.

## Project Overview

This project allows users to input a URL and returns a shortened version of it. The shortened URL redirects to the original URL when accessed. The application also keeps track of the number of times each shortened URL is clicked.

## Features

- URL shortening: Users can input a URL and receive a shortened version of it.
- Click tracking: The application keeps track of the number of times each shortened URL is clicked.

## Technologies Used

- PHP: The backend logic of the application is written in PHP.
- MySQL: Used for storing the original URLs, their shortened counterparts, and the click counts.
- Bootstrap: Used for styling the frontend.

## Setup

1. Clone the repository to your local machine.
2. Set up a MySQL database and update the `config.php` file with your database credentials.
3. Run the `index.php` file in your web server to start the application.

## Usage

To shorten a URL, enter it into the input field and click the 'Shorten' button. The page will refresh and display the original URL, the shortened URL, and the click count in a table below the input field.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.
