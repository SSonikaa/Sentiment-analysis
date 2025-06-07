<h1>📊 YouTube Comment Sentiment Analyzer</h1>

<p>
  This Python-based web app performs <strong>sentiment analysis</strong> on YouTube video comments using natural language processing. 
  It classifies comments into <strong>Positive</strong>, <strong>Negative</strong>, or <strong>Neutral</strong> and visualizes the results in a bar chart.
</p>

<p>
  The project fetches comments using the YouTube Data API, processes them with sentiment analysis (using VaderSentiment), and renders a clean graph 
  in a Flask-powered web interface.
</p>

<h2>🧠 Features</h2>
<ul>
  <li>🔍 Fetches real YouTube video comments using API</li>
  <li>📊 Analyzes sentiment (Positive, Negative, Neutral)</li>
  <li>📈 Displays the result in a matplotlib bar chart</li>
  <li>💻 Web app built using Flask</li>
</ul>

<h2>📸 Snapshot</h2>
<p>
  ![_20250130_065558](https://github.com/user-attachments/assets/0edca664-a496-410c-b4ea-8ef993dec220)
  ![_20250130_065610](https://github.com/user-attachments/assets/aa6b2e1d-c765-4faa-ac39-b3079b82123a)
</p>

<h2>🔁 Steps to Replicate</h2>
<ol>
  <li>Create your API key for YouTube from: <a href="https://developers.google.com" target="_blank">https://developers.google.com</a></li>
  <li>Download and install Conda: <a href="https://docs.conda.io" target="_blank">https://docs.conda.io</a></li>
  <li>
    Create a virtual environment and install required packages:
    <pre><code>conda create -n yt-sentiment python=3.9
conda activate yt-sentiment
pip install flask google-api-python-client emoji vaderSentiment matplotlib</code></pre>
  </li>
  <li>
    Run the app:
    <pre><code>python app.py</code></pre>
  </li>
  <li>Open <code>http://127.0.0.1:5000</code> in your browser to use the application.</li>
</ol>

<h2>📂 Project Structure</h2>
<pre><code>youtube-sentiment-analyzer/
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── style.css (optional)
└── README.html
</code></pre>

<h2>🧪 Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>Flask</li>
  <li>Google API Client</li>
  <li>VaderSentiment</li>
  <li>Matplotlib</li>
  <li>HTML/CSS (Frontend)</li>
</ul>

<h2>🙌 Credits</h2>
<p>
  Built by <strong>Sonika</strong><br/>
  APIs powered by <strong>Google YouTube Data API</strong>
</p>

View the running project here : https://www.linkedin.com/posts/ssonikaa_datascience-python-flask-activity-7197236724547166208-SAlz?utm_source=share&utm_medium=member_desktop <br>






