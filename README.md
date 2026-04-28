This project scans the cryptocurrency data from several assets and suggesting the optimized portfolio.

Methodologies:

1. The scanning process uses XGB because it is not computationally heavy (compared to neural network) and from several
   researches, they claim that it is compatible for cryptocurrency market.

2. The portfolio is then built using modified Markowitz's MPT, by adding several constraints such as equation constraints
   and the confidence level constraints from the scanning process. These constraints is expected to reduce noises.

Disclaimer: this code is not a financial advise. Do your own research before entering the market.
