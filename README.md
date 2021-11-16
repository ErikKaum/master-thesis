# Demand estimation with double/debiased machine learning: a comparison to traditional methods
**Author**: Erik Kaunismäki


**Thesis Supervisor**: Ari Hyytinen


**Grade**: overall: 4/5, choice of research method: 5/5

## Abstract:
The thesis explores how recent advances in econometric methodology can be used for estimating demand
and price elasticities of demand. Traditional econometric methods perform poorly when the number of
variables is large proportional to the number of observations, usually leaving variable selection on
the researcher’s judgement. New advances, incorporating machine learning methods in econometric
methods, provide a data driven variable selection procedure and are able to deal with sparse data
sets.

Using a data set with rich product descriptions from a Finnish retail firm, the double machine
learning (DML) methodology by [Chernozhukov et al. (2018)](https://academic.oup.com/ectj/article/21/1/C1/5056401?login=true) is used to estimate the own price
elasticity of demand. The results are furthermore compared to the estimates from traditional
econometric methods. The formulation of the demand model follows as closely as possible the one laid
out in Chernozhukov et al. (2017), where DML is used to estimate price elasticity of everyday retail
goods.

Interestingly, the estimates of price elasticity obtained with DML differ little to those of
traditional methods, which is similar to the findings in Chernozhukov et al. (2018). The results
also highlight the importance of choosing the correct method as the first stage estimator and
configuring it properly. Furthermore, only a few of the product characteristics are crucial for
demand estimation. It is unclear whether this is due to product characteristics actually not
affecting price elasticity or due to potential biases in how product characteristics are recorded.
