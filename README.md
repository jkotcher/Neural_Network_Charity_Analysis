# Neural_Network_Charity_Analysis

# Overview of the Analysis
The purpose of this analysis was to use a neural network model to determine where Alphabet Soup should invest its money, more specifically what organizations would be most suited to recieve funding.

# Results

## Data Preprocessing
1. The target variable for this model is the "Is_Sucessful" column values.
2. The same column but the original column.
3. The columns that were initially dropped such as "EIN" and "NAME" are neither.  In addition to those two, other columns that would not be considered features or targets would be the two special considerations columns at the end of the DataFrame.


## Compiling, Training, and Evaluating the Model
1. In the initial attempt for the model I chose to use two hidden layers and two activation functions.  I also decided to go with 43 input features and this element through both the initial and optimization I chose to keep the same.  As a first step I just wanted to see what accuracy this would achieve as a way to see how much I would need to gain to get to 75% performance.  
2. I was not able to achieve the target performance in the initial model nor during the three attempts to achieve the terget model performance.
3. Through the three attempts to try to increase the model performance a general rule I followed was to try to optimize the model itself by changing the number of layers, nodes, and changing the activation functions.  The reason I felt this made sense is because while noisy data will affect the model there is a lot of optimization that one can do by changing structural components of the model i.e. number of nodes in each layer.  Also, I felt that changing the data itself in this case might not add as much since there was already a certain amount of preprocessing that took place.  Specific steps taken was to add more layers which for the second attempt there were four layers instead of two.  The first attempt to optimize the model was by adding more nodes to the two layers present.  During the third attempt the changes made were adding an additional layer and changing the activation function.


# Summary
Overall the model did not perform as well as expected.  I was able to get the performance up to 53% through the three attempts.  In order to fully assess the accuracy of the model, more attempts would be needed to determine what steps are best for optimization.  In addition to that another step would be to drop data as I did not do that.  As a recommendation for further research and testing the use of a neural network model is sufficient and terget performance could be achieved but through more testing and training and tinkering of the model such as nodes, layers and activation functions.
