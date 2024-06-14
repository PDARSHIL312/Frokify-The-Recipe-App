# forkify Project

# Forkify

Watch the demo video:
https://github.com/PDARSHIL312/Frokify-The-Recipe-App/assets/137078389/dbb34735-3cf5-4bb2-8224-7faf0fc68a2c


Forkify is a web application built with HTML, SASS, and JavaScript. It leverages modern ES6 features and follows Object-Oriented Programming (OOP) principles. This application allows users to search for recipes, add new recipes, bookmark their favorite recipes, and adjust ingredient quantities based on the number of servings.




## Features

- **Search Recipes:** Users can search for their favorite recipes.
- **Add New Recipes:** Users can add their own recipes.
- **Bookmark Recipes:** Users can bookmark recipes for easy access.
- **Adjust Ingredients:** Ingredient quantities adjust automatically based on the number of servings.

## Technologies Used

- **HTML:** Structure of the web application.
- **SASS:** For styling the application.
- **JavaScript (ES6):** Logic and interactivity.
- **API:** Fetching recipe data from [Forkify API](https://forkify-api.herokuapp.com/v2).

## Setup Instructions

### Prerequisites

- Node.js and npm installed on your machine.
- API key from the [Forkify API](https://forkify-api.herokuapp.com/v2).

### Steps

1. **Clone the Repository:**
    ```sh
    git clone <repository-url>
    cd forkify
    ```

2. **Install Dependencies:**
    ```sh
    npm install
    ```

3. **Generate API Key:**
    - Visit [Forkify API](https://forkify-api.herokuapp.com/v2) to generate your API key.

4. **Configure API Key:**
    - Create a `config.js` file in the root directory.
    - Add your API key to the `config.js` file:
    ```js
    export const API_KEY = 'your-api-key';
    ```

5. **Run the Application:**
    ```sh
    npm start
    ```

## Usage

- **Search for a Recipe:**
    - Use the search bar to find recipes by keyword.
- **Add a New Recipe:**
    - Use the form to submit your own recipes.
- **Bookmark a Recipe:**
    - Click the bookmark icon to save your favorite recipes.
- **Adjust Ingredient Quantities:**
    - Use the serving size selector to adjust quantities.

## Project Structure

