# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
When the StandardScaler part of the program was commented, the model suffered a decrease in accuracy, which would be caused by the overall dataset not accounting for the fact that its inital position would be skewed to one side. 
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
The model with StandardScaler reaches an overall accuracy of 0.84, which would be sufficient for most use cases because well beyond a majority of consumers would logically have their decisions deduced. 

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
The model performed well as it had an overall accuracy of 0.84. There are some occasions where the output was almost exactly the inverse of the predicted output as a general pattern. 
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
Under those parameters, a SUV would not be bought. 
