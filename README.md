def get_user_info():
    name = input("What is your name? ")
    
    age = input("How old are you? ")
    
    study = input("What are you studying? ")
    
    print("\n--- User Information ---")
    print(f"Name: {name}")
    print(f"Age: {age}")
    print(f"Studying: {study}")

get_user_info()


model 1 : The Logistic Regression Model

best used in classification of binary data.
Easy to understand and apply model.
provide estimations of the probability.

model 2 : random forest

adaptable to regression and classification.
Strong against overfitting because to the group aspect.
Capable of efficiently managing extensive datasets and high-dimensional feature spaces.
Each model has advantages and disadvantages, and the selection of a model depends on the specific issue at hand, the type of data, and the balance between interpretability and prediction capability.
