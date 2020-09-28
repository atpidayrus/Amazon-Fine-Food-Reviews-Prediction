# Amazon-Fine-Food-Reviews-Prediction
Using Different ML approaches to predict the polarity of reviews using the review text<br><br>
<b>NOTE: This set of projects was done as part of the Applied Machine Learning Course by <a href=appliedaicourse.com>appliedaicourse.com</a>
 in 2019.</b>
<br>
Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews <br><br>
<ul>
<li>The 1st notebook implements Data Visualization using t-SNE algorithm on the reviews.</li>
<li>Notebooks 10 & 11 show various Clustering techniques and the SVD Dimensionality reduction technique on this dataset respectively.</li>
<li>Except these notebooks, all the others employ ML techniques for Classification & use the following basic approach:
  <ol>
    <li>Loading the data from an sqlite file.</li>
    <li>Setting target value of polarity to 1 for all reviews greater than 3 stars, and 0 for reviews less than 3 stars</li>
    <li> Exploratory Data Analysis </li>
    <li> Removal of duplicate records</li>
    <li> Review Text Preprocessing - Removal of HTML tags, special characters,  converting to lowercase, removal of stopwords & stemming the words.</li>
    <li> Applying Count Vectorization(Bag of Words), TF-IDF vectorization on review texts</li>
    <li> Cross validation & hyperparameter tuning on the Machine Learning model being used in the solution.</li>
    <li> Training the ML model using best hyperparameters found on the Train Set, and predicting on the Test Set.</li>
    <li> Applying Average Word2Vec and TFIDF weighted Word2Vec vectorizations on the review texts and repeating steps 7 & 8.</li>
    <li> Performance comparison of all approaches and hyperparameters used.</li>
  </ol>
</ul>

