<h1>Movie-recommendation-system</h1>
This repository contains the code for building movie recommendation engine. This movie recommendation system is built using Python as the backend and Jupyter Notebook for development, with Streamlit as the frontend. The system leverages a powerful machine learning algorithm to provide personalized movie recommendations to users based on their preferences and previous interactions. By analyzing user data such as movie ratings, genre preferences, and viewing history, the algorithm intelligently learns patterns and makes accurate predictions about movies that a user is likely to enjoy. It takes into account various factors such as movie genres, directors, actors, and user ratings to generate tailored recommendations that align with individual tastes. The system provides an intuitive and user-friendly interface through Streamlit, allowing users to easily interact with the application. Users can input their preferences, browse through a vast movie database, and receive instant recommendations based on their input.
<h2>Features</h2>
<ul>
    <li>Personalized movie recommendations based on user preferences</li>
    <li>User-friendly interface with Streamlit for easy interaction</li>
    <li>Integration with a rich movie database to provide a wide range of movie suggestions</li>
    <li>Continuously learning algorithm that adapts to user feedback</li>
</ul>
<h2>Installation</h2>
1. Clone or download this repository to your local machine.<br>
2. Install all the libraries mentioned in the requirements.txt file with the command <code>pip install -r requirements.txt</code>
<h2>Usage</h2>
1. Navigate to the project directory: <code>cd movie_recommendation_system</code> <br>
2. Launch the Streamlit application: 
	 <code>streamlit run app.py</code><br>
3. Access the application through <a href="http://localhost:8501" target="_blank">http://localhost:8501</a>.
<h2>Details about Dataset</h2>
All the information related to dataset is described in this section.
<ul>
  <li>We have used TMDB 5000 Movie Dataset in order to build movie recommendation engine.</li>
  <li>You can download the dataset from <a href="https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv" target="_blank">here</a></li>
</ul>
<h2>Dependencies</h2>
<ul>
    <li>Python >=3.5</li>
    <li>pandas</li>
    <li>numpy</li>
    <li>scipy</li>
    <li>scikit-learn</li>
    <li>scikit-surprise</li>
    <li>lightfm</li>
    <li>matplotlib</li>
    <li>seaborn</li>
    <li>jupyter notebook</li>
    <li>jupyter lab</li>
    <li>textblob</li>
</ul>
<h2>Data Privacy and Security</h2>
<ul>
	<li>User data protection: This system ensures the privacy and security of user data. All user information and interactions are anonymized and handled securely.</li>
	<li>Data storage and retention: The system stores user data for the sole purpose of improving recommendations. Data retention is kept to a minimum and follows best practices in compliance with privacy regulations.</li>
</ul>
<h2>Contributions</h2>
Contributions are welcome! We value your input and encourage you to actively participate in the project. If you have any ideas, suggestions, bug reports, or feature requests, please don't hesitate to open an issue on GitHub. Additionally, we appreciate any code contributions you may have. If you'd like to contribute code, please submit a pull request, and we will review it as soon as possible. Thank you for your support!
