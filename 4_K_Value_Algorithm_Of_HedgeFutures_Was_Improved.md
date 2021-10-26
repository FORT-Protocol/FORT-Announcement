# The k-value algorithm of HedgeFutures was improved

The k-value algorithm of HedgeFutures is adjusted as follows

	σ = |(S1 - S0) / S1 / T^0.5|
	K = 0.002 * max(σ/σ0, 1) + t^0.5 * max(σ, σ0)
	
Variable description:
	S1 represents current price
	S0 represents previous price
	T represents seconds between S1 and S0
	σ represents real-time volatility
	t represents seconds between S1 to now
	σ0 represents long-term volatility of ETH, which is currently set to 0.00021368
	
FORT Core

2021.10.26
