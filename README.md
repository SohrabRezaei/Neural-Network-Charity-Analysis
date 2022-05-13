# Neural_Network_Charity_Analysis

## Overview of the analysis

This analysis aims to create a deep neural network to classify whether the donations that were given to this charity are being used appropriately. Afterward, we try to optimize the whole model by first increasing neurons, then adding a hidden layer, and finally increasing the epochs.

## Results

* What variable(s) are considered the target(s) for your model?

The Is Succesful column, which shows whether the donated money was used efficiently, is our target in this specific model.

* What variable(s) are considered to be the features of your model?

The features were any column except our Is Succesful column.

![image](https://user-images.githubusercontent.com/95439555/167424049-f5bcdcc1-422b-404f-9dbe-e4f31ef499e2.png)

* What variable(s) are neither targets nor features, and should be removed from the input data?

Status and ASK_AMT column should be removed because they create noise in the accuracy of the model.

![image](https://user-images.githubusercontent.com/95439555/168325278-2a40bfa3-d935-48a5-ad0d-199874a839d6.png)
![image](https://user-images.githubusercontent.com/95439555/168326507-bfb69172-cb50-496b-95b6-2cdce2febc2c.png)

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

At first, I started with 8 and 5 neurons, respectively, for the two hidden layers. Then, I increased the neurons to 11 for the first hidden layer in order to get a better 

model accuracy. Finally, I added another hidden layer with three neurons to further escalate the model's accuracy.

![image](https://user-images.githubusercontent.com/95439555/168326644-d3d72b0c-d4cc-45d8-8f6f-987dbc7d3170.png)

![image](https://user-images.githubusercontent.com/95439555/168326716-c21ba402-5a0b-4eae-96af-920becc83bae.png)

![image](https://user-images.githubusercontent.com/95439555/168326779-c1d126f4-ed6e-448a-9783-5f603f226b8e.png)

![image](https://user-images.githubusercontent.com/95439555/168326827-2392332f-54a9-4e03-a7b7-466fe9c07533.png)

* Were you able to achieve the target model performance?

No, I couldn't reach 75 percent accuracy.

* What steps did you take to try and increase model performance?

* dropped two features

* Increased the first hidden layer's neurons from 8 to 11

* added another hidden layer with three neurons

## Summary

After several optimization processes, I increased the model's accuracy from 72.37 to 72.79 by dropping features and adding neurons and a hidden layer to the model.

