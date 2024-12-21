# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
The R squared coefficient for my model aproximately 0.86, meaning that this model has a relatively good accuracy in correlating with the original dataset. 

2. Is your model accurate? Why or why not?

The model is fairly accurate as the predicted return values from the linear regression relatively matches with original dataset.

3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?

10 yr, 89k miles -> 9236
20 yr, 150k mles -> 2227

4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?

This happens because this linear regression does not have any bounds in the case that the price does go negative, meaning that given a high miles or age, the predicted price will go negative. 