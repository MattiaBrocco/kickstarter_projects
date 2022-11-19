# Kickstarter campaigns (October 2009 - January 2018)

*TOPICS*: R, Classification, Machine Learning


Comparison of ML algorithms for a binary classification task on Rstudio.


Kickstarter is a great crowdfunding platform used worldwide. To date it has been used to raise more than 5 billion dollars and with a total of nearly 200.000 successfully funded projects, with a success rate of 38% (SOURCE: Kickstarter).

Through a dataset found on Kaggle I've tried to see if it was possible to predict the outcome of a project (from 2018 to date) given its category, the period of activity and the cash target of the project.

I wanted to conduct this work with Rstudio, to deepen my knowledge on the syntax for ML algorithms, specifically for binary classification tasks.

Interestingly, here an estimation (via Bass Model) for the amounts of the campaigns grouped by month. During the span analyzed, it seems that the popularity of the campaigns started on Kickstarter has almost finished its lifecycle (what the Bass Model is designed to infer).
![image](https://user-images.githubusercontent.com/61026948/202702772-3d33e4f4-2f2e-461e-904a-ba9f2474560c.png)


### SOURCES
[1] Data: https://www.kaggle.com/kemical/kickstarter-projects
[2] Mahajan, V., Muller, E., & Bass, F. M. (1990). *New Product Diffusion Models in Marketing: A Review and Directions for Research*. Journal of Marketing, 54(1), 1–26. https://doi.org/10.1177/002224299005400101
[3] Max Kuhn. Contributions from Jed Wing, Steve Weston, Andre Williams, Chris Keefer, Allan Engelhardt, Tony Cooper, Zachary Mayer, Brenton Kenkel, the R Core Team, Michael Benesty, Reynald Lescarbeau, Andrew Ziem, Luca Scrucca, Yuan Tang and Can Candan. (2016). [*caret: Classification and Regression Training. R package version 6.0-71*](https://CRAN.R-project.org/package=caret)
