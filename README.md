# tasks_economics
Estimate a modified Keynesian consumption function

Consider the attached dataset.
It has three columns with data on 1,000 households
(every row is one household) in the following order: Income, Consumption and whether
the head of the household is a male (1) or not (0). The task is to estimate the marginal
propensity for consumption (model: cons ~ mpc*income + beta*control variables +
error).

Questions:
1. Load the data in a software of your choice (e.g. R/Stata/python).
2. Create a table with summary statistics for the three variables.
3. Plot an empirical histogram of income. Ensure that the histogram is normalized
properly so that the area under the curve in integrated to 1.
4. Using maximum likelihood (or any other method), fit a Lognormal distribution and
a Gamma distribution to the empirical probability density function of income. Plot
both distributions on top of the raw data. Discuss which one has better fit and
describe based on which metric you would choose the best fit distribution.
5. Estimating MPC: Regress consumption on income and the gender dummy as a
control variable. Discuss the magnitude of estimated MPC in view of the relevant
literature (you may search online and provide at most three important references
PTO

from international journals). Discuss the precision of the estimates.