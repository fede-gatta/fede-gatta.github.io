---
layout: page
title: Risk Measures
permalink: /papers/risk-measures/
---

## Risk Measures

<div class="paper-item">
  <h3>A high-frequency approach to Realized Risk Measures (2025)</h3>
  <p class="authors">Federico Gatta</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> We propose a new approach, termed Realized Risk Measures (RRM), to estimate Value-at-Risk (VaR) and Expected Shortfall (ES) using high-frequency financial data. It extends the Realized Quantile (RQ) approach proposed by Dimitriadis and Halbleib (2022) by lifting the assumption of return self-similarity, which displays some limitations in describing empirical data. More specifically, as the RQ, the RRM method transforms intra-day returns in intrinsic time using a subordinator process, in order to capture the inhomogeneity of trading activity and/or volatility clustering. Then, microstructural effects resulting in non-zero autocorrelation are filtered out using a suitable moving average process. Finally, a fat-tailed distribution is fitted on the cleaned intra-day returns. The return distribution at low frequency (daily) is then extrapolated via either a characteristic function approach or Monte Carlo simulations. VaR and ES are estimated as the quantile and the tail mean of the distribution, respectively. The proposed approach is benchmarked against the RQ through several experiments. Extensive numerical simulations and an empirical study on 18 US stocks show the outperformance of our method, both in terms of the in-sample estimated risk measures and in the out-of-sample risk forecasting.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://arxiv.org/abs/2510.16526" target="_blank">[arXiv]</a>
    <a href="https://github.com/fgt996/Realized_Risk_Measures" target="_blank">[GitHub]</a>
  </p>
</div>

<div class="paper-item">
  <h3>CAESar: Conditional Autoregressive Expected Shortfall (2024)</h3>
  <p class="authors">Federico Gatta, Fabrizio Lillo, Piero Mazzarisi</p>
  <p class="journal"><em>SSRN Electronic Journal</em></p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> In financial risk management, Value at Risk (VaR) estimates potential portfolio losses but fails to account for losses beyond a certain threshold. Expected Shortfall (ES) addresses this limitation by providing the conditional expectation of such exceedances, providing a better measure of tail risk. However, ES is not elicitable on its own, meaning that it cannot be estimated by minimizing some scoring function, although its joint elicitability with VaR allows for combined estimation. Building on this property, we propose the Conditional Autoregressive Expected Shortfall (CAESar) model, which flexibly handles dynamic patterns and heteroskedasticity, without making distributional assumptions on price returns. The optimization of CAESar coefficients involves three steps: fitting the VaR component via CAViaR regression, formulating ES as an autoregressive process, and jointly estimating VaR and ES coefficients while ensuring a monotonicity constraint to avoid crossing quantiles. Through extensive backtesting, CAESar outperforms existing methods, proving highly effective for risk forecasting.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://arxiv.org/abs/2407.06619" target="_blank">[arXiv]</a>
    <a href="https://github.com/fgt996/CAESar" target="_blank">[GitHub]</a>
  </p>
</div>
