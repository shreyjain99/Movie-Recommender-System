<h2 align= "center"><em>Movie Recommender System</em></h2>

<div align="center">
  <img height="400" src="https://github.com/shreyjain99/Movie-Recommender-System/blob/main/src%20files/cover%20image.png"/>
</div>

<hr width="100%" size="2">

<h3 align= "left"> <b> Key Project Formulation </b> </h3>

<br>

<p>
<strong>Real World/Business Objective :</strong>To Predict the rating that a user would give to a movie that the user has not yet rated and minimize the difference between predicted and actual rating (RMSE and MAPE).
</p>

<br>

<p>
<strong>Constraints :</strong>
</p>
<ol>
<li>Interpretability (why was it recommended)</li>
</ol>

<br>

<p>
<strong>Get the data from :</strong> https://www.kaggle.com/netflix-inc/netflix-prize-data/data
<br> Dataset from Netflix's competition to improve their reccommendation algorithm (Netflix prize data competitiion)
</p>

<br>

<p>
<strong>Data Overview :</strong>
<br>
<p> Data files : 
<ul> 
<li> combined_data_1.txt </li>
<li> combined_data_2.txt </li>
<li> combined_data_3.txt </li>
<li> combined_data_4.txt </li>
<li> movie_titles.csv </li>
</ul>
</p>
<br>
<p>
    Data file's information:
</p>
<p>  

The first line of each file [combined_data_1.txt, combined_data_2.txt, combined_data_3.txt, combined_data_4.txt] contains the movie id followed by a colon. Each subsequent line in the file corresponds to a rating from a customer and its date in the following format:

CustomerID,Rating,Date

MovieIDs range from 1 to 17770 sequentially.
CustomerIDs range from 1 to 2649429, with gaps. There are 480189 users.
Ratings are on a five star (integral) scale from 1 to 5.
Dates have the format YYYY-MM-DD.
</p>

<br>

<br />


<p>
<strong>ML Problem Formulation :</strong>
</p>
<p> <strong>For a given movie and user we need to predict the rating would be given by him/her to the movie. 
The given problem is a Recommendation problem 
It can also seen as a Regression problem </strong> </p>
<br>
<p>Objective is to Minimize RMSE and Try to provide some interpretability.</p>

<br>
<br>

<p>
<strong>Performance metrics :</strong>
</p>
<ol>
<li>Mean Absolute Percentage Error (MAPE)</li>
<li>Root Mean Square Error (RMSE)</li>
</ol>

<hr width="100%" size="2">

<br>

<body>

  <h3>Flow of Project : </h3>
  
  <br>

  <h3 align= "center"><strong>Data Preprocessing</strong></h3>
  
  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center"><strong>Temporal Train-Test split </strong></h3>

  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">Preliminary data analysis</h3>
  
  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>
  

  <h3 align= "center">Sparse matrix representation</h3>
  

  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">Cold start problem</h3>

  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">User-User similarity matrix</h3>
  
  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>  
  
  <h3 align= "center">Movie-Movie similarity matrix</h3>

  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">Machine learning models</h3>


  
</body>

<hr width="100%" size="2">


<br>

<p>
<strong>Future Scope :</strong>
</p>
<ol>
<li>Instead of using 10K users and 1K movies to train the above models, use 25K users and 3K movies (or more) to train all of the above models.</li>
<li>Tune hyperparamters of all the Xgboost models above to improve the RMSE.</li>
</ol>

<hr width="100%" size="2">
<br>

<p>
<strong>Skills and Software Tools Used in the Project :</strong>
</p>
<ul>
    <li>Data Preprocessing</li>
    <li>Temporal Analysis</li>
    <li>Exploratory Data Analysis (EDA)</li>
    <li>Sparse Matrix Representation</li>
    <li>Cold Start Problem Solutions</li>
    <li>User-User Similarity Matrix</li>
    <li>Movie-Movie Similarity Matrix</li>
    <li>Machine Learning Models</li>
    <li>Regression</li>
    <li>Python</li>
    <li>Pandas</li>
    <li>NumPy</li>
    <li>XGBoost</li>
</ul>

<hr width="100%" size="2">
