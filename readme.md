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

[Historical Volatility](historical_volatility.ipynb) - Some description

[Historical Returns Distribution fitting](historical_returns_fit.ipynb) - Some description

[Normal At the Money Price Simulation](normal_at_money_simulation.ipynb) - Some description

[Normal Out of the Money Price Simulation](normal_out_money_simulation.ipynb) - Some description

[Laplace Out of the Money Price Simulation](laplace_out_money_simulation.ipynb) - Some description

[Student's t Out of the Money Price Simulation](student_t_out_money_simulation.ipynb) - Some description

[Profit and Loss Bootstrap Simulation (in trending down sample)](pnl_bootstrap_down_simulation.ipynb) - Some description

[Profit and Loss Bootstrap Simulation (in trending sideways sample)](pnl_bootstrap_sideways_simulation.ipynb) - Some description

[Profit and Loss Bootstrap Simulation (in trending up sample)](pnl_bootstrap_up_simulation.ipynb) - Some description

[Profit and Loss Historical Simulation](pnl_historical_simulation.ipynb) - Some description

[Empirical Value at Risk (VaR) and Conditional Value at Risk (CVaR)](historical_var.ipynb) - Some description
