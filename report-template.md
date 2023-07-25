# Module 21 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the neural networks machine learning models used in this Challenge. This might include:

* Overview of the analysis. Explain the purpose of the analysis.

The purpose of this analysis is to assist the Alphabet Soup nonprofit foundation in selecting the applications with the best chance of success in their venture.

## Results
Using bulleted lists and images to support your answers, address the following questions:

* Data Preprocessing:
    * What variable(s) are the target(s) for your model?
    
    The target for this model is if a application with a successful outcome. The column is labeled "IS_SUCCESSFUL".
    
    * What variable(s) are the features for your model?
    
    The variables in this model include the application type, the affiliation (affiliated sector of the industry, the classification (government organization classification), the use case (use case for funding), the organization type, the status (active or inactive), the income classification, the ask amount and any spceial considerations. 
    
    * What variable(s) should be removed from the input data because they are neither targets nor features?
    
    The EIN and Name columns were dropped because tehy were neighter targets or features. 

* Compiling, Training, and Evaluating the Model

    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
    There is an initial layer, a hidden layer and an output layer. The initial and first hidden layer have 6 neurons each, and the activation function is relu for both layers. I chose relu because it is the most reliable activation function for neural networks. The output layer has 1 neuron and an activation function of sigmoid. 
    
    * Were you able to achieve the target model performance?
    
    I was close but unable to achieve teh target model performance of 75% accuracy or above. The model, even after several attempts to optimize, were only 72%.
    
    * What steps did you take in your attempts to increase model performance?
    
    In order to increase model performance, I tried several things. First, in addition to binning the classification and application types, I binned income amount categories. I also added an additional hidden layer and added 2 neurons to the prexisting second layer. Finally, I adjusted the activation function from relu to tanh for the newly added layer. 
   
## Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Overall, the results between both the initial AlphabetSoupCharity code and the optimized code are very similar, despite attempts to optimize the code. However, I would ultimately recommend the initial model. While it includes one less layer and slightly less binning. However, with fewer neurons and one less layer, it runs more quickly, occupying less space and memory, while achieving the same results, and is therefore more economical for the organization to use when computing.