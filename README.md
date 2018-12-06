# Book Recommendation System

### Methodology

Before building any machine learning model, it is vital to understand what the data is, and what are we trying to achieve. Data exploration reveals the hidden trends and insights and data preprocessing makes the data ready for use by ML algorithms.

Then, we made a simple popularity based recommendation system can be built based on count of user ratings for different books. In order, to cope up with computing power machine has and to reduce the dataset size, so considering users who have rated at least 100 books and books which have at least 100 ratings. 
Then building CF-based recommendation systems to generate user-item ratings matrix from the ratings table. Then function recommendItem recommends books for user-based or item-based approach (based on selected approach and metric combination). Recommendations are made if the predicted rating for a book is greater than or equal to 6, and the books have not been rated already. Similarity metric like Cosine and Correlation are used.

### Approaches

*(1) Item-based (using Correlation Similarity)*<br>
*(2) Item-based (using Cosine Similarity)*<br>
*(3) User-based (using Correlation Similarity)*<br>
*(4) User-based (using Cosine Similarity)*