# BOMBAY-HOSPITALITY-Hypothesis-Test
To investigate restaurant owner claim about increase in weekly operating costs

# <h1 align="center"><font color='green'>**HYPOTHESIS TESTING**</font></h1>

### Background:
<br/>
Bombay hospitality Ltd. operates a franchise model for producing exotic Norwegian dinners throughout New England. The operating cost for a franchise in a week (W) is given by the equation W = $1,000 + $5X, where X represents the number of units produced in a week. Recent feedback from restaurant owners suggests that this cost model may no longer be accurate, as their observed weekly operating costs are higher.
Objective:
To investigate the restaurant owners' claim about the increase in weekly operating costs using hypothesis testing.
<br/>
Data Provided:
<br/>
•	The theoretical weekly operating cost model: W = $1,000 + $5X
<br/>
•	Sample of 25 restaurants with a mean weekly cost of Rs. 3,050
<br/>
•	Number of units produced in a week (X) follows a normal distribution with a mean (μ) of 600 units and a standard deviation (σ) of 25 units

### State the Hypotheses statement

H0: μ = 1000 + 5*600 = Rs. 4000
<br/>
H1: μ > 4000

### Calculate the Test Statistic

This is the formulas for t-test
<br/>
$t = \frac{\bar{X} - \mu}{\sigma / \sqrt{N}}$
<br/>
X̄ = sample mean weekly cost = Rs. 3,050
<br/>
μ = theoretical mean weekly cost according to the cost model (W = $1,000 + $5X for X = 600 units)
<br/>
σ = standard deviation of the weekly cost = 5*25 = 125
<br/>
n = sample size = 25 restaurants

Calculate the mean for theoretical cost
<br/>
μ = 1,000+5×600
  =1,000+3,000
  =4,000

Compute the t-test
<br/>
$t = \frac{\3050 - \4000}{\5x25 / \sqrt25}$
<br/>
### Determine the Critical Value

Using an alpha level of 5% (𝛼=0.05) for a one-tailed test, we can determine the critical value from the standard normal (Z) distribution table.
<br/>
For a one-tailed test at 𝛼=0.05, the critical value is approximately 1.645.

### Make a Decision

Compare the calculated test statistic with the critical value to decide whether to reject the null hypothesis.

Let's perform this in Python

```ruby
import math

#Given data
sample_mean = 3050
theoretical_mean = 4000
sample_std = 5*25
sample_size = 25

# Calculate the test statistic (t)
t_statistic = (sample_mean - theoretical_mean) / (sample_std / math.sqrt(sample_size))
t_statistic
```

-38.0

```ruby
# Determine the critical value for one-tailed test at alpha = 0.05
alpha = 0.05
critical_value = 1.645
```

```ruby
# Compare test statistic with critical value
reject_null = t_statistic > critical_value
reject_null
```
False

```ruby
# Output results
(t_statistic, critical_value, reject_null)
```

(-38.0, 1.645, False)

## **Results**


1. Test Statistics (t) : -38.0
2. Critical Value : 1.645
3. Decision : Do not reject the null hypothesis


## **Conclusion**

Based on the test statistic and the critical value, we do not reject the null hypothesis. This means there is no strong evidence to support the restaurant owners' claim that the weekly operating costs are higher than the theoretical model suggests. The observed mean weekly cost of Rs. 3,050 is significantly lower than the theoretical mean cost of Rs. 4,000, contradicting the claim of higher costs.
