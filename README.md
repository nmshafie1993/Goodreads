# The Goodreads Data Visualization Project (Pandas, Matplotlib, Seaborn)
As a bookie, I always enjoyed Goodreads website. I got this dataset is from <a href="https://www.kaggle.com/jealousleopard/goodreadsbooks"> kaggle </a> and tried to practice my data cleaning and data visulization skills. 

## Columns Description:
<ul>
<li>bookID: Unique ID of the books<li>
<li>title: Titles of the books<li>
<li>authors: Authors of the books<li>
<li>average_rating: The average rating of the books, as decided by the users<li>
<li>isbn: Specific information about the books - such as edition and publisher<li>
<li>isbn13: The new format for ISBN, implemented in 2007. 13 digits<li>
<li>language_code: Language of the books<li>
<li>num_pages: Number of pages for the books<li>
<li>ratings_count: Number of ratings given for the books<li>
<li>text_reviews_count: The count of reviews left by users<li>
<li>publication_date: Date of the publication of the books<li>
<li>publisher: Name of the publisher of the books<li>
</ul>


## Data Cleaning
<ol>
<li> I dropped the isbn and isbn13 columns.</li>
<li> The authors columns has been modified.</li>
<li> The duplicated rows of the same books removed.</li>
  
</ol>

## Exploratory Data Analysis
Most rated books:
![alt text](https://github.com/nmshafie1993/Goodreads/blob/master/Most%20rated%20books.png)<br>

Longest books
![alt text](https://github.com/nmshafie1993/Goodreads/blob/master/most%20lonest%20book.png)<br>

Rating distribution
![alt text](https://github.com/nmshafie1993/Goodreads/blob/master/download.png)<br>

Correlation Analysis
![alt text](https://github.com/nmshafie1993/Goodreads/blob/master/corr.png)<br>
