
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

  <h3>...eager to always collaborate within the different exciting fields of AI</h3>

  <details open>
    <summary>Home</summary>
    <p>Welcome to my personal projects. These are bunch of some stuff worked on and things being worked on, tons of stuff yet to be done tho</p>
  </details>

  <details>
    <summary>About Me</summary>
    <p>Hi, I'm Alison, and these are my github projects, my concentration are in Machine Learning, Reinforcement Learning, Deep Learning, NLP, Computer vision tasks, Data analysis and Cloud computing.</p>
  </details>

  <details>
    <summary>Projects</summary>
    <ul>
      <li><strong>2024 NYC Yellow Taxi Database</strong>: A data analysis and ML models case study addressing insights from the database. Over 20 Million NYC rides were used within Jan-June 2024. Based off the three different ML models, easily I can predict NYC total tax for Yellow taxi, I can predict if a driver will receive a tip or not and a passenger payment type.  <a href="https://github.com/Mach-A/NYC_taxi_dataset_2024dataset">GitHub</a></li>
      <img src="asset/ride.png" alt="Zones/ride table" style="max-width: 100%; height: auto;">    
      <li><strong>Movie Genre Classifier</strong>: An LSTM-based model and a BERT-model to classify genres from movie synopses, trained on 14,000 movies. While improved LSTM Model(embedded with GloVe words) achieved over 72% acc(this is averagely a low accuracy metric), BERT Model(pretrained) achieved an accuracy of 93% <a href="https://github.com/yourusername/movie-genre-classifier">GitHub</a></li>
      <img src="asset/imp_lstm.png" alt="Improved LSTM Accuracy" style="max-width: 100%; height: auto;"> 
      <img src="asset/bert_model.png" alt="Bert Model with F1 score and Accuracy" style="max-width: 100%; height: auto;"> 
      <img src="asset/bert_f1_acc.png" alt="Bert Model with only F1 score<<macro/micro" style="max-width: 100%; height: auto;"> 
      <li><strong>Implementing regression models using the classicial MNIST dataset</strong>: The regression models, binary logistic regression and multi-logistic regression models were implemented using no inbuilt functions/external libraries <a href="https://github.com/Mach-A/mlr_blr_svm_using_mnist_dataset">GitHub</a></li>
      <img src="asset/rbf_vary_gamma.png" alt="Radial Basis Function with varying Gamme value on the MNIST dataset" style="max-width: 100%; height: auto;"> 
    </ul>
  </details>

<details>
    <summary>Next challenges</summary>
    <p>Currently working and also in team collaboration within a couple of research AI fields in preventive healthcare, consumer tech, some bits of mobility and advanced transportation systems like traffic count and vehicle type classification, interesting stuff basically.</p>
  </details>

  <details>
    <summary>Howdy</summary>
    <p>gcolally@gmail.com</p>
  </details>

Kindly follow Me
[Follow me on GitHub](https://github.com/Mach-A)
    
