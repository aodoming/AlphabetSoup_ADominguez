Include a 5–10 sentence writeup in your README that addresses the following questions:


1) How many neurons and layers did you select for your neural network model? Why?

Prior to optimizing model, the model was using 8 and 5 neurons for hidden_nodes_layer1 and hidden_nodes_layer2 respectively because there
were 8 feature columns and so as to not overfit the model.
There were also 2 hidden layers used, along with the relu activation function.


2) Were you able to achieve the target model performance? What steps did you take to try and increase model performance?

No, model did not achieve the target model performance even after optimizing model. It acted poorly at accuracy rate = 53%
However, steps taking to increase model performance includes:
-- Adding more neurons on the different hidden layers
-- Adding one more hidden layer to allow neurons to train on activated input values
-- Using different activation functions across hidden layers


3) If you were to implement a different model to solve this classification problem, which would you choose? Why?
Most likley the Decision Tree model as it tends to have a higher accuracy rate and Decision Trees can handle both categorical and numerical data.
