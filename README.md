# Book Recommender System
This python notebook shows how to build and testing a recommender system using the two types of collaborative filtering: User-Based Collaborative Filtering (UB-CF) and Item-Based Collaborative Filtering (IB-CF). Some techniques perform data exploration and cleansing on the Book-Crossing dataset that was collected by Cai-Nicolas Ziegler in a 4-week crawl (during the August/September 2004 period) from the [Book-Crossing](http://www2.informatik.uni-freiburg.de/~cziegler/BX/) community. It contains 1.1 million ratings of 270,000 books by 90,000 users. The ratings are on a scale from 1 to 10. The data consists of three tables: ratings, books information and users information.

# Methodology:
The model implements a simple recommendation system based on collaborative filtering machine learning algorithm. But before that it is vital to understand what the data is, and what is being achieved. Data exploration reveals the hidden trends and insights and data preprocessing makes the data ready for use by ML algorithms.

# Technologies:
Everything from data loading to training is done using Python and its libraries. The numeric computation is performed by numeric library of Python called NumPy. Other libraries used for utilities functions are pandas and sklearn.

# Approaches:
(1) User-based (using Cosine Similarity)<br/>
(2) User-based (using Correlation Similarity)<br/>
(3) Item-based (using Cosine Similarity)<br/>
(4) Item-based (using Correlation Similarity)<br/>
