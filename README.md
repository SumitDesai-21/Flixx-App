## Flixx App

Flixx is a movie and TV show discovery app built using HTML, CSS, and JavaScript. It integrates with the TMDB API to fetch and display trending movies, popular TV shows, detailed media pages, and a real-time search feature all with a responsive UI and dynamic routing.

<div style="display:flex; overflow-x:auto; gap:10px;">
  <img src="images/pic1.png">
  <img src="images/pic2.png">
  <img src="images/pic3.png">
  <img src="images/pic4.png">
</div>

### Features

- Browse trending **movies and TV shows**
- Swiper-powered **"Now Playing" slider** (currently in theaters)
- Detailed pages with overviews, ratings, genres, and release dates
- Full featured **search** with **pagination**
- **Responsive design** optimized for all screen sizes


### Technologies Used

- **HTML5** – Semantic and accessible markup
- **CSS3** – Responsive and modern styling
- **JavaScript (Vanilla)** – App logic and dynamic content rendering
- **TMDB API** - Open-source API for movie and TV data
- **Swiper.js** - Modern carousel library for the slider


### Getting Started

#### 1. Clone the Repository

```bash
git clone https://github.com/SumitDesai-21/flixx-app.git
cd flixx-app  
```

#### 2. Get a Free TMDB API Key

- Visit TMDB API Settings
- Create an account and generate a new API key.

#### 3. Add Your API Key

Open myscript.js file and Add your API key.

```
const global = {
  currentPage: window.location.pathname,
  search: {
    term: "",
    type: "",
    page: 1,
    totalPages: 1,
    totalResults: 0,
  },
  api: {
    // Add Your API Key Here.
    apiKey: "",
    apiUrl: "https://api.themoviedb.org/3/",
  },
};
```

#### 4. Run Your App

You can open index.html in your browser or use a local server
(like Live Server in VS Code).

### About the Author
 - **LinkedIn**: [Sumit Desai](https://linkedin.com/in/sumit-v-d-3b6a9632a)
 - **GitHub**: [Sumit Desai](https://github.com/SumitDesai-21)
 
Happy Coding! :heart:
