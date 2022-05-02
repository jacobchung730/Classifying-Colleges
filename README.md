# Classifying-Colleges

Our project is designed to help people apply to college, especially the underprivileged, by allowing them to fill out their ideal university criteria details and helping them figure out whether to look into public, private, or for-profit universities as they begin their college application process. Many students do not have access to good college resources such as counselors or might be the first in their families to navigate the applications, so figuring out the best type of universities to fit them is an important step.

We obtained our dataset from Kaggle. After performing various data wrangling and manipulation, we found it was most efficient to one-hot encode our categorical variables and now use quantitative variables such as as tuition, enrollment, and location. Given some of these feature variables as input, our algorithm will be able to predict whether a school with those characteristics is more likely to be public, private, or for profit.

We started off by using k-Nearest Neighbors, Guassian Naive Bayes, and Decision Tree. By using recusive feature elimination and hyper parameter tuning, we were able to improve the accuracy of our results. We discovered that the two most efficient algorithms to use were k-Nearest Neighbors and Decision Tree, with Decision Tree performing slightly more optimally. 

Upon concluding our project, we were able to determine that the three most important features in classifying a school as public, private, or for-profit are in_state_tuition, out_of_state_total, and total_enrollment. In the future, we feel that we could use more feature variables, add more data points, and also train our model with other algorithms such as Support Vector Machine. 
