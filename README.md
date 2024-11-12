# News Website

This project is a simple responsive News Website that fetches and displays news articles from the GNews API. Users can browse through categories like Business, Politics, Sports, and Technology, as well as search for news by keywords.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Key Configuration](#api-key-configuration)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- Fetches news articles dynamically using the GNews API.
- Displays news articles with images, titles, descriptions, and sources.
- Navigation bar with categories for Business, Politics, Sports, and Technology.
- Search functionality to find news articles based on user input.
- Responsive design for better user experience on different screen sizes.
- Clean and minimalistic user interface.

## Technologies Used

- HTML
- CSS
- JavaScript

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/news-website.git

2. Navigate to the project directory:

cd news-website


3. Open the index.html file in your web browser.

## Usage

- On loading the webpage, it displays news articles related to "India" by default.
- Use the navigation bar to switch between categories like **Business**, **Politics**, **Sports**, and **Technology**.
- Enter keywords in the search bar and press the **Search** button to fetch related news articles.

## API Key Configuration

To use the GNews API, you'll need to configure an API key:

1. Sign up and get an API key from [GNews API](https://gnews.io/).
2. Replace the `API_KEY` value in `script.js` with your API key:
   ```javascript
   const API_KEY = "your-api-key";