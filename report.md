# Module 21 Report

## Prediction Analysis for Alphabet Soup Charity

## Purpose of the Analysis
The goal here is to help Alphabet Soup Charity predict which organizations are more likely to receive successful funding. This helps them focus their efforts on projects that really make an impact and have a higher chance of success.

## Model Results
We tried multiple attempts to optimize the neural network model and improve accuracy. Each attempt involved different techniques:
We adjusted the number of neurons and hidden layers.
Changed activation functions.
Added Dropout layers to prevent overfitting.
Tweaked the number of epochs to give the model more time to learn.
In the end, while we didn’t hit the 75% accuracy target, the model showed consistent results and was close to the goal. With these results, Alphabet Soup has a model that’s fairly good at identifying patterns of success among organizations, though it still has room for improvement.

## Results Questions
What accuracy did the model achieve? The accuracy was around 72-73%.
How many epochs did you use to train the model? We tested different configurations, with the best results using 150 and 200 epochs.
How many hidden layers does the model have? The final model has 3 hidden layers.
What optimization techniques did you use? We added more neurons, additional hidden layers, Dropout, and different activation functions.
What were the final loss and accuracy results? The loss was between 0.53 and 0.56, and accuracy stayed around 72-73%.
Which activation function worked best? The relu and tanh functions worked best in combination with Dropout layers.

## Overall Summary
Although the model didn’t reach the target accuracy, we tried various techniques and got consistent accuracy close to 73%. This suggests that the model can give a general idea of an organization’s likelihood of success, although there’s still room to improve.

## Next Steps with Other Models
We might consider trying different models, like decision trees or ensemble methods like Random Forest, as they often work well with tabular data. These models could better handle the non-linear relationships between variables and might reach higher accuracy without requiring so much manual tuning.