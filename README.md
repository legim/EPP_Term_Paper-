# Student Project: Replication of Marco Leonardi (2015)

>This repository constains my repliacation of following article :
[Marco Leonardi,University of Milan (2015)](https://www.aeaweb.org/articles?id=10.1257/app.20130359)
Leonardi, Marco. 2015. "The Effect of Product Demand on Inequality: Evidence from the United States and the United Kingdom." American Economic Journal: Applied Economics, 7 (3): 221-47.

## Marco Leonardi (2015)
Using Consumer Expenditure Survey data the author in this paper shows that more educated workers demand more high-skill-intensive services (such as education services, medical, and professional services) and, to a lower extent, more very low-skill-intensive services (such as personal services). The positive (and J-shaped) relationship between the education (and income) elasticities and the skill-intensity of consumption goods and services is evident in the United States. The parametrization of a simple two-sector model suggests that overall the income and education effects in favor of skill-intensive goods and services can explain around 6.5 percent of the total increase in the college premium in the United States from 1984 to 2002.

- The original data provided by the author can be found [here](https://www.openicpsr.org/openicpsr/project/113590/version/V1/view).

## Replication
 This repository contains the replication of the main results of the evidence from the United States.

The right sequence of files to run to replicate the US results:

 - Data cleaning file [here](https://github.com/legim/EPP_Term_Paper-/blob/991d468b7ef43805df9b95f2b05441a23ce44356/files/skillintensityUS.ipynb)
 - Estimates of Education and Income Elasticities [(Table 1)](https://github.com/legim/EPP_Term_Paper-/blob/991d468b7ef43805df9b95f2b05441a23ce44356/files/figure1_table1-2.ipynb)
 - Plot of education elasticities against skill intensity, together with a linear and a quadratic fit obtained by a OLS regression weighted by the mean expenditure share of each consumption item (a measure of the importance of the item in the household budget) [(Figure 1)](https://github.com/legim/EPP_Term_Paper-/blob/991d468b7ef43805df9b95f2b05441a23ce44356/files/figure1_table1-2.ipynb)
 - Results of the linear weighted regression of estimated education and income elasticities on two measures of skill intensity [(Table 2)](https://github.com/legim/EPP_Term_Paper-/blob/991d468b7ef43805df9b95f2b05441a23ce44356/files/figure1_table1-2.ipynb)
 - Table of education elasticities by family type [(Table 3 Panel A)](https://github.com/legim/EPP_Term_Paper-/blob/991d468b7ef43805df9b95f2b05441a23ce44356/files/table3_panelA.ipynb)
 - Table of education elasticities estimated over time [(Table 3 Panel B)](https://github.com/legim/EPP_Term_Paper-/blob/991d468b7ef43805df9b95f2b05441a23ce44356/files/table3_panelB.ipynb)
 - Calculations to quantify overall income and education effects: parameters of the model [(Table 5)](https://github.com/legim/EPP_Term_Paper-/blob/991d468b7ef43805df9b95f2b05441a23ce44356/files/table5.ipynb) and quantification of the income and education effects [(Table 6)](https://github.com/legim/EPP_Term_Paper-/blob/991d468b7ef43805df9b95f2b05441a23ce44356/files/Table6.ipynb)

## .zip files
 - Please, extract files from the 1data.zip and 2data.zip files to the data folder
 - Please, extract files from the 1files.zip, 2files.zip, 3files.zip files to the files folder
