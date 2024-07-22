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
![image.png](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAANoAAABjCAIAAAByuokxAAAIcElEQVR4Ae2c32tSbxzHv//AueiyP2BdeLWLLsLszm6CGgOhRohJrF1szSCMTQtchThylczsB0RQbWyIixGuiGHQLmobaxsyWLYwHa2GGwexmaKe86WedjDbps/R53ja3ufGc46f53Oe8/q8PD4eH/1PxAICqiHwn2p6go6AgAgdIYGKCEBHFRUDXYGOcEBFBKCjioqBrkBHOKAiAtBRRcVAV6AjHFARAeioomKgK9ARDqiIAHRUUTHQFegIB1READqqqBjoCnSEAyoiAB1VVAx0BTrCARURgI4qKga6Ah3hgIoIQEcVFQNdgY5wQEUEoOPvYkSjUZPJ1PTnYjKZotGoisq127sCHX9XOJfL8Ty//ufC83wul9vtDqjo/KCjioqBrkDH3w6k02m/39/S0nLhwoXl5eX5+fnW1taOjo5q3qwFQRgYGHC5XNlslhxmY2NjYGAgHo/DvC0JQMefWDKZTF9f38zMjCAIo6OjOp3ObrfHYrHW1laHw5HP57dkV3ZnMpk0Go1Op1MQBBIcCoUaGxvD4XDZtnszADr+rPvr16/9fr9kTENDw+zs7NTU1P79++/fvy/bjEgkotVqg8GglMHtdhsMBp7npT1YKSZQHx2z2Ww6nS7uR33XP378mEqlSB+8Xm9zc/Pa2lqhUEgmk4VCgexfXV19U24peWcPBoPF18JUKlXl5ba+lBQ4eh10jMViR48eVedFghjT1dUljfakGtDqKAiC0+k0Go3JZJIkIRfL4eFhKSdWSgjUQcdgMMhxXHGdSvpUx81Pnz4dOXKkJsaQgWPx0BMDx7KVVVrHfD7vcDg4jise4JftJdMAQRBGRkY6OzsTiUQoFCIDR3LEJ0+eTE1NyTv6hw8fDh06JJktCEJvby8ZBoyNjb19+1Ze2t3dSmkdeZ43GAwcxxUP8OuLmHSpubk5Ho9brVatVhuJRERRXFxcvHbtmuwxLnkT6O/vJx+rZ2ZmtFqtxWLhed7tdn/9+rW+Z63OoyutI7lmSCVXA5R8Pn/79u2Lv5ZAIHDr1q329naXy2Wz2RKJhLwekoFjQ0ODTqfr6emx2+1ut/vVq1d6vf7SpUvPnj2Tl3bXt1JIx4WFhVAo5PV6L168yHHcwYMHnU7nzZs3Hz9+LPvyU8PaCIKQTCZJT8h6MpmUbhbKOJA0cMxkMjzPS+eYTqe/f/8uI+EeaaKQjpcvX25qajpx4oRGo+E4TqfTkbkKNpttY2Nj97EmbwLqGZD8K4QV0pHgINcMqoFjPB73eDw36ZdAIFDH2Q8ldxz/FRvq3k9FdQyHw42NjVQDx5WVFa/XW4mNXq83FApJN6rn5+dlf7lXfVXcbrc672RVf2pMMyiqo5rvONaWMpmrVtuceyGbcjpKdxx7e3ur+ZRQ86pwdVpqfiK7IKFyOsoYOO4CvjgFKgLK6Shj4Eh1JgjeBQSU0/HvgWMymQyHwzt/4CCzvGS8nZ49e1aapMOiTplM5v3799Inpzdv3qytrbE40J7KqZCO0sBR+qpaEASfzyd9h7Yd9EKh8PdPWP78QcvWW9Kd5+0yV7N/aWnJaDTa7faOjg6NRnPlyhWPx4M53tUgJW0V0jGdTlssFo7jpCkFi4uLRqPxy5cv1Z+DwhkSiYTZbJ6enibTyK1WK+ZD1KoECumYz+evX7/Ocdzg4KAoitFo9PTp0xMTE7U6DSXzjI6OWq3WTCYjiiJ5mUHHWvFXSEdRFJeWlpqamjQazbFjx/R6/bt371R1u6dyoC6Xi7yoRFFcWVkxmUyfP3+uvDkidyCgnI6iKOZyudivpY5f3+3AosKnvF4vGXIIgvDo0SOfz/ePvq4qPF8lwxTVUckTY3es1dXV7u7uYDDY398/NDT0T7+02FGSlxk6yuFGftUFEeWw27ENdNwRD55UlgB0LMNbxh14qUmZ1Hj6LwLQ8S8k2FE/AtCxWvb37t07ts1Sbeq91x46Vlvzw4cPV5sC7TcJQMdNErIeX758eefOHVlN0WgLAtBxCyiV7zp16lTlwYgsSwA6lkW0bcD4+Pjdu3e3fRpP0BOAjvTMNlucOXOGTGNLp9NDQ0NjY2PZbHZyctLj8YRCIdwk3+RE8QgdKWAVh05MTNy4cYPsGR8fn5ub6+zsPH/+fDQaTaVS586dk/3nPsVH2Wvr0LGiivt8vhcvXhSHtrW1ffv2jUx5DAQCy8vLLS0tc3NzoiiSf+XDrLNiXBWuQ8fyoNra2gwGg9FolEKnp6edTqe0KYri7Oys2Wwmf+UYiUROnjyJyeHFfCpch47lQY2MjDx//pzjuMnJSRJtsVhK/oLs4cOH0u8uhoeHHQ5HJpP58eNH+eyIKCIAHYtg7Lh6/Pjx9vZ2URQXFhb6+vqKY7PZbFdXF/lHHjI/PBQKzf5aisOwXpYAdCyL6HeA3+/ft29fLBaz2Wwll8b19XWz2Uz+FTKbzfb09Dx48GBwcBAfriuFuxkHHTdJVPCo1+uvXr3q8XhKYgVBSKfT0pzwQqGQSqWkzZJgbO5AADruAKf0qadPnx44cKDk0lgahO0qCEBHOnjd3d10DRBNQwA60tBCLGMC0JExYKSnIQAdaWghljEB6MgYMNLTEICONLQQy5gAdGQMGOlpCEBHGlqIZUwAOjIGjPQ0BKAjDS3EMiYAHRkDRnoaAtCRhhZiGROAjowBIz0NAehIQwuxjAlAR8aAkZ6GAHSkoYVYxgSgI2PASE9DADrS0EIsYwLQkTFgpKchAB1paCGWMQHoyBgw0tMQgI40tBDLmAB0ZAwY6WkIQEcaWohlTAA6MgaM9DQEoCMNLcQyJgAdGQNGehoC0JGGFmIZE4COjAEjPQ0B6EhDC7GMCUBHxoCRnoYAdKShhVjGBKAjY8BIT0Pgf2gQ/wVxPD+9AAAAAElFTkSuQmCC)

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
![t test.PNG](data:image/png;base64,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)

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
