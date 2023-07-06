# Naive Bayes 
- The aim of Machine Leanring is to generate models which can perform tasks like Regression & Classification.
- To achieve this Machine Leanring takes support of different mathematics branches for formulating various mathematical approaches to solve the above mentioned problems like Regression & Classification.

Examples:
- **Linear Regression**
    - The approach of linear regression is to construct a line which represents the trend of the data points in the n dimensional hyperspace using an algebraic equation and substitute values of an instance in the variables to get the prediction.
    - The concepts which are used to formulate this algorithm are Covariance, Correlation and algebraic equations.
- **Logistic Regression**
    - The apprach of logistic regression is to construct a sigmoid curve which represents the probabilities of every instance of belonging to a class and dividing the data points based on the probability predicted by this sigmoid curve comparing to the threshold of probability we set prior.
    - This algorithm is based on the concepts like Odds, Odds Ratio, log odds and threshold probability.

- Similarly there are other machine learning algorithms which are based on many concepts of probability theory for solving the mentioned problems.
- One of such concepts is called **Bayes Theorem**. Let's understand what is Bayes theorem and how we can use it to approach for a solution in Classification or Regression.

## Bayes Thoerem 
- Probability is a number which represents the likelihood of happening a particular event.
- This probability is more or less thoeritical in nature.
    - Example: Probability of a coin flipped getting heads is 0.5.
- What bayes thoerem helps us is to update this probability in the context of evidance.
    - Example: Probability of a person being male if that person owns a scooty.
    - Here the evidence of the event is owning a bike.
    - The event is the person being a male.
    - Now we know that probability of a person being male of female is 0.5
    - Bayes thoerem helps us to update the probability of being a male from 0.5 to a new probability by considering the new evidence that the person owns a scooty.
    - This is also called as **conditional probability**.

  ![Bayes Thoerem Formula](https://miro.medium.com/v2/resize:fit:457/0*Ih9B5Bh6RHPmOzSM.png)
  

