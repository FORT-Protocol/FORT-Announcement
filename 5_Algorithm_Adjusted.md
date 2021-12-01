Algorithm for HedgeFutures adjusted.

The sustainability of Fort needs to add an impact cost, which is calculated as follows

1. Calculation formula of impact cost: C = Vol / 1000 / 10000

Where C is the number of DcuS traded

2. The impact cost is only available when buying, but not when selling

When bullish, the initial price is multiplied by (1 + K + C) and the selling price is divided by (1 + k)

When bearish, the initial price is divided by (1 + K + C) and the selling price is multiplied by (1 + k)

When merging, S0 uses the recorded price and S1 uses K to correct

3. The perpetual contract needs to add an impact cost interface, which is planned to be updated to BSC and eth today

FortCore

2021-12-01
