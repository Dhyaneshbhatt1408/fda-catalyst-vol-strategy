# fda-catalyst-vol-strategy
Event-driven biotech options strategy backtest
# FDA Catalyst Volatility Crush Strategy

An event-driven options research project analyzing whether implied volatility 
around FDA regulatory catalysts (drug approvals, trial readouts) in biotech 
stocks systematically overprices realized price moves.

Built with Python, using real historical price data (Yahoo Finance), live 
options chains, and public FDA data (openFDA API). Includes a risk-managed 
backtest with Kelly-based position sizing and portfolio-level exposure caps.

**Note:** Uses live options data as a proxy for historical options pricing, 
since free data sources don't provide historical options chains.
