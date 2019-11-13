# Learning_All_Linear_models


we used 90% of our time on understanding the data attributes, to handle missing data, feature extraction, and transformations. Initially We clubbed whole train and test data to do the preprocessing steps together. 

It also took a while since there are so many attributes which are both numerical and categorical. So, we separated and did preprocessing separately.  We also did many mistakes and learned from them, Got Help from TA.  Like example aggregating revenue by customer after getting predictions (we initially did for session wise prediction and then aggregated), for which we didn’t get good scores. 

One Hot encoding is another big task for us. Since there are many categorical / textual data. We considered attributes only which we felt will impact more on revenue in the Realtime.  

Initially for training our model we gave all the variables and then updated formula by considering only which are satisfying P-Value (< 0.05). We didn’t get good R^2.  Then again instead considering with p-value, we calculated correlation with target variable ‘revenue’ took which are more correlated and applied log transformations for which there is skewness. Then we got better score then before. 


Then again with other linear models :

We know we didn’t do well in before modeling, 

got improved a lot now. Thanks to Dr. Nicholson for providing sample modelling. 

Almost the same as we did, expect one feature extraction ‘session_cnt’ and factor lumping. 

And Yes, with or without one hot encoding there is no much effect on end the prediction.  

Lumping helped here. And another mistake we did from HW5 is we didn’t handle negative values from the prediction. we replaced then with zero. 

That’s it - we got really huge difference by using MARS Model then the other models (OLS(HW5), PLS, Ridge, Lasso, Elastic Net). 
