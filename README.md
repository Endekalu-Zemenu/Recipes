# Taco Recipes Web App

This repository contains the source code for a simple web application that allows users to select their favorite taco ingredient (chicken, beef, or fish) and see the corresponding recipe. The web app is built using HTML, CSS, Node.js, and Express.js.

## Features

- Choose from three different taco ingredients: chicken, beef, or fish.
- View the recipe for the selected taco ingredient, including its protein, salsa, and toppings.
- Simple and intuitive user interface.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Endekalu-Zemenu/Recipes
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the server:

   ```bash
   cd Recipes
   node index.js
   ```
4. Open your browser and navigate to `http://localhost:3000` to view the web app.

## Usage

1. Upon opening the web app, you will see three buttons representing different taco ingredients: chicken, beef, and fish.
2. Click on the button corresponding to your preferred taco ingredient.
3. The web app will display the recipe for the selected taco ingredient, including its protein, salsa, and toppings.
4. If you want to select a different taco ingredient, simply click on another button.

## Directory Structure

1. `public` : Contains static assets such as CSS files.
2. `views` : Contains the EJS template files used for rendering HTML pages.

### Dependencies

1. [Express.js](https://expressjs.com/) : Web application framework for Node.js.
2. [Body-parser](https://www.npmjs.com/package/body-parser) : Node.js body parsing middleware.
3. [EJS](https://ejs.co/) : Embedded JavaScript templating for Node.js.

### Contributing
Contributions are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request.

### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
