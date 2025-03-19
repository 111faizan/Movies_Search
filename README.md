# Movies Search App

The **Movies Search App** is a React.js-based web application that allows users to search for movies, view detailed information, and save movies to a **Watch Later** list. The app fetches data from a public movie API, providing an intuitive movie discovery experience.

## Key Features:
- **Search Functionality**: Users can search for any movie by entering keywords in the search bar.
- **Movie Listings**: Displays a list of movies matching the search query, with posters, titles, and release dates.
- **Movie Details**: Users can view additional information such as ratings, descriptions, and genres for selected movies.
- **Watch Later**: Users can save movies to a **Watch Later** list and access them whenever needed.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used:
- **React.js**: Frontend framework for building the user interface.
- **CSS**: For styling and making the design responsive.
- **Movie API**: To fetch movie data.
- **LocalStorage**: Used to store the user's **Watch Later** list in the browser.

## Installation & Setup

Follow these steps to install and run the Movies Search App locally.

### 1. Clone the Repository
Open your terminal and run the following command to clone the repository:
```bash
git clone https://github.com/111faizan/Movies_Search.git
```

### 2. Navigate to the Project Directory
```bash
cd movies-search-app
```

### 3. Install Dependencies
Install the required dependencies using **npm** or **yarn**:
```bash
npm install
```
or
```bash
yarn install
```

### 4. Obtain API Key
The app uses a movie database API. Follow these steps to get an API key:
- Visit the [The Movie Database (TMDb)](https://www.themoviedb.org/) website.
- Create an account and generate an API key.
- Store this key in a `.env` file in the project root directory:
  ```
  REACT_APP_API_KEY=your_api_key_here
  ```

## How to Run

### 1. Start the Development Server
To run the app locally, use the following command:
```bash
npm start
```
or
```bash
yarn start
```
The app will be accessible on `http://localhost:3000`.

### 2. Build the App for Production
To create a production build of the app:
```bash
npm run build
```
or
```bash
yarn build
```
This will generate an optimized build in the `build/` directory for deployment.

## Watch Later Functionality

The **Watch Later** feature allows users to save movies to a list that they can return to at any time. This list is stored using the browser's **LocalStorage**, so users won't lose their list when they refresh the page.

### Adding a Movie to Watch Later:
- On the movie card or detail page, users can click a **"Watch Later"** button to add the movie to their list.

### Accessing the Watch Later List:
- Users can navigate to the **Watch Later** section to view the movies they have saved, remove movies from the list, or access detailed information for each.

---

Let me know if you'd like further changes!

![Capture12](https://github.com/user-attachments/assets/811def82-4852-4f68-8d7d-82bc087ff3c6)


![Capture21](https://github.com/user-attachments/assets/34586209-829d-4440-ab8e-abd560362273)
