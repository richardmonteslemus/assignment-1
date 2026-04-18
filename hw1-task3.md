# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

> **This is a regression problem since we are predicting species richness. We are more interested in inference because the goal is understanding which factors affect species richness, not predicting a specific value. The size of the observation dataset is n = 200 and there are p = 4 predictors (reserve size, years since establishment, enforcement budget, proximity to human settlements).**

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.


> **This is a prediction problem**


> **This is a classification problem since we are predicting if a corridor will successfully support wildlife movement or not and that is a binary variable. We are more interested in prediction because the agency wants predit waht class (successful or unsuccessful) the corridor will be based on a number of predictors. The size of the observation dataset is n = 30 and there are p = 11 predictors (corridor width, length, surrounding land use type, and eight other variables).**

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

> **This is a regression problem because we are predicting ozone concentration. We are more interested in prediction because the goal is predicting future ozone levels, not understanding the relationship between variables. The size of the observation dataset is n = 52 (one observation per week in 2019) and there are p = 4 predictors (sea surface temperature, wind speed, solar radiation, and atmospheric pressure).**

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

> **A very flexible approach will reduce error for the specific data we are using, so it can capture more complex patterns. The tradeoff is that it increases variance and may overfit, making it less generalizable to new data. A more flexible approach is preferred when the relationship is not a simple linear relationship. A less flexible approach is preferred when the relationship is linear. When inference is the goal we may prefer a flexible approach that can capture general patterns nuances. When predicition is the goal, a less flexible approach might be better in order for it to be generalizable to diferent data and make reliable predictions we might rely on to make informed decisions.**

---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

> **A parametric approach means there is a specific model that can be used to represent the relationship between the predictor and response. A non-parametric approach means you use a method that finds its own relationship by looking at patterns in the data. The advantage of a parametric approach is that it is simpler and easier to understand and more automated than a non-parametric approach. A disadvantage for a parametic appraoch is that if the model is not appropriate the model will not perform well**