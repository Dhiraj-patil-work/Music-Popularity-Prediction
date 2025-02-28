<h1>🎵 Music Popularity Prediction</h1>
    
<h2>📌 Overview</h2>
  <p>Music popularity prediction involves developing machine learning models to estimate the popularity of music tracks based on their audio features. Predicting the popularity of music can help streaming platforms understand user preferences, optimize playlists, and enhance recommendation systems.</p>
    
<h2>📊 Dataset</h2>
  <p>The dataset consists of 227 music tracks with various features such as:</p>
  <ul>
      <li>Track Name</li>
      <li>Artists</li>
      <li>Album Name</li>
      <li>Popularity Score</li>
      <li>Musical Features (Danceability, Energy, Loudness, etc.)</li>
      <li>Metadata (Release Date, Duration, Explicit Content, etc.)</li>
  </ul>
    
<h2>📌 Exploratory Data Analysis (EDA)</h2>
  <p>Key insights from EDA:</p>
  <ul>
      <li>Higher energy and danceability correlate positively with popularity.</li>
      <li>Acousticness and lower loudness correspond to lower popularity.</li>
      <li>Correlation analysis shows that loudness and danceability have a moderate positive correlation with popularity.</li>
  </ul>
    
<h2>📌 Features Used for Prediction</h2>
  <ul>
      <li>Energy</li>
      <li>Valence</li>
      <li>Danceability</li>
      <li>Loudness</li>
      <li>Acousticness</li>
      <li>Tempo</li>
      <li>Speechiness</li>
      <li>Liveness</li>
  </ul>
    
<h2>🖥️ Model Training</h2>
  <p>The dataset was split into training and testing sets. Features were normalized, and a <b>Random Forest Regression</b> model was trained with hyperparameter tuning using GridSearchCV.</p>
    
<h2>📈 Model Performance</h2>
  <p>The model performed well in predicting the popularity of songs. A scatter plot comparing actual vs. predicted popularity showed good alignment with some deviations at lower popularity values.</p>
    
<h2>🛠️ Technologies Used</h2>
  <ul>
      <li>Python</li>
      <li>Pandas & NumPy</li>
      <li>Matplotlib & Seaborn (Visualization)</li>
      <li>Scikit-Learn (Machine Learning)</li>
  </ul>
    
<h2>📌 How to Run the Project</h2>
  <ol>
      <li>Clone the repository: <code>git clone &lt;repository-url&gt;</code></li>
      <li>Install dependencies: <code>pip install -r requirements.txt</code></li>
      <li>Run the Jupyter Notebook or Python script.</li>
  </ol>
    
<h2>📌 Conclusion</h2>
  <p>Music popularity prediction helps streaming platforms, artists, and producers make data-driven decisions. The Random Forest model provided meaningful predictions, highlighting key factors influencing a song’s popularity.</p>
    
<h2>📩 Contact</h2>
  <p>For any queries or contributions, feel free to reach out!</p>

