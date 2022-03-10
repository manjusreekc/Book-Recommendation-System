# Book-Recommendation-System
## Aim:
Given the book crossing dataset, to build Recommendation Systems for recommending books to the users.
## Book Recommendation System
Recommendation systems are widely used to recommend products to the end users that are most appropriate. It helps in the increased sales and efficiency of websites. With the development of electronic commerce, the number of online book-selling websites has increased. For such a website Recommendation system is one of the strongest tools to increase the profit. The book recommendation system must recommend books that are of buyer’s interest.
## Steps Involved
### 1. Data pre-processing 
We are given three datasets-Users,Books and Ratings. These three datasets are cleaned and pre-processed separately by removing unwanted columns, extracting required information, null value treatement and duplicate removal. Then the three pre-processed datasets are merged using inner join to obtain the final dataset. Since we consider only explicit ratings for this project, we removed 0 ratings.
### 2. Exploratory Data Analysis
To find the patterns in data,we performed EDA and came up with findings like
* Most Rated Books
* Top Book Authors
* Top Book Publishers
* City, State and Country from which the highest number of ratings was recorded
* Age Distribution
* Most Rated Books by Teenage,Youth,Middle Age, elderly
### 3. Building Recommendation Systems
We built 5 types of recommendation systems in this project. They are\
* Popularity-Based Recommendation System
* Simple Recommendation System
* Author-Based Recommendation System
* Collaborative Recommendation - k-Nearest Neighbors
* Collaborative Recommendation- Singular Value Decomposition
### 4. Evaluation
We evaluated Collaborative Filtering Based Recommendation-SVD and got a recall@5 of 30% and recall@10 of 41%. 


              
