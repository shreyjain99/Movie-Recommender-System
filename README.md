<h2 align= "center"><em>Movie Recommender System</em></h2>

<div align="center">
  <img height="400" src="https://github.com/shreyjain99/Movie-Recommender-System/blob/main/src%20files/cover%20image.png"/>
</div>

<hr width="100%" size="2">

<h3 align= "left"> <b> Key Project Formulation </b> </h3>

<br>

<p>
<strong>Real World/Business Objective :</strong>To Predict the rating that a user would give to a movie that he ahs not yet rated and minimize the difference between predicted and actual rating (RMSE and MAPE).
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
<p> <strong>There are nine different classes a genetic mutation can be classified into => Multi class classification problem</strong> </p>
<br>
<p>Objective is to Predict the probability of each data-point belonging to each of the nine classes.</p>

<br>
<br>

<p>
<strong>Performance metrics :</strong>
</p>
<ol>
<li>Multi class log-loss</li>
<li>Confusion Matrix</li>
</ol>

<hr width="100%" size="2">

<br>

<body>

  <h3>Flow of Project : </h3>
  
  <br>

  <h3 align= "center"><strong>Exploratory Data Analysis</strong></h3>
  <p align= "center"><em> - Basic text preprocessing like removal of stopwords, removing extra spaces, lower casing text etc. </em></p>
  <p align= "center"><em> - test, train and cross validation split </em></p>
  <p align= "center"><em> - Univariate analysis </em></p>
  
  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center"><strong>Prediction using Random Model </strong></h3>

  <div align= "center">|</div>
  <div align= "center">|</div>
  <div align= "center">\/</div>

  <h3 align= "center">Building Machine Learning Models</h3>
  <p align= "center"><em> - Baseline model is naive bayes hyperparameter tuned model  </em></p>
  <p align= "center"><em> - K Nearest Neighbhor with hyperparameter tuning   </em></p>
  <p align= "center"><em> - Logistic regression with and without class balancing and hyperparameter tuning  </em></p>
  <p align= "center"><em> - Linear support vector machine with hyperparameter tuning </em></p> 
  <p align= "center"><em> - Random forest classifier with hyperparameter tuning </em></p>  
  <p align= "center"><em> - Linear support vector machine with hyperparameter tuning and one hot encoding as well as response coding </em></p>  
  <p align= "center"><em> - Stacking classifier </em></p>  
  <p align= "center"><em> - Maximum voting classifier </em></p>  
  <p align= "center"><em> - Feature importance from all above models </em></p>  



  
</body>

<hr width="100%" size="2">
<br>

<div align="center">
  <img height="200" src="https://github.com/shreyjain99/Personalized-Cancer-Diagnosis/blob/main/src%20files/cancer-diagnostics-market.jpg"/>
</div>

<br>

<p>
<strong>Future Scope :</strong>
</p>
<ol>
<li>Apply All the models with tf-idf features (Replace CountVectorizer with tfidfVectorizer and run the same cells) </li>
<li>Instead of using all the words in the dataset, use only the top 1000 words based of tf-idf values</li>
<li>Apply Logistic regression with CountVectorizer Features, including both unigrams and bigrams </li>
<li>Try any of the feature engineering techniques discussed in the course to reduce the CV and test log-loss to a value less than 1.0</li>
</ol>

<hr width="100%" size="2">
