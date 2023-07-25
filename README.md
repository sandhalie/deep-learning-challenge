# deep-learning-challenge

## Purpose
The purpose of this challenge is to develop a machine learning model that can predict whether applicants will be successful if funded by the nonprofit foundation Alphabet Soup. The dataset provided contains information about more than 34,000 organizations that have previously received funding from Alphabet Soup. Each organization's data includes various features like EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, and the target variable IS_SUCCESSFUL, which indicates whether the funding provided to the organization was used effectively or not.

By using machine learning and neural network techniques, the goal is to create a binary classifier that can accurately predict whether an organization will be successful if funded by Alphabet Soup based on the provided features. This classifier will help the foundation's business team in selecting applicants with the best chance of success for their ventures, ensuring that the funding is directed towards organizations likely to make the most impact with the resources provided.

The successful implementation of this classifier can assist Alphabet Soup in making informed decisions about where to allocate their funding, ultimately maximizing the positive outcomes and benefits of their philanthropic efforts.

## Results
### Data Preprocessing
Target for the model is IS_SUCCESSFUL
Features for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
EIN and NAME columns were removed from the input data because they are neither targets nor features

### Compiling, Training, and Evaluating the Model

3 layers were used in the neural network model with 80,30,30 nuerons respectively. The activation funtion used was the sigmoid function as the model output is binary classification had to be between 0 and 1.
Accuracy reched by the model is 0.7294460535049438
Summary: Summarise the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

The neural network trained model from the keras tuner method achieved 73% prediction accuracy with a 0.57 loss, using a sigmoid activation function with 3 hidden layers at a 80, 30, 30 neurons split and 50 training epochs. Performing better than the non automized model.