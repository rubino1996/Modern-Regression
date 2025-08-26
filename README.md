## Modern Regression with GLMs in R

Short, hands-on examples of Generalized Linear Models (GLMs) in R—focusing on binomial & quasibinomial, sum-to-zero / deviation coding and treatment / dummy coding). 

## What's inside

- **Cases**
  - Binomial & quasi-binomial logistic regression
  - Treatment (dummy) coding
  - Sum-to-zero (deviation) coding

- **For each case**
  - Clear research question
  - Step-by-step R Markdown
  - Visualizations 
  - Brief interpretation/summary of results
 
# Techniques covered

- Binomial: glm(y ~ x1 + x2, data = d, family = binomial(link = "logit"))

- Quasi-binomial (handles overdispersion): glm(y ~ x1 + x2, data = d, family = quasibinomial(link = "logit"))

- Treatment (dummy) coding: compares each level to a reference

- Sum-to-zero (deviation) coding: compares each level to the grand mean

# Try your own questions
Feel free to fork and plug in your data or modify the Rmds to explore your own research questions and practice your regression skills.
