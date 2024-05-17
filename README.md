<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

   
</head>
<body>
    <div class="container">
        <h1>MovieApp </h1>

 <h2>Overview</h2>
        <p>MovieApp is a web application designed to display information about movies, including their titles, posters, and ratings. The app fetches data from a movie database API and presents it in a user-friendly interface.</p>

 <h2>Features</h2>
        <ul>
            <li><strong>Movie Listings</strong>: Displays a list of movies with their titles, posters, and ratings.</li>
            <li><strong>Search Functionality</strong>: Allows users to search for movies by title.</li>
            <li><strong>Responsive Design</strong>: Optimized for both desktop and mobile devices.</li>
        </ul>

 <h2>Tech Stack</h2>
        <ul>
            <li><strong>Frontend</strong>: HTML, CSS, JavaScript, React</li>
       
<li><strong>API</strong>: <a href="https://www.omdbapi.com/apikey.aspx" target="_blank">The Movie Database (OMDb) API</a></li>
        </ul>

<h2>Installation</h2>

 <h3>Prerequisites</h3>
        <ul>
            <li>Node.js (version 14 or higher)</li>
            <li>npm (version 6 or higher)</li>
        </ul>
        <h3>Steps</h3>
        <ol>
            <li>Clone the repository:
                <pre><code>git clone https://github.com/Anuj054/movieapp.git
                cd movieApp</code></pre>
            </li>
            <li>Install dependencies:
                <pre><code>npm install</code></pre>
            </li>
            
 <li>Start the development server:
                <pre><code>npm start</code></pre>
            </li>
            <li>Open your browser and navigate to <code>http://localhost:3000</code>.</li>
        </ol>

<ul>
            <li><strong>Browse Movies</strong>: On the homepage, a list of popular movies will be displayed. Each movie entry includes the title, poster, and rating.</li>
            <li><strong>Search Movies</strong>: Use the search bar at the top of the page to find movies by title. Results will update as you type.</li>
        </ul>

 <h2>Project Structure</h2>
        <div class="project-structure">
            <pre><code>movieApp/
├── public/
│   ├── index.html
├── src/
│   ├── App.css
│   ├── App.js
│   ├── index.js
│   ├── MovieCard.jsx
│   └── search.svg
├── gitignore
├── package-lock.json
├── package.json
└── README.md</code></pre>
        </div>

 <h2>Contributing</h2>
        <p>We welcome contributions! Please follow these steps:</p>
        <ol>
            <li>Fork the repository.</li>
            <li>Create a new branch (<code>git checkout -b feature/your-feature</code>).</li>
            <li>Commit your changes (<code>git commit -m 'Add your feature'</code>).</li>
            <li>Push to the branch (<code>git push origin feature/your-feature</code>).</li>
            <li>Open a pull request.</li>
        </ol>
 <img href="/Users/anujchaudhary/Desktop/movieapp/src/Screenshot 2024-05-17 at 4.00.31 PM.png">

 </body>
     
