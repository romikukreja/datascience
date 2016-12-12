##Types of Data Science Questions
### In approximate order of difficulty
* Descriptive
* Exploratory
* Inferential
* Predictive
* Casual
* Mechanistic

## Descriptive
Goal - Desrcibe a set of data
* The first kind of analysis performed
* Commonly applied to census data
* Descrition and Interpretation of this data are two different steps
* Descriptions usually can not be generalized without additional statistical modeling - 
  in other words you are describing what you see in data but cannot predict about other records
Example - Google Ngram

## Exploratory
Goal - Find relationships you didn't know about
* Exploraory models are good for discovering new connections
* Useful for defining future studies
* Usually not the final say
* Exploratory analysis alone should not be used for generalization/prediction
* Correlation does not imply causation

## Inferential
Goal - Use a smaller set of data to extrapolate/generalize to a bigger population
* Inference is commonly the goal of statistical models
* Inference involves estimating both the quantity you care about and your uncertainity about the estimate
* Inference relies heavily on both the population and the sampling scheme

## Predictive
Goal - To use data on some objects to predict values for another object
* If X predicts Y it does not mean that X causes Y
* Accurate prediction depends heavily on meausing the right variables
* Although there are better and worse prediction models, more data and simple models work really well
* Prediction is very hardr, specially about future reference

## Casual
Goal - To find out what happens to one variable when you change another
* Usually randomized studies are required to identify casuation
* There are approaches to inferring causation in non-randomized studies, but they are complicated and sensitive to assumptions
* Casual relationships are usually identified as average effects, but may not apply to every individual
* Casual models are usually the "gold standard" for data analysis

## Mechanistic  - Very rarely used in Data Science
Goal - Understand the exact changes in variables that lead to changes in another variables for individual objects
* Incredibly hard to infer, except in simple situations
* Usually modeled by a deterministic set of equations (physical/engineering science)
* Generally the random component of data is measurement error
* If the equations are known but parameters are not, they may be inferred by data analysis

# Data
* Question is the most important thing in data science
* Data is the second most important factor
* Often the data will limit or enable teh question
* But having data cant save you if you dont have the question


# Data Scientists to follow
* Nate Silver
* Andrew Ng
* 


##Machine Learning Types
### Supervised Learning  - We gave dataset with right answers given and have labelled data
* Regression - Predict Continuous valued output - regression analysis is a statistical process for estimating the relationships among variables. It includes many techniques for modeling and analyzing several variables, when the focus is on the relationship between a dependent variable and one or more independent variables (or 'predictors')
Example- Given a picture of a person, we have to predict their age on the basis of the given picture

    * Linear Regression - Straight line
    * Polynomial Regression - Curve


* Classification - Predict Discrete valued output - Statistical classification, identifying to which of a set of categories a new observation belongs, on the basis of a training set of data
Example - Given a patient with a tumor, we have to predict whether the tumor is malignant or benign.

### Unsupervised Learning - Unlabelled data - Automatically cluster data
* Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.

We can derive this structure by clustering the data based on relationships among the variables in the data.

With unsupervised learning there is no feedback based on the prediction results.

Example:

* Clustering: Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.

* Non-clustering: The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a cocktail party).



