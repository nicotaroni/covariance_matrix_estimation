# Covariance matrix estimation for large financial dataset

The aim of this project is to show empirically the
importance of covariance filtering in the prediction of the risk
of a portfolio. To this extent, we compare the out-of-sample risk
of the Global Minimum Variance Portfolio. We first compute
it naively and then with each of the following methods: eigen
values clipping, Rotationally Invariant Estimators (RIE), Average
Oracle (AO) and Bootstrap Average linkage Hierarchical Clustering (BAHC). We analyze also the Optimal Mean-Variance
portfolio performance for each of the mentioned techniques.

The dataset that we use for the analysis consists of daily
close-to-close return observation of the US equity markets
data for 42 years: from 01-01-1980 to 31-03-2022. We select
the 1135 stocks with the largest market capitalization using
WRDS. Therefore, in total, we have 5598 rows and 1135
columns.
