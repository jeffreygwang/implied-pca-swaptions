# Identifying Regime Shifts from Implied PCA

PCA on the yield curve can decompose market rates into interpretable factors, and offer a method to predict pricing of treasuries at different maturities. Here, we use a forward-looking method, "implied PCA," that performs eigendecomposition on a forward-looking covariance matrix constructed with implied volatilities from the swap rate options market. The data for the paper is available here. 

```
methods.ipynb / analysis notebook
data
  fed_data    / bal sheet, ffr, etc. 
  swap_rates  / raw swap rates (sofr/libor)
  swaptions   / swaption vol, swap spread options vol, etc. 
``` 
