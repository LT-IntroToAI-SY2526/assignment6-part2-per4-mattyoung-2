# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: bedrooms
2. bathroom
3. age
4. Least Important: squarefeet

**Explanation:**
I ordered them by which one had the largest effect on pricing. Bedrooms had by far the most impact so it was first and the rest followed.



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Each additional bedroom increases the pice by $6648.97


**Feature 2:**

: Age; every new year of age decreases the predicted price by $(-950.35)
---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
My model's R^2 score is 0.9936. This tell me that my model explains 99.36% of the different various house prices



---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Location

**Why it would help:**
House location is the biggest determination in price level.

**Feature 2:**
Lot size

**Why it would help:**

 The lot size is important because if the houses are the same size, the next determination of price would be the area/land size that it sits on.


---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**


I would not trust this model 100% to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old because these features are outside of the training data range.