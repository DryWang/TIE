# TIE

Tail Insurance Excess and Stock Returns

The repository contains the tech note on tail insurance excess estimation based on regression quantiles.

I need to address the overlapping observation issue.

The repository also contains the Python code of TIE estimation based on Figlewski (2008) utilising a novel model-free risk-neutral quantile formula.

The advantage of utilising the new formula is to gain extra freedom in selecting interpolants of the implied volatilities, when the objective
is to measure the risk-neutral value-at-risk, expected shortfall, amongst other measures related to the strike/state spectrum.

Based on the new model-free formula, there is no need to explicitly impose conditions on the first and second derivatives which correspond to the 
cdf and pdf such that they are well-behaved. Hence circumventing the 'curse of differentiation'. Preliminary evidence based on S&P 500 index options 
highlights the advantage of having such flexibility.
