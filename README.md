# Square-Finder-Web-App
Discover Square Finder App - Instantly calculate the square of any number! Seamlessly navigate between pages with local storage. Fast, intuitive, and at your fingertips. Try it now!
Square Finder App is a simple web application that calculates the square of a given number. It consists of three main pages: the home page, the result page, and the about page.

## Table of Contents

- [Square Finder App](#square-finder-app)
  - [Table of Contents](#table-of-contents)
  - [Project Structure](#project-structure)
  - [Features](#features)
  - [Setup](#setup)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Local Storage Usage](#local-storage-usage)
  - [Contributing](#contributing)
  - [License](#license)

## Project Structure

Square Finder App
│
├── index.html # Home page
├── result.html # Result page
├── about.html # About page
├── mystyle.css # Stylesheet
└── README.md # Project documentation


## Features

- **Home Page**: Allows users to input a number and find its square.
- **Result Page**: Displays the square of the number entered on the home page.
- **About Page**: Provides information about the author.
- **Local Storage**: Utilizes local storage to pass data between pages.

## Setup

### Prerequisites

Before you begin, ensure you have the following:

- A web browser (e.g., Google Chrome, Mozilla Firefox).
- An internet connection.
- [Git](https://git-scm.com/) installed on your local machine.

### Installation

1. **Clone the repository**:

   ```sh
   git clone https://github.com/yourusername/square-finder-app.git
   
2. Navigate to the project directory:

   cd square-finder-app

3. Open the project in your favorite code editor:

   code .

4.Open the index.html file in your web browser to start using the app.


This app makes use of the browser's local storage to pass data between multiple pages. Here’s how it works:

Storing Data: When a user enters a number on the home page (index.html) and submits the form, the square of the number is calculated and stored in local storage.
Displaying Data: The result page (result.html) retrieves the squared value from local storage and displays it to the user. If a user attempts to access the result page directly without first entering a number, a message is displayed, and the user is redirected back to the home page.
