# The k-value algorithm of HedgeFutures was improved

The k-value algorithm of HedgeFutures is adjusted as follows

	σ = |(S1 - S0) / S1 / T^0.5|
	K = 0.002 * max(σ/σ0, 1) + t^0.5 * max(σ, σ0)
	
Variable description:
1. S1 represents current price
2. S0 represents previous price
3. T represents seconds between S1 and S0
4. σ represents real-time volatility
5. t represents seconds between S1 to now
6. σ0 represents long-term volatility of ETH, which is currently set to 0.00021368
	
FORT Core

2021.10.26
