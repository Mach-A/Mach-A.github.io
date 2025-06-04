
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

  <h1>...focused on augumenting human capabilities</h1>

  <details open>
    <summary>Home</summary>
    <p>Welcome to my personal projects. These are bunch of stuff worked on and things being worked on.</p>
  </details>

  <details>
    <summary>About Me</summary>
    <p>Hi, I'm Alison, and these are my github projects, my studies concentration are on Machine Learning, Reinforcement Learning, Deep Learning, NLP, computer vision tasks, data analysis and cloud computing.</p>
  </details>

  <details>
    <summary>Projects</summary>
    <ul>
      <li><strong>2024 NYC Yellow Taxi Database</strong>: A data analytics and ML models case studies addressing insights on the database. <a href="https://github.com/Mach-A/NYC_taxi_dataset_2024dataset">GitHub</a></li>
      <img src="asset/ride.png" alt="Zones/ride table" style="max-width: 100%; height: auto;">    
      <li><strong>Movie Genre Classifier</strong>: An LSTM-based model and a BERT-model to classify genres from movie synopses, trained on 14,000 movies. Achieved an accuracy of 72% <a href="https://github.com/yourusername/movie-genre-classifier">GitHub</a></li>
      <li><strong>Implementing regression models using the classicial MNIST dataset</strong>: The regression models, binary logistic regression and multi-logistic regression models were implemented using no inbuilt functions/external libraries <a href="https://github.com/Mach-A/mlr_blr_svm_using_mnist_dataset">GitHub</a></li>
    </ul>
  </details>

<details>
    <summary>Next challenges</summary>
    <p>Currently working and also in team collaboration within a couple of research AI fields in preventive healthcare, consumer tech, some bits of mobility and advanced transportation systems like traffic count and classification, amongst others.</p>
  </details>

  <details>
    <summary>Howdy</summary>
    <p>gcolally@gmail.com</p>
  </details>
  
</body>
</html>




  



