# Titanic: predicting from a disaster

Data science project on classification. Data on ~ 800 passengers were given divided in 10 variables. The objective was to predict whether the passenger would have survived or not

# Data preprocessing / EDA

1. extrapolating the info on the doc, 
2. categorizing people according to both title and letter of the ticket, dividing them according to the number of rooms possessed) I applied first a random forest with the grid search and then a simple Keras NN with 2 hiddent layers (on which then I added dropout layers and early stop to prevent overfitting). Given the small amount of data, the NN gave always different results with often the validation loss being lower than the training loss. NN needs definitely more data (in this case we had only 800 rows in our dataset).
