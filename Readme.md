<!--Headings-->
# Data Science Assignment
## Assignment 1 --> Part 1 : Predict the price of a house:

### A) SUMMARY:

####  Models and Assumptions used: 
 1) Models used here are

                    a) Linear regression.

                    b) Polynomial linear regression degree 2 and 3.
                        
                    c) Lasso and Rigde regularisation. (to check the overfitting)
                        
2) Assumptions used to verify the model:
                  
                    a) Monocolinearity

                    b) Linear relation between inputs and output(Trick check residual of inputs relationship with output)
                                       
                    c) Linear relation should be homoskedastick and not heteroskedastick
                                       
                    d) Residual should have no skewness

### B) ANALYSIS:
            1) Accuracy with Linear Regression was around 66% but 3 out of 4 assumptions mentioned above were not satisfied so we we rejected the model

            2) We used Polynomial Regression model with degree 3 and it satisfied all the assumptions with a much better accuracy score of 79.8%.

            But we found that the model of overfit and to reduce the overfitting we moved to Lasso and Ridge regularisation.

            3) Here we found that Lasso made all the slopes of input zero so we could not use that model to reduce the overfitting and hence we moved to Ridge regularisation.

            4) After applying Ridge regularisation we found that the accuracy got reduced to 67% but we saw that the difference between training and testing score reduced thus reducing the overfitting.        

## Assignment 2 --> Part 2: Product matching:            

            1) The libraries used here are numpy,pandas and warnings.

            2) To compare the similar products I have given 5 different options for the user to choose and then used 'merge()' function accordingly to join the 2 tables.
