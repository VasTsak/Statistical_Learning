# Statistical Learning

It is an area of statistics combined with machine learning. It is a recently developed method of understanding complex data sets.

Let's assume that we want to predict *Y* based on *X*. We assume that there is a function *f(X)* that approximates *Y*.

*Y = f(X) + ε*

Where ε is a random error term.

Statistical Learning, is a set of methods that approximate this *f* function. This *f* function can be used for **prediction** or **inference**. In the former case, we want to predict the dependent variable (*Y*) using a set of independent variables (*X*). In the latter case, we want to see the impact of the independent variables on the dependent variable (association of *X* with *Y*, relationship *Y* with *X*)

Statistical Learning can be divided into **supervised learning** and **unsupervised learning** tools. 

**Supervised Learning**: we want to predict/inference a target variabe Y based on predictors X.

  * Supervised learning can be divided to **Classification models** that predict discrete values (cat/ not a cat( annd **Regression models** that predict continuous values (Sales / Stock price).

**Unsupervised Learning**: we want to understand the relationship between variables (fields/columns) or observations (rows).

Another dimension that can be used to differentiate the Statistical Learning methods, is whether they are paramentric or non parametric.

**Parametric** methods, are those that we have made an assumption on the formula (e.g Y = βο + β1 * Χ1 + β2 * Χ2) and then we train the parameters (βο, β1, β2) so that the formula fits the data. 

**Non Parametric** methods, we make no assumption of the formula of *f(X)*. Instead we approxiamte the *f(X)* that fit the data best. 

What is the best method to use though? Well, it depends on what you need! If you want to be able to *Interprete* the results, then you should go for a **parametric** method. On the other hand, if your goal is to have the highest *accuracy possible* and don't care about the *interpretability* of the model you should go for a **non parametric** method.


But what is the difference between **Statistical Learning** and **Machine Learning**? 
