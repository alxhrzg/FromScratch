# FromScratch
A collection of Machine Learning Algorithms from scratch, the collections so far include: 
1. K-Means Clustering 
2. Gaussian Mixture Models (GMM)
    * Lots of the logic could be vectorized, but I wanted to do every calculation to really understand each step in depth to really get a good grip on Expectation Maximisation
3. Principal Component Analysis (PCA)
    * Here I wanted to give an illustrative example of how the transformation re-aligns the axis of components with the highest variance with the original coordinate system
    * The whole topic is a bit abstract, but understanding what the steps involved are doing rather than how the underlying calculations are done leads to a good path to formulate some intition.
4. Linear Regression with Polynomial Terms: 
    * *Fitting a line to the points of a high-degree polynomial + noise*
    * Other transformations other than the polynomial one are not included 
5. Logistic Regression: 
    * The implemented loss function is from this [link](https://www.youtube.com/watch?v=KIhPtHOfbhQ&t=533s)
    * It works, but there is a little bug, I am predicting 0's where there should be ones and vice-versa. I fixed it by inverting the term in the *predict* method

All Algorithms are implemented while following the lectures in my machine learning course (CSCM45) at Swansea University. The implementation is not mandatory in the scope of my course but motivated by my own desire to thouroughly understand them. 
