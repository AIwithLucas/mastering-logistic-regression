# Learnings

## 1. Categorical Feature Encoding

- Label Encoding: order matters
- one-hot encoding: order doesnt matter + convert true/false to 1 & 0 using astype(int) for machine learning

## 2. Use mutual_information to find out usefulness of features for logistic regression

- can be for both continuous / discrete
- discrete variables have to be encoded first

## 3. use feature scaling on data before feeding to model (esp. if categorical variables are encoded)

- to prevent sigmoid fn from overflowing to infinity
- scale very small values to larger values
