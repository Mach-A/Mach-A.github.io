<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Your Name - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 40px auto;
      padding: 0 20px;
      line-height: 1.6;
      background-color: #fdfdfd;
    }

    h1 {
      text-align: center;
      font-size: 2.5rem;
    }

    details {
      margin: 1rem 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 0.8rem;
      background-color: #f9f9f9;
    }

    summary {
      font-weight: bold;
      font-size: 1.25rem;
      cursor: pointer;
    }

    summary::-webkit-details-marker {
      display: none;
    }

    details[open] summary::after {
      content: "▲";
      float: right;
    }

    summary::after {
      content: "▼";
      float: right;
    }

    a {
      color: #0366d6;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <h1>Your Name</h1>

  <details open>
    <summary>🏠 Home</summary>
    <p>Welcome to my personal project portfolio. Here you'll find what I'm working on, who I am, and links to everything I've built.</p>
  </details>

  <details>
    <summary>🙋‍♂️ About Me</summary>
    <p>I’m a developer passionate about machine learning, data science, and building creative software solutions.</p>
    <p>When I’m not coding, I enjoy reading, working on open source, and exploring new technologies.</p>
  </details>

  <details>
    <summary>🛠️ Projects</summary>
    <ul>
      <li><strong>Movie Genre Classifier</strong>: An LSTM-based model that classifies genres from movie synopses. <a href="https://github.com/yourusername/movie-genre-classifier">GitHub</a></li>
      <li><strong>PageRank with PySpark</strong>: Custom PageRank implementation for graph data. <a href="https://github.com/yourusername/spark-pagerank">GitHub</a></li>
      <li><strong>Portfolio Website</strong>: This site, built with HTML and GitHub Pages. <a href="https://github.com/yourusername/yourusername.github.io">GitHub</a></li>
    </ul>
  </details>

</body>
</html>




  



