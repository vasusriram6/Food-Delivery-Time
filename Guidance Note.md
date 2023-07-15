There are mainly 3 types of feature selection techniques:
  1. Filter methods
  2. Wrapper methods
  3. Embedded methods

1. Filter methods: They select features from the dataset no matter what ML algorithm is going to be used. It is computationally faster and cheap to use filter methods on high-dimensional datasets.

 Some Filter methods are:
  
  i) Information Gain: Measures the amount of information provided by the feature for predicting the target value
  
  ii) Chi-square test: Used to test the relationship between two categorical variables
  
  iii) Fisher's Score: Ranks the features by their scores under Fisher Criterion
  
  iv) Correlation Coefficient: Measures the relationship between two continuous variables



2. Wrapper methods: Wrapper methods, also referred to as greedy algorithms train the algorithm by using a subset of features in an iterative manner. Based on the conclusions made from training in prior to the model, addition and removal of features takes place. They are computationally slower and expensive

   Some Wrapper methods are:

   i)Forward Feature Selection: Add features one by one until the performance of the model stops improving
   
   ii)Backward Elimination: Works the opposite way compared to forward feature selection. Eliminates least significant features until the model performance stops         improving
   
   iii)Exhaustive Selection: Tries all combinations of selected features and picks the one with best performance

   iv) Recursive Elimination: Selects features by recursively considering smaller and smaller sets of features
   

4. Embedded methods: They take the best parts of both filter and wrapper methods, having the accuracy close to wrapper methods while also being computationally reasonable.

   Some Embedded methods are:

   i) Regularization: This method adds a penalty to different parameters of the machine learning model to avoid over-fitting of the model.

   ii) Tree-based methods: Provides us feature importance as a way to select features as well.
   
