## DESCRIPTION
Exploring and implementing neural networks using the TensorFlow platform in Python. We explore the major costs and benefits of different neural networks and compare these costs to traditional machine learning classification and regression models. Additionally, we practice implementing neural networks and deep neural networks across a number of different datasets, including image, natural language, and numerical datasets. Finally, we learn how to store and retrieve trained models for more robust uses.

### SITUATION/TASK
Use a machine learning model and neural network model to build and predict the success of a venture paid by Alphabet Soup Company.
Create a binary classifier to project which applicants are likely to be successful if they received future funding from Alphabet Soup. 

### APPROACH
Used a CSV file with more than 34,000 organizations that have received various amounts of funding from Alphabet Soup over the years.
First, import, analyze, clean, and preprocess a “real-world” classification dataset. Then select, design, and train a binary classification model of your choosing. Finally, optimize model training and input data to achieve desired model performance.

### RESULTS
1) How many neurons and layers did you select for your neural network model? Why?

Prior to optimizing model, the model was using 8 and 5 neurons for hidden_nodes_layer1 and hidden_nodes_layer2
respectively because there were 8 feature columns and so as to not overfit the model.
There were also 2 hidden layers used, along with the relu activation function.

2) Were you able to achieve the target model performance? What steps did you take to try and increase model performance?

No, model did not achieve the target model performance even after optimizing model. It acted poorly at accuracy rate = 53%

However, steps taking to increase model performance includes:
* Adding more neurons on the different hidden layers
* Adding one more hidden layer to allow neurons to train on activated input values

* Using different activation functions across hidden layers

3) If you were to implement a different model to solve this classification problem, which would you choose? Why?

Most likely the Decision Tree model as it tends to have a higher accuracy rate and Decision Trees can handle both categorical and numerical data.

### THINGS LEARNED
* Compare the differences between the traditional machine learning classification and regression models and the neural network models.
* Describe the perceptron model and its components.
* Implement neural network models using TensorFlow.
* Explain how different neural network structures change algorithm performance.
* Preprocess and construct datasets for neural network models.
* Compare the differences between neural network models and deep neural networks.
* Implement deep neural network models using TensorFlow.


