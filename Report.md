**Data Preprocessing**

**What variable(s) are the target(s) for your model?**
-The target variable is the 'IS_SUCCESSFUL' column in application_df
**What variable(s) are the features for your model?**
Feature variables are every other column from application_df. This was done by dropping the 'IS_SUCCESSFUL' column from the original dataframe
**What variable(s) should be removed from the input data because they are neither targets nor features?**
Both 'EIN' and 'NAME' columns were dropped/removed, as they are not targets or features for the dataset

**Compiling, Training, and Evaluating the Model**

**How many neurons, layers, and activation functions did you select for your neural network model, and why?**
-In the first attempt, i used 6 hidden_nodes_layer1 and 4 hidden_nodes_layer2 and then from there was able to hone in more to get better results. 
**Were you able to achieve the target model performance?**
-I was unable to acheive the 75% target performance. I was able to get it to 72-73%
**What steps did you take in your attempts to increase model performance?**
-I attempted to add more layers, remove additional columns, add additional hidden nodes, and tried to switch up the activation functions associated with each layer but was unable to achieve a higher model performance

**Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.**
-In summary the deep learning model was roughly 72-73% accurate in prediciting the classification problem. If we used a model that had better correlation the input and output  would likely result in a better prediction accuracy. We could acheive this by doing additional data cleanup on the front end or we could use a different model all together. A different model with different activation functions may allow us to obtain a higher accuracy score as well. 
