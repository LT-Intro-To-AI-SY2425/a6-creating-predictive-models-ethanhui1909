# Part 2 - Training and Testing Data Writeup

After completing `a6_part2.py` answer the following questions

## Questions to answer

1. What makes this model more effective than the model you created in the previous lesson?

This model is more effective because the training data, on average, does not account for the outlying data, which would significantly change the regression model equation. 


2. What does the R squared coefficient tell you about the model?
The R squared coefficient represents how closely the generated model accounts for the data as a whole. 


3. Would you say that your model is accurate? What evidence supports your conclusion? Consider the meaning of the predicted and actual values in the context of the chart below from the American Heart Association’s website on understanding blood pressure.

I would not say that this model is accurate because the standard error of the regression model is too high to return any meaningful blood pressure number. Given that the different procedures for blood pressure vary from increments of 10, a standard error of more than 10, which this model greatly exceeds, would considerably change the variablity of what treatment a person of a certain age sohould recieve, which may lead to inconclusive or incorrect conclusions.  