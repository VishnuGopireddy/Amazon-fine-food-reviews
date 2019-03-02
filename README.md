# Amazon-fine-food-reviews

<h3>Dataset: </h3>
<ul> 

<li> Number of reviews: 568,454 </li>
<li> Number of users: 256,059 </li>
<li> Number of products: 74,258 </li>
<li>Number of products: 74,258 </li>
<li>Timespan: Oct 1999 - Oct 2012 </li>
<li>Number of Attributes/Columns in data: 10</li>
<hr>
</ul>
<h3> 1. Exploratory data analysis on Amazon fine food reviews dataset.</h3>
<p>&nbsp &nbsp &nbsp &nbsp Perform exploratory data analysis on whole data with seaborn, wordcloud.</p>
<hr>

### Generated Wordcloud on reviews
<p> <img src="wordlcloud.png", width=500,height=500> </p>

<h3> 2. Perform text sentimental analysis on Amazon fine food reviews</h3>
<ul>
<li>There are large number of reviews in the dataset working with such large reviews can run out of memory and system crashes. So we take a sample of 1,00,000 reviews.</li>
<li>Considering only reviews column for text analysis.</li>
</ul>
<h3>Featurization</h3>
<ul>
<li> Bag Of Words </li>
<li> tfidf vectorization </li>
</ul>


<h3>Machine Learning Model</h3>
<ul> 
<li> Naive bayes Model </li>
<li> Logistic Regression </li>
</ul>

<h3>Preformance of model with F1 score</h3>
<ul>  Naive bayes Model 
<li> Bag Of Words => 90.94 </li>
<li> Tfidf => 90.61
</ul>
<ul>  Logistic Regression 
<li> Bag Of Words => 93.41 </li>
<li> Tfidf => 91.90
</ul>
