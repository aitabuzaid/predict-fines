# Predict Blight Ticket Violation Compliance
This project uses data from Detroit city to predict compliance with blight violations. Data includes numerical and categorical features such as:
### Numerical:
- Latitude
- Longitude
- Fine amount
- Late fee
- Judgement amount
### Categorical
- Inspector Name
- Violation Code
- Agency Name

The model processes both types of features as preparation for the classfication model. Gradient Boosting classifier acheives an AUC score of 0.78 on the validation set.
