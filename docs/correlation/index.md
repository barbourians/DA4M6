# Correlation - Theory

## What is Correlation?
Correlation is a statistical measure that **describes the strength and direction** of a relationship between two variables. It tells us how changes in one variable are associated with changes in another.  

**Correlation ranges from -1 to 1**

### Positive correlation (+1)
- As one variable increases, the other also increases (e.g., height and weight).

### Negative correlation (-1)
- As one variable increases, the other decreases (e.g., temperature and hot chocolate sales).

### No correlation (0)
- No predictable relationship between the variables.

## Correlation Analysis
Correlation analysis is a statistical method used to measure the strength and direction of the relationship between two or more variables. It helps determine whether and how strongly variables are related.  

### Strength of the Relationship
- Strong, moderate, or weak correlation
- Measured by the correlation coefficient

### Direction of the Relationship
- **Positive correlation**: As one variable increases, the other also increases.  
- **Negative correlation**: As one variable increases, the other decreases.  
- **No correlation**: No pattern or relationship between variables.  

### Types of Correlation Measures
- Pearson's Correlation Coefficient (r): Measures linear relationships (values between -1 and 1).  
- Spearman's Rank Correlation (ρ): Measures monotonic relationships (for ranked or non-linear data).  
- Kendall's Tau (τ):  Another rank-based correlation measure.  

## The correlation coefficient
- The correlation coefficient is a numerical value that **quantifies the strength and direction** of the relationship between two variables.
- It ranges from -1 to 1 and is commonly represented by r (for Pearson’s correlation).

### Interpreting the Correlation Coefficient (r):

| Value        | Interpretation |
|--------------|----------------|
| +1           | Perfect positive correlation (both variables increase together) |
| +0.7 to +0.9 | Strong positive correlation. |
| +0.4 to +0.6 | Moderate positive correlation. |
| +0.1 to +0.3 | Weak positive correlation. |
| 0            | No correlation (variables are unrelated). |
| -0.1 to -0.3 | Weak negative correlation. |
| -0.4 to -0.6 | Moderate negative correlation. |
| -0.7 to -0.9 | Strong negative correlation. |
| -1           | Perfect negative correlation (one variable increases while the other decreases). |

## Correlation Coefficient ~ Example

**Scenario**: A researcher measures study hours and exam scores for five students:

| Study Hours (X) | Exam Score (Y) |
| --------------- | -------------- |
|  2              | 50             |
|  4              | 65             |
|  6              | 75             |
|  8              | 85             |
| 10              | 95             |

Using Pearson's correlation formula, we get **r ≈ 0.98**, indicating a **strong positive correlation**.

---
## Correlation is an association
- link/relationship/dependency/similarity between two or more variables
- both variables must be numeric
- **avoid claiming causation**

## Strength of the correlation
The Strength of the correlation is measured by the correlation coefficient, which:
- quantifies the strength of the association between numeric data
- ranges from -1 to +1
- sign only indicates if the dependency is positive or negative
- the absolute value (between 0 and 1) indicates the strength of the relationship

## Correlation coefficient CAN TELL:
- can tell the sign of the dependency (positive / negative relationship)
- can tell the strength of the relationship (regardless of underlying reasons)

## Correlation coefficient DOES NOT:
- does not work with non-linear data
- does not tell if there is a relationship or not
  - but rather how strong it is
- does not prove that change in one variable CAUSES change in another variable
  - **so correlation is not causation**
- does not tell the direction of the dependency
  - i.e. which variable is dependent and which one is independent
- does not detect if two variables we're looking at do not depend on each other at all
  - they could rather depend on another, third variable, which hasn't been even included into the model 
- does not exclude the possibility that two variables that seem to follow the same trend is pure coincidence
- does not tell the shape of data
  - completely different distributions can produce identical coefficient
  - https://en.wikipedia.org/wiki/Anscombe%27s_quartet

## To summarise:
Correlation coefficient only tells is two variables follow the same trend/pattern – regardless of the underlying reasons/dependency/randomness

However, it does not specify the direction of the dependency (if there is such dependency) – so correlation is not causation
