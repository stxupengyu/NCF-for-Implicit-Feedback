# NCF-for-Implicit-Feedback  
Neural collaborative filtering (NCF) method is used to verify the experimental results on Microsoft MIND news dataset.  
Our approach:  
- construct a rating dataset from the original raw MIND dataset. Each row of the rating dataset: [User ID, Item ID, Rating Score] .
- negative sampling.
- we treat the positive feedback as 5, and the negative feedback as 3.
- NCF implement by keras.
