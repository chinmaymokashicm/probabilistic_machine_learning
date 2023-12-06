# Probabilistic Machine Learning
Code implementation following the chapter structure of "Machine Learning: A Probablistic Perspective" by Kevin Murphy

# Chapters:
1. Introduction
    1. Machine learning: what and why?
        1. Types of machine learning
    2. Supervised learning
        1. Classification
        2. Regression
    3. Unsupervised learning
        1. Discovering clusters
        2. Discovering latent factors
        3. Discovering graph structure
        4. Matrix completion
    4. Some basic concepts in machine learning
        1. Parametric vs non-parametric models
        2. A simple non-parametric classifier: K-nearest neighbors
        3. The curse of dimensionality
        4. Parametric models for classifications and regression
        5. Linear regression
        6. Logistic regression
        7. Overfitting
        8. Model selection
        9. No free lunch theorem
2. Probability
    1. Introduction
    2. A brief overview of probability theory
        1. Discrete random variables
        2. Fundamental rules
        3. Bayes' rule
        4. Independence and conditional independence
        5. Continuous random variables
        6. Quantiles
        7. Mean and variance
    3. Some common discrete distributions
        1. The binomial and Bernoulli distributions
        2. The multinomial and multinoulli distributions
        3. The Poisson distribution
        4. The empirical distribution
    4. Some common continuous distribution
        1. Gaussian (normal) distribution
        2. Degenerate pdf
        3. The Student's t distribution
        4. The Laplace distribution
        5. The gamma distribution
        6. The beta distribution
        7. Pareto distribution
    5. Joint probability distributions
        1. Covariance and correlation
        2. The multivariate Gaussian
        3. Multivariate Student t distribution
        4. Dirichlet distribution
    6. Transformations of random variables
        1. Linear transformations
        2. General transformations
        3. Central limit theorem
    7. Monte Carlo approximation
        1. Example: change of variables, the MC way
        2. Example: estimating &pi; by Monte Carlo integration
        3. Accuracy of Monte Carlo approximation
    8. Information theory
        1. Entropy
        2. KL divergence
        3. Mutual information
3. Generative models for discrete data
    1. Introduction
    2. Bayesian concept learning
        1. Likelihood
        2. Prior
        3. Posterior
        4. Posterior predictive distribution
        5. A more complex prior
    3. The beta-binomial model
        1. Likelihood
        2. Prior
        3. Posterior
        4. Posterior predictive distribution
    4. The Dirichlet-multinomial model
        1. Likelihood
        2. Prior
        3. Posterior
        4. Posterior predictive
    5. Naive Bayes classifiers
        1. Model fitting
        2. Using the model for prediction
        3. The log-sum-exp trick
        4. Feature selection using mutual information
        5. Classifying documents using bag of words