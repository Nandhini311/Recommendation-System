# Recommendation-System

can be done in two ways:

**User-based collaborative filtering:**

   Build a matrix of things each user bought/viewed/rated
   compute similarity scores between users
   Find users similar to you
   Recommend stuff they bought/viewed/rated that you haven't yet
   
**Limitations:**

   Sparsity : there are more number of people than the number of items
   Scalability: computation increases with increase in number of people.
   interest of people can keep changing.

**Item-based collaborative filtering:**

   Recommendations are based on relationship between things instead of people
   there are usually fewer things than people and hence less computation
   things or facts about them don't change
   Harder to game the system ( we can't create fake item unlike humans)
   
**How does item-based Collaborative filtering works:**
(movie recommendation)

 1. find every pair of movies that are watched by the same person
 2. measure the similarity of their ratings across all users who watched both
 3. sort by movie, then by similarity strength
