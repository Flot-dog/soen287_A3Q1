This project demonstrates an Express.js server with various functionalities, including summation calculation, string manipulation, average and median calculation, and finding a 4-digit number from a given string. The server responds to both GET and POST requests, and the client-side JavaScript interacts with the server using fetch.
Features

    Find Summation:
        Takes a number as input and returns the summation of all numbers from 1 to the given number.

    Uppercase First and Last Letters:
        Takes a string as input and returns the string with the first and last letters of each word capitalized.

    Find Average and Median:
        Takes an array of numbers as input and returns the average and median of the array.

    Find 4-Digit Number:
        Takes a string of numbers as input and returns the first 4-digit number found in the string.

Installation

    Clone the repository:

    bash

git clone <your-repo-url>
cd <your-project-directory>

Install the dependencies:

bash

    npm install

Usage

    Start the Express.js server:

    bash

    node server1.js

    Open your browser and go to http://localhost:3000. You should see the main page with a form for each of the functionalities.

Endpoints

    GET /findSummation?number={number}
    Calculates the summation of numbers from 1 to the given number.

    GET /uppercaseFirstandLast?toString={string}
    Capitalizes the first and last letters of each word in the input string.

    POST /findAverageAndMedian
    Takes an array of numbers and returns the average and median.
    Request body (JSON): { "numbers": [1, 2, 3, ...] }

    GET /find4Digits?numbers={string}
    Returns the first 4-digit number found in the input string.

Files

    server1.js: The Express.js server file containing the endpoints for the various functionalities.
    public/index.html: The client-side HTML file containing forms for user interaction.
    public/script.js: The client-side JavaScript file that handles form submission and communicates with the server via fetch.