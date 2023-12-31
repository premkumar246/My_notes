<h1><b>Classification using Machine Leanring</b></h1>

- This is a detailed notes to learn how to perform classification task and what all you need to learn for training a model and successfully tune it.
- We will start the discussion by providing a perpespective on Artificial Intelligence which is the top level body of knowledge everythingis a part of and gradually dive deep in to the classification task.
- In this notes you will learn



[**1. What is Artificial Intelligence?**](#what-is-artificial-intelligence?)<br>
**2. What is Machine Learning?**<br>
**3. Why do we need machine leanring?**<br>
**4. What is Supervised Leanring?**<br>
**5. What is Classification?**<br>
**6. List of Algorithms for Classification?**<br>
**7. Map to understand algorithms** <br>




## What is Artificial Intelligence?

- Artificial Intelligence is a field of computer science which aims to create intelligent computers which can think and act like humans which means which can think and act rationally. -- This helps us to develop systems which help us to solve complex problems and take effective decisions in complex situations. 
- We can achieve AI by training algorithms using huge amounts of data where an algorithm learns from the data and achieves experience to perform various tasks like regression and classification.
- There are three levels of AI 

**Artificial Narrow Intelligence (ANI)**
- Artificial Narrow Intelligence which is also called as weak AI which deals with building intelligent systems which can perform specific tasks. 
Ex: Apple siri, Chat GPT, IBM Watson, etc. 

**Artificial General Intelligence (AGI)**
- Artificial General Intelligence which is called Strong AI deals with systems which have human-like intelligence capability, ability to understand, reason & solve complex problems. 
Ex: robots with human-like abilities. 

**Artificial Super Intelligence (AGI)**
- Artificial Super Intelligence is also called as superintelligence which would surpass the intelligence of human beings which do not have any practical application for today. 

- Application of AI are Speech Recognition, Customer Service, Computer Vision, Recommendation engine, automated Stock Trading etc.  

- Artificial intelligence can be organized in several ways, depending on stages of development or actions being performed. 
For instance, four stages of AI development are commonly recognized.

	- **Reactive machines:** Limited AI that only reacts to different kinds of stimuli based on preprogrammed rules. Does not use memory and thus cannot learn with new data. IBM’s Deep Blue that beat chess champion Garry Kasparov in 1997 was an example of a reactive machine.

	- **Limited memory:** Most modern AI is considered to be limited memory. It can use memory to improve over time by being trained with new data, typically through an artificial neural network or other training model. Deep learning, a subset of machine learning, is considered limited memory artificial intelligence.

	- **Theory of mind:** Theory of mind AI does not currently exist, but research is ongoing into its possibilities. It describes AI that can emulate the human mind and has decision-making capabilities equal to that of a human, including recognizing and remembering emotions and reacting in social situations as a human would. 

	- **Self aware:** A step above theory of mind AI, self-aware AI describes a mythical machine that is aware of its own existence and has the intellectual and emotional capabilities of a human. Like theory of mind AI, self-aware AI does not currently exist.

AI consists of two subfields: the first is ** Machine Learning** & the other is ** Deep Learning.**
  
## What is Machine Learning?

- Machine learning is a field of Artificial Intelligence which deals with developing various learning models and algorithms which helps machines to learn from the data to perform various tasks without explicitly programming for the tasks. 
- Machine Learning has various learning models 
	- Supervised Learning 
	- Unsupervised Learning 
	- Semi Supervised Learning 
	- Reinforcement Learning 
	- Deep Learning 

**Why do we need Machine Learning?**

- In traditional computer science programmers use mathematics to solve problems using logic and reasoning where this logic is translated into code and stored in computers to access this logic to perform problem solving on the inputs it receives. 
- It’s fine until the complexity is at low or medium. But when the complexity or the number of factors affecting a problem increases, handling the problem solving task manually is a very cumbersome task and not even feasible in many perspectives. 
- This is where machine learning enters into the picture and helps us to identify factors and generate logic for solving complex problems which are tough to handle by humans. All it requires is a huge amount of data and process ability to learn from the data. 

**What is supervised Learning?**

Supervised Learning is a model of machine learning where the algorithms learn from labeled data which means we supply huge instances of data which have a set of independent variables and a dependent variable whose values are collected as data where for every instance of data the output value is also mentioned. 
This label helps the algorithms  to map a model which represents the relation between the predictor variables and a response variable. This label acts as a supervisor guiding the algorithm which all the instances lead to what type of output and the algorithm learns from this data and builds a model which can perform tasks like prediction and classification.  

**What is Classification?**

- When we have a huge amount of data which holds the behavior of variables for a period of time. The same data helps us to predict the future of the target variables. This is where machine learning helps businesses to forecast a lot of factors to take business decisions and formulate strategies for the future.  

- Data has two categories in broad based on the type of data 
	- **Numerical Data**
		- Continuous Numerical Data
		- Discrete Numerical Data
	- **Categorical Data**
	  	- Nominal Categorical Data
		- Binomial Categorical Data
		- Ordinal Categorical Data 

We talk about Numerical Data when we learn about the regression task. 

- Let's understand what sort of predictions we can make  if the target variable is a categorical variable. 
- As we just saw there are three types where the Nominal Data holds a unique value for each instance like ID, Name, email, Mobile Number, Acc Num etc. This doesn't hold any information, patterns and no influence on target variables for this type of data is not useful for learning. 

- Based on the rest of the two data types the classification task is divided into two types. 
**Binary Classification.**
**Multiclass Classification.**

## Binary Classification
- Binary Classification is a type of classification task where the target variable has only two class labels for the machine learning to predict. In this case all the instances in the data are needed to be mapped to these two outcomes and formulate the model for classification of instances. 
Example: Credit Card Fraud detection, Loan Defaulter Prediction, etc. 

## Multiclass Classification
Multiclass Classification is a type of classification where the target variable has more than two class labels for prediction. The model has to map all the instances to the labels and formulate the model. 
Example: Character Classification. 

- Most of the people think that machine learning is tough and think it is very difficult to understand.
- That is true for sime extent but we can understand machine learning whe we can have an organized view of the subject. '
- Now I will try to give such organized picture atleast for Classification task which can be similarly applied for other tasks in machine learning.
- This picture allows you organize everything you learn and remember the gamet of machine learning under one tree. 

### Machine Learning 
- Subfield of AI which trains models to perform tasks.
- Its sole purpose is to design different leanring techniques and develop various algorithms to train models and acheive tasks.

### Learning Approaches or Paradigms 
- Now under this field we have various **learning approaches** or we can also called as **Learning paradigms**.
	- **Supervised Learning** - Model learns from labeled data
 	- **Unsupervised Learning** - Model learns from unlabeled data
  	- **Semisupervised Leanring** - Model learns from semi labeled data
  	- **Reinforcement Learning** - Model learns from Rewards & Punishments

### Tasks
- Now lets try to understand what we can do in Supervised Learning
- In supervised leanring we can train models from labeled data so that model can perform prediction **tasks**.
	- **Regression** - If the task is prediction of values for a Numerical Target Variable. 
 	- **Classification** - If the task is prediction of values for a Categorical Target Variable.  
    	 
### Techniques
- Techniques are nothing but a theoritical approach for solving a problem.
- Consider classification task, there are many methods to solve it.
	- **Logistic Regression** - Classifies the data point based on the probability predicted by the sigmoid function.
 	- **K-Nearest Neighbours** - Classifies the data point based on the nearest class in its proximity
  	- **Navie Bayes** - Classifies the data point based on the conditional probability etc.
- There are many techniques for solving each task.
- Each technique holds a specific process of handling the problem and solving it.
- A technique is a theoritacl and mathematical in form
- To apply these techniques in Machine Learning, We have algorithms.

### Original Algorithms & Variants 
- These algorithms are pre written and all we need to do is to import them and train them by giving required inputs.
- The algorithms has two types
	- **Original Algorithms**
 		- Logistic Regression - it is an original algorithm provided by sklearn for classification  
 	- **Variant Algorithms**  
		- Multinominal Logistic Regression - it is an variant which is used when there are morethan two classes.
- This is not over yet, each Algorithm it may be a original or Variant has different implementations provided by multiple libraries
- Note: Techniques are mathematical appraoches for solving problems where as Algorithms are programs to execute that approach

### Implementations
- An Implementation is nothing but a program or an algorithm that is available for us under a specified libraried developed using specific programming languages.
- Let's us see what are Implementations are available for Logistic Regression
	- **LogisticRegression** - This is an Python implementation of Logistic Regression Technique under sklearn library
 	- **Logit** - This is also an Python implementation of Logistic Regression Technique under statsmodels library
  	- **glm funtion** - This is an R implementation of Logistic Regression Technique.
  	- **glmfit function** - This is an matplot implementation of Logistic Regression Technique.


>  Machine Leanirng >> Learning Approaches/Paradigms >> Tasks >> Mathematical Approaches >> Original & Variant Algorithms >> Implementations 


- We learn to train models using algorithms at implementation level.
- Which means we select a particular programming language, Then we select a learning paradigm and task based on the problem, then we choose one of the approaches for solving the problem and we select an Implementation of a orginal or variant algorithm to implement and solve the problem.

- Now let's try to understand what all components we should understand, learn while training the algorithms for performing tasks.
- This is when you defined the problem and selected a paradigm and task to solve the problem. 
	- **Concepts**: Conceptual Framework behind the problem solving approach.
	- **Thoery**: Theoritical approach for solving the problem.(optional)
	- **Variants**: what variant serves best in the specific context of the problem
	- **Implementation**: What specific implemenation which can be implemented
	- **Algorithm Flow** : Step by step procedure folwed by the algorithm to solve a problem.
	- **Advantages & Limitations** : Pros & Cons of using a particular algorithm. 
	- **Assumptions**: what assumptions does the data should hold true to consider an algorithm to train.
	- **Validation of Assumptions**: Validating assumption using statistical tests. 
	- **Importing**: Importing the implementation from the library 
	- **Imputs & Outputs**: What inputs does the Implementation takes while training
   	- **Training Model**: How to train the model using data.
  	- **Model Evaluation**: What metrics we can use to evaluate the model.
	- **Calculation of Metrics**: Using code how to calculate the metrics.
	- **Interpretation of Measurements**: What does it mean to have a specific value for a specific parametre
	- **Hyperparameter Tuning**: How to tune hyperparametres for a better model performance
	- **Hanlding Overfitting**: Techniques to handle over fitting.

This gives a complete list of things to understand and learn to do while training a model using a specific implementation. 
 
Tasks - Regression, Classification 
Classification - Binomial & Multiclass Classification
Binomial Classification - (Techniques / Methods)
LogisticRegression - Statistical Technique for Performing classification
Naive Bayes 
Decision Tree
LogisticRegression - 
- LogisticRegression() - Sklearn Library - (Implementations / Variants)
- Logit() - statistical models library 


