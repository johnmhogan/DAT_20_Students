*Provide answers to these questions in your own words:*

1. The error you calculated in step 4 is called generalization error. 
    Explain why it's called generalization error and why it's important when evaluating our regression model.
2. Of the features you used for regression above, which one best explains cnt?
3. Which variables in the dataset are correlated and how do these affect your regression?
4. How would the p-value of our regression change as we took smaller subsets 
    of the dataframe to build our training model?

*1. The error you calculated in step 4 is called generalization error. 
Explain why it's called generalization error and why it's important when 
evaluating our regression model.*

The difference of the R^2 values from applying the model to the training 
dataset vs. the test dataset is called 'generalization' error, because the 
model is attempting to describe a formula that fits one set of data, but 
differences in the score when applying it to a different set indicate that 
your model is not 'general' enough. A high generalization error indicates 
that the model was over fit to the training data. 

*2. Of the features you used for regression above, which one best explains 
cnt?*

in this model: atemp, with a coefficient of 169.23306331263109
 
*3. Which variables in the dataset are correlated and how do these affect 
your regression?*

tmp and humidity are inversely correlated, so they will effectively cancel 
each other out

tmp and atemp are somewhat correlated, but they should actually have a 
similar effect on the model in real life, so we should probably only use one
 of them.
   
rush_hour is extremely correlated. 
 
*4. How would the p-value of our regression change as we took smaller subsets 
of the dataframe to build our training model?*
