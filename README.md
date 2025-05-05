<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Taxi Fare Prediction - README</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; }
    h1, h2 { color: #2c3e50; }
    pre { background: #f4f4f4; padding: 10px; border-radius: 5px; overflow-x: auto; }
  </style>
</head>
<body>
  <h1>🚖 Taxi Fare Prediction Project</h1>
  
  <h2>📌 Overview</h2>
  <p>This project builds a machine learning model using <strong>Random Forest Regression</strong> to predict taxi fares based on historical data. It uses datetime, coordinates, and other features to estimate fare amounts.</p>

  <h2>📁 Files</h2>
  <ul>
    <li><code>fare_taxi_train.csv</code> – Training dataset</li>
    <li><code>fare_taxi_test.csv</code> – Testing dataset</li>
    <li><code>Notebook.ipynb</code> – Main Jupyter notebook with preprocessing and model training</li>
  </ul>

  <h2>⚙️ Requirements</h2>
  <pre><code>pandas
scikit-learn
numpy
jupyter</code></pre>

  <h2>🚀 How to Run</h2>
  <ol>
    <li>Install dependencies: <code>pip install -r requirements.txt</code> or manually install listed packages.</li>
    <li>Launch Jupyter Notebook: <code>jupyter notebook</code></li>
    <li>Open <code>Notebook.ipynb</code> and run all cells.</li>
  </ol>

  <h2>🧠 Model</h2>
  <ul>
    <li>Algorithm: <strong>RandomForestRegressor</strong></li>
    <li>Features used: <code>pickup_datetime (converted)</code>, <code>pickup/dropoff coordinates</code></li>
    <li>Missing data handled using: <code>SimpleImputer</code></li>
  </ul>

  <h2>📈 Output</h2>
  <p>The model predicts fare amounts and prints the result for the test set. Example output:</p>
  <pre><code>Predicted fare amount: [9.28]</code></pre>

  <h2>✍️ Author</h2>
  <p>Chirag Bajaj – AI Enthusiast | B.Tech CSE (AI)</p>
</body>
</html>
