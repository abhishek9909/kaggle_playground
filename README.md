## Rough Plan:
- v0:
    - contains various types of EDA.
    - contains different approaches to solve the problem 
        - i) xgboost with as is without much thought.
        - ii) 'T' binary classifiers, each with it's own xgboost.
        - iii) incorporating original data in the training data in particular.
        - iv) T binary classifiers with original data incorporated as well.

- v1 (will contain):
    - understanding feature importance for each type of prediction and optimizing it.
    - perform feature engineering based on domain knowledge and expected inputs.
    - looking at training curves and making correct judgements for hyperparameters.