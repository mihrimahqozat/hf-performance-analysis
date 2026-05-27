# hf-performance-analysis
A Python analysis of five hedge fund strategies using real market data: Long/Short Equity, Global Macro, Market Neutral, Momentum, Risk Parity. 

## Key Findings
- **Long/Short Equity achieved the highest Sharpe
  ratio (0.71)** — marginally outperforming the
  S&P 500 (0.69) at less than half the volatility
  (8.71% vs 17.70%), delivering the core hedge
  fund value proposition of superior risk-adjusted
  returns with lower drawdown (-18.46% vs -33.72%)
- **Global Macro generated the highest alpha
  (+7.72% annualized)** with near-zero market
  correlation (-0.31) and negative beta (-0.181),
  making it the most valuable portfolio diversifier
  despite its lower absolute return (5.17%)
- **The S&P 500 won on raw return (14.07%)** —
  none of the hedge strategies matched it on
  absolute terms during one of the strongest
  U.S. equity decades in history, validating
  the passive investing challenge for active managers
- **Market Neutral failed its core mandate** —
  delivering -2.13% annualized return due to
  structural short exposure against large-cap
  tech, the strongest-performing equity segment
  of the decade, despite successfully achieving
  near-zero beta (0.054)
- **S&P 500 CVaR of -2.74% daily** is more than
  double Long/Short Equity's -1.29% — confirming
  hedge strategies provide significantly better
  tail risk protection critical for institutional
  allocators with liability constraints
- **All positive-return strategies achieved
  53-55% win rates** — confirming that even
  well-constructed active strategies win only
  slightly more than half the time, reflecting
  the statistical difficulty of generating
  consistent alpha
- **Global Macro's R-squared of 0.095** confirms
  its returns are 90.5% unexplained by equity
  market movement — the highest diversification
  purity of any strategy and the primary
  justification for its inclusion in
  multi-asset institutional portfolios
- **Momentum's 0.71 S&P 500 correlation** is
  the highest among hedge strategies, limiting
  its diversification benefit and explaining
  its vulnerability to sharp market reversals
  when momentum factors suffer crowded unwinds
