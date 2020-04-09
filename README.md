# Stata-Check the outliers with Value-at-Risk (VaR) models
## Thesis: Testing VaR models on long-run Sovereign bond data
..*In the face of current chaos in finance, risk management is an urgent requirement in controlling losses. This thesis shed light on testing VaR model on monthly Sovereign bond data over 200 years. The main contents compare performance of one-day prediction of 25 selected portfolios via three methods – Historical Simulation (Engle and Manganelli (2001)), GARCH(1,1) (Robert Eagle (1982)) and Expected Shortfall (Artzner et al. (1997)). Remarkably, performance is evaluated by Kupiec test, Independence test and Conditional Coverage test, named shortly as Back-testing. After testing, Historical Simulation and Expected Shortfall of Historical Simulation are most effective. Besides, Normal GARCH(1,1) and ES Normal GARCH(1,1) are also potential. However, a persistent model applied throughout time should be carefully considered, especially in crisis. As regards GARCH(1,1), tested normal distribution works surprisingly better than Student-t. Last but not least, 1% percentile is more effective than 5% percentile in most approaches.

**Keywords:** Value-at-Risk; Sovereign bond; long-run; Historical Simulation; GARCH(1,1); Expected Shortfall; Back-testing

**Support:** risk management, portfolio optimization

### Data source: 
.Meyer et. al (2018) with project "200 years of Sovereign Haircuts and Bond Returns", limit 25 single portfolios including 24 countries and 1 global portfolio.
.Excel and Stata files contain the bondId (ID), Name, Country (c), issue date (issuey), maturity date (maturityy), monthly return (rmdreal)
