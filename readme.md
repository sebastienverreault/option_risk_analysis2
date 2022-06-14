# Free Option Risk Analysis

## Intro

In order to realisticaly price an option, one can blindly use the Black–Scholes–Merton formula (BSM) and plug-in numbers,
but understanding the underlying assumptions is of interest and confirming with a second pricing method comes handy in assessing the risk.

Given that Volatility is the most important parameter (no volatility no optionality) in option pricing, understanding its derivation and assumptions is the first step.

Then putting the assumptions in context

Pricing an option using BSM and confirming using Monte Carlo simulation

Pricing an option after changing the assumptions 

Deriving a pricing model for a zero-premium option in order to determine a fee structure for such a transactions.

*For rigourous mathematical treatement refer to [Hull, Options, Futures, and Other Derivatives](https://www.pearson.com/nl/en_NL/higher-education/subject-catalogue/finance/Options-Futures-and-Other-Derivatives-Hull.html)

## Notebooks:

[Historical Volatility](historical_volatility.ipynb) - Topics covered

[Historical Returns Distribution fitting](historical_returns_fit.ipynb) - Some description

[Log Normal At the Money Price Simulation](normal_at_money_simulation.ipynb) - Some description

[Log Normal Out of the Money Price Simulation](normal_out_money_simulation.ipynb) - Some description

[Log Laplacian At the Money Price Simulation](laplacian_at_money_simulation.ipynb) - Some description

[Log Laplacian Out of the Money Price Simulation](laplacian_out_money_simulation.ipynb) - Some description
