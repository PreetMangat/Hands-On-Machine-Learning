# Chapter 1 - Exercises

#### Question 1 - How would you define Machine Learning?

Machine learning is the use and development of computer systems, that can learn and adapt without being explicitly programmed to do so. These systems learn and adapt by using algorithms and statistical models to analyze and draw inferences from patterns in data.

#### Question 2 - Can you name four types of problems where it shines?

Machine learning shines when:

1. There are complex problems in which using a more traditional approach doesn't work. In cases like these, machine learning can help (though it's not guarenteed depending on the problem).

2. There is an environment where there is a fluctuation in data, or there is consistent, new data that is incoming into the system.

3. There is large amounts of data. In such cases, humans can use machine learning to gain insight into patterns, and solutions to complex problems in which large amounts of data can help.

4. There are problems that require a lot of fine tuning, or have a long list of rules

#### Question 3 - What is a labelled training set?

Data labeling is the process of identifying raw data, by adding meaningful and informative "tags" or "labels". These labels provide context to machine learning models so that they can learn from the data. This is generally done in supervised learning.

#### Question 4 - What are two common supervised tasks?

One common task for supervised learning is classification. Classification predicts the category that the data belongs to. The categories are known ahead of time. Examples of this include spam detection (categories would be spam, and not spam), sentiment analysis, dog breed detection, etc.

Another common task for supervised learning is regression. Regression predicts a numerical value based on previously observed data. An example of regression would be to predict the price of a car, given a set of features such as mileage, age, brand, etc.

#### Question 5 - What are 4 common unsupervised tasks?

One common task for unsupervised learning is clustering. Clustering involves finding similarities between data instances and grouping them together based on these similarities. It may sound similar to classification but the difference is that with classification, these similarities / categories are known ahead of time whereas with clustering, the machine learning algorithm must discover these similarities by itself.

Another common task for unsupervised learning is anomaly and novelty detection. Both of these tasks require the algorithm to be able to detect outliers in data, or find data instances that have some unusual feature compared to the other instances. However, they differ with how strict they are when it comes to detection. A good example provided by the textbook that explains the differences is as follows: Imagine you have thousands of dog pictures, and 1% of these pictures are of Chihuahuas. In novelty detection, the algorithm should not treat new pictures of Chihuahuas as novelties or outliers, whereas in anomaly detection these dogs might be so rare and different than other dogs that it would classify them as anomalies.

Another common task for unsupervised learning is Visualization and dimensionality reduction. Visualization algorithms take a lot of complex and unlabeled data, and can output 2d or 3d repersentations that can be plotted. Generally, visualization algorithms try and preserve as much structure from the data as possible so that humans can see and understand how the data is organized, in order to identify unsuspected patterns. Somewhat related, is deimensionality reduction. These algorithms try and simplify the data without losing too much information. A common way to do this is by merging several correlated features into one. For example, a car's mileage may be strongly correlated with its age, so a dimensionality reduction algorithm can merge them into one feature that repersents the car's wear and tear.

Lastly, one other common task for unsupervised learning is association rule learning. These algorithms analyze large amounts of data and discover relationships between attributes. This differs from clustering, as these relationships don't necessarily imply that the attributes should be grouped together into one category.

#### Question 6 - What type of Machine Learning algorithm would you use to allow a robot to walk in various unknown terrains?

A good machine learning algorithm to use in this case would be reinforcement learning, as the agent would be able to observe the environment and make decisions based on rewards (for example, staying upright and moving) and penalties (for example, falling, not moving because it got stuck, etc).

#### Question 7 - What type of algorithm would you use to segment your customers into multiple groups?

#### Question 8 - Would you frame the problem of spam detection as a supervised learning problem, or an unsupervised learning problem?

I would frame the problem of spam detection as a supervised learning problem. This is because the training data for a model in this domain would have to be labelled (spam, or not spam), as this is a classification problem.

#### Question 9 - What is an online learning system?

An online learning system is a method of machine learning in which the data is sequentially and incrementally fed into the machine learning algorithm, as soon as it arrives. The algorithm updates its parameters after learning from each individual training instance. 

This is opposed to batch (or offline) learning, where the entire dataset is fed into the algorithm at once.

An online learning system is a great option when the dataset is too large to fit entirely into memory (thus it pairs well with out-of-core learning), or when it's known that the model will need to deal with newly, varying, incoming data on a frequent basis.

#### Question 10 - What is out-of-core learning?

#### Question 11 - What type of learning algorithm relies on a similarity measure to make predictions?

#### Question 12 - What is the difference between a model parameter, and a learning algorithms hyperparameter?

#### Question 13 - What do model based algorithms search for? What is the most common strategy they use to succeed? How do they make predictions?

#### Question 14 - Can you name four of the main challenges in Machine Learning?

#### Question 15 - If your model performs great on training data, but generalizes poorly to new instances, what is happening? Can you name 3 possible solutions?

#### Question 16 - What is a test set, and why would you want to use it?

#### Question 17 - What is the train-dev set, when do you need it, and how do you use it?

#### Question 18 - What can go wrong if you tune hyperparameters using the test set?