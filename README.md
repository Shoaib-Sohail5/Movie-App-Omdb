# 🎬 Movie Search Web Application

Welcome to the Movie Search Web Application! This app allows you to search for movies by title and view detailed information about them. Built using React.js, it fetches data from the OMDB API to provide a seamless movie discovery experience.

## ✨ Features

- **Homepage**: Displays a search bar and a grid of popular movies by default.
- **Search Functionality**: Search for movies by title and view results with movie titles and release years.
- **Movie Details Modal**: View additional details about a selected movie, such as plot summary, genre, and ratings, in an interactive modal.
- **Error Handling**: 
  - "No Data Found" message for unmatched search queries.
  - "API Error" message for handling API request errors.

## 📸 Screenshots

### Homepage

![Homepage](https://github.com/Dipanshu-verma/Movie-omdb/assets/128663583/7a9298b7-c312-4119-9e73-36ba20b40ade)
_The homepage displays movie cards in a grid format._

### Movie Details Modal

![Movie Details Modal](https://github.com/Dipanshu-verma/Movie-omdb/assets/128663583/8dc05a9a-65c2-44d8-b1ed-66522d0607aa)
_The modal shows detailed information about the selected movie._

### Loading Skeleton

![Skeleton card While Loading](https://github.com/Dipanshu-verma/Movie-omdb/assets/128663583/a55d29e7-52e7-4292-a05b-3b91e01dbb6a)
_Visible while the API is loading._

### No Data Found

![No Data Found](https://github.com/Dipanshu-verma/Movie-omdb/assets/128663583/9187b7e0-0dbe-4038-abbd-ff95bef1cfdf)
_Displayed when no movies match the search query._

### API Request Error

![API Request Error](https://github.com/Dipanshu-verma/Movie-omdb/assets/128663583/2a19905f-56cd-4d6b-b274-97afb9a8910a)
_Displayed when there is an error making the API request._

## 🔑 Getting an API Key

To use this application, you'll need an API key from OMDB. Follow these steps to obtain your API key:

1. Visit [OMDB API](https://www.omdbapi.com/).
2. Click on the "API Key" tab in the navbar.
    ![API Key Tab](https://github.com/Dipanshu-verma/Movie-omdb/assets/128663583/922451c2-f7d6-4ffb-969c-95d2c0221db6)
3. Select the free account type, enter your details, and submit the form.
    ![API Key Form](https://github.com/Dipanshu-verma/Movie-omdb/assets/128663583/7a69a96e-87d7-40d1-a8a2-a50dac20ab3c)
4. You will receive your API key via email.

## 🛠️ Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Dipanshu-verma/Movie-omdb.git
    cd Movie-omdb
    ```

2. **Install dependencies**:
    ```sh
    npm install
    ```

3. **Create a `.env` file** in the root directory and add your OMDB API key:
    ```
    REACT_APP_OMDB_API_KEY=your_api_key_here
    ```

4. **Run the application**:
    ```sh
    npm start
    ```

5. **Open your browser** and navigate to `http://
