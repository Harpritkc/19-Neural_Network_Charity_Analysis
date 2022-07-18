# 19-Neural_Network_Charity_Analysis
 
### Overview
The purpose of this analysis is to use a neural network to decide which companies should recieve loans from Alphabet Soup. This analysis uses python's TensorFlow library to create, train, and evaluate data gathered from previous loans.

### Results
Data Preprocessing
After looking at the data, I established that the target variable is the "IS_SUCCESSFUL" column. I then removed the "EIN" and "NAME" columns as they did not offer any relevant data that could help the model perform better. The remaining columns became the features for the model.

### Compiling, Training, and Evaluating the Model

For my first attempt at compiling a neuron network consisted of 80 neurons in the first layer and 30 in the second. Both layers had relu activation functions and the output layer had a sigmoid activation function. I started with these parameters as relu does better with nonlinear data, and two layers allows for a second layer to reweight the inputs from the first layer. Here are the preformance metrics of this model.

<img width="715" alt="ASC1" src="https://user-images.githubusercontent.com/99519095/179438876-6edf6ae1-6062-47dd-acea-bec134aec88b.png">


For my seconf attempt at compiling a neuron network consisted of 8 neurons in the first layer and 5 in the second. Both layers had relu activation functions and the output layer had a sigmoid activation function.

<img width="711" alt="ASC" src="https://user-images.githubusercontent.com/99519095/179438930-6c48d1b4-00d1-45de-8700-3d1e5d5dc1a8.png">

In my third attempt, at compiling a neuron network consisted of 12 neurons in the first layer and 6 in the second. Both layers had relu activation functions and the output layer had a sigmoid activation function..

<img width="709" alt="ASCO" src="https://user-images.githubusercontent.com/99519095/179438976-e45b9125-4305-4fbc-ad7d-e5827345ba8c.png">

### Summary
After four attempts, I was unable to create a model that could preform a 75% accuracy rating. This is potential becasue I got rid of too many columns, I did not use the correct activation function, or I did not have hte right amount of layers and neurons. These were the main areas I continued the change with little to no improvement. Next time, I would research more about activation functions to make sure that I am always choosing the right one based on the data.
