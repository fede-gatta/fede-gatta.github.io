---
layout: page
title: Decentralized Finance
permalink: /papers/defi/
---

## Decentralized Finance

<div class="paper-item">
  <h3>Deviations from Tradition: Stylized Facts in the Era of DeFi</h3>
  <p class="authors">Daniele Maria Di Nosse, Federico Gatta, Fabrizio Lillo, Sebastian Jaimungal</p>
  <p class="journal"><em>Quantitative Finance</em> (In Press)</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> Decentralized Exchanges (DEXs) are now a significant component of the financial world where billions of dollars are traded daily. Differently from traditional markets, which are typically based on Limit Order Books, DEXs typically work as Automated Market Makers, and, since the implementation of Uniswap v3, feature concentrated liquidity. By investigating the twenty-four most active pools in Uniswap v3 during 2023 and 2024, we empirically study how this structural change in the organization of the markets modifies the well-studied stylized facts of prices, liquidity, and order flow observed in traditional markets. We find a series of new statistical regularities in the distributions and cross-autocorrelation functions of these variables that we are able to associate either with the market structure (e.g., the execution of orders in blocks) or with the intense activity of Maximal Extractable Value searchers, such as Just-in-Time liquidity providers and sandwich attackers.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://arxiv.org/abs/2510.22834" target="_blank">[arXiv]</a>
    <a href="https://github.com/DanieleMDiNosse/Deviations_from_Tradition" target="_blank">[GitHub]</a>
  </p>
</div>

<div class="paper-item">
  <h3>A Multi-step Approach for Minimizing Risk in Decentralized Exchanges</h3>
  <p class="authors">Daniele Maria Di Nosse, Federico Gatta</p>
  <p class="journal"><em>arXiv & SSRN</em> (2024)</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> Decentralized Exchanges are becoming even more predominant in today's finance. Driven by the need to study this phenomenon from an academic perspective, the SIAG/FME Code Quest 2023 was announced. Specifically, participating teams were asked to implement, in Python, the basic functions of an Automated Market Maker and a liquidity provision strategy in an Automated Market Maker to minimize the Conditional Value at Risk, a critical measure of investment risk. As the competition's winning team, we highlight our approach in this work. In particular, as the dependence of the final return on the initial wealth distribution is highly non-linear, we cannot use standard ad-hoc approaches. Additionally, classical minimization techniques would require a significant computational load due to the cost of the target function. For these reasons, we propose a three-step approach. In the first step, the target function is approximated by a Kernel Ridge Regression. Then, the approximating function is minimized. In the final step, the previously discovered minimum is utilized as the starting point for directly optimizing the desired target function. By using this procedure, we can both reduce the computational complexity and increase the accuracy of the solution. Finally, the overall computational load is further reduced thanks to an algorithmic trick concerning the returns simulation and the usage of Cython.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://arxiv.org/abs/2406.07200" target="_blank">[arXiv]</a>
    <a href="https://github.com/DanieleMDiNosse/SIAM_code_challange" target="_blank">[GitHub]</a>
  </p>
</div>

<div class="paper-item">
  <h3>Optimizing Liquidity Provision in Uniswap v3 via Physics-Informed Neural Networks</h3>
  <p class="authors">Salvatore Cuomo, Federico Gatta, Vincenzo Vocca</p>
  <p class="journal"><em>Journal of Computational and Applied Mathematics (2026)</em></p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> Decentralized Exchanges are rapidly changing financial markets by using blockchain technology to eliminate intermediaries. Among others, Uniswap v3 is the most prominent due to the Concentrated Liquidity mechanism, which allows liquidity providers to allocate capital within flexible price ranges, thus increasing possible revenues. This feature brings a key trade-off: narrower ranges increase both potential returns and the risk of inactive liquidity; wider ranges ensure continuous but lower profits. Thus, developing approaches for choosing the optimal liquidity provision range is becoming a predominant task both in the industry and academia. In this work, we propose a novel framework for optimizing liquidity provision in Uniswap v3 using Physics-Informed Neural Networks (PINNs). Our approach models market dynamics through stochastic processes and employs the Feynman-Kac theorem to compute the expected utility associated with the provision position as the solution of a Partial Differential Equation (PDE). This PDE is then solved using PINNs, enabling a fast approximation of expected utility. In such a way, it is possible to efficiently optimize the liquidity allocation in real-time with minimal computational cost. We assess our methodology through numerical experiments, where the backtesting results over eight pools demonstrate its effectiveness in optimizing liquidity provision performance. Thus, our results highlight the potential of the proposed framework for real-world applications.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://www.sciencedirect.com/science/article/pii/S0377042726000348" target="_blank">[Journal]</a>
  </p>
</div>
