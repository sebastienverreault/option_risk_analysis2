# Free Option Risk Analysis

## Intro

In order to realistically price an option, one can blindly use the Black–Scholes–Merton formula (BSM) and plug-in numbers,
but understanding the underlying assumptions is of interest and confirming with a second pricing method comes handy in assessing the risk.

Given that Volatility is the most important parameter in option pricing (no volatility no optionality), understanding its derivation and assumptions is the first step.

Then putting the assumptions in context

Pricing an option using BSM and confirming it using Monte Carlo simulation

Pricing an option after changing the assumptions 

Deriving pricing models for a zero-premium option in order to determine the viability of the proposition
and a fee structure for such transactions.

Analyzing profit and loss from simulation to confirm price model behaviour

Analyzing profit and loss from historical data

Finally looking into risk measures for quantitative assesment of the expected risk

*For rigourous mathematical treatement refer to [Hull, Options, Futures, and Other Derivatives](https://www.pearson.com/nl/en_NL/higher-education/subject-catalogue/finance/Options-Futures-and-Other-Derivatives-Hull.html)

## Notebooks:

[Historical Volatility](historical_volatility.ipynb) - Derive Volatility from prices

[Historical Returns Distribution fitting](historical_returns_fit.ipynb) - Returns in context

[Normal At the Money Price Simulation](normal_at_money_simulation.ipynb) - Vanilla Option pricing

[Normal Out of the Money Price Simulation](normal_out_money_simulation.ipynb) - Premium-on-Strike Option pricing

[Laplace Out of the Money Price Simulation](laplace_out_money_simulation.ipynb) - Alt. model I Premium-on-Strike Option pricing 

[Student's t Out of the Money Price Simulation](student_t_out_money_simulation.ipynb) - Alt. model II Premium-on-Strike Option pricing 

[Profit and Loss Bootstrap Simulation (in trending down sample)](pnl_bootstrap_down_simulation.ipynb) - PnL Analysis on down trend price

[Profit and Loss Bootstrap Simulation (in trending sideways sample)](pnl_bootstrap_sideways_simulation.ipynb) - PnL Analysis on sideways trend price

[Profit and Loss Bootstrap Simulation (in trending up sample)](pnl_bootstrap_up_simulation.ipynb) - PnL Analysis on up trend price

[Profit and Loss Historical Simulation](pnl_historical_simulation.ipynb) - PnL analysis on 1 year playback of price history

[Empirical Value at Risk (VaR) and Conditional Value at Risk (CVaR)](historical_var.ipynb) - Risk figures on 1 year playback results
