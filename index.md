---
layout: page
---

## About Me

I am a PhD candidate in Computational Methods and Mathematical Models for Sciences and Finance at Scuola Normale Superiore. I have a keen interest in real-world problems, particularly at the intersection of Artificial Intelligence and Finance, and my university studies have been dedicated to exploring the dynamic interplay between these two fields. Additionally, I have supplemented my education by independently delving into various topics that pique my intellectual curiosity. In my free time, I practice kickboxing, support the Napoli football club, and enjoy learning about history. When I feel inspired, I like to go for a drive or a bike ride while listening to music. But above all, I love hanging out with friends over a beer.

<hr>

## Research Interest

My research sits at the intersection of risk measures, decentralized finance, market microstructure, and machine learning. Over the years, I have collaborated with a diverse network of colleagues. Following my Master's degree, I served as a research fellow in the Mathematical mOdelling and Data AnaLysis (M.O.D.A.L.) laboratory, where I worked on deep learning approaches for time series analysis. Subsequently, I moved to Pisa to pursue my PhD. During my doctoral studies, I spent time at the University of Toronto as an International Visiting Graduate Student.
Overall, my research can be summarized as follows:

* **Decentralized Finance** Microstructural analysis of the main standards and protocols in this space, with a specific focus on decentralized exchanges.
* **Risk Measures** Development and evaluation of filtering and forecasting approaches for financial risk measures, with a specific focus on Value-at-Risk and Expected Shortfall.
* **Machine and Deep Learning** Research on AI-driven solutions for financial and industrial problems, mainly related to Industry 4.0.

<hr>

## Awards & Achievements

* **Honorable Mention Award - FinteQC**, 2026. My paper "Deviations from Tradition: Stylized Facts in the Era of DeFi" has been awarded an Honorable Mention in the Student Category by the Scientific Committee of the Canadian Conference on Fintech (FinteQC 2026).
* **Winner of the SIAG/FME Code Quest**, 2024. The competition combined two FinTech themes: Decentralized Finance and Automated Asset Management. Over 120 teams from around the world signed up for the competition.
* **Buon Compleanno Federico II Award** for academic excellence, 2020.

<hr>

## Selected Publications

<div class="paper-item">
    <h3>A high-frequency approach to Realized Risk Measures (Working paper)</h3>
    <div class="authors">F. Gatta, F. Lillo, P. Mazzarisi</div>
    <div class="abstract-container">
        <details class="fancy-abstract">
            <summary>View Abstract</summary>
            <div class="abstract-content">
                We propose a new approach, termed Realized Risk Measures (RRM), to estimate Value-at-Risk (VaR) and Expected Shortfall (ES) using high-frequency financial data. It extends the Realized Quantile (RQ) approach proposed in Dimitriadis and Halbleib (2022) by lifting the assumption of return self-similarity, which displays some limitations in describing empirical data. More specifically, as the RQ, the RRM method transforms intra-day returns in intrinsic time using a subordinator process, in order to capture the inhomogeneity of trading activity and/or volatility clustering. Then, microstructural effects resulting in non-zero autocorrelation are filtered out using a suitable moving average process. Finally, a fat-tailed distribution is fitted on the cleaned intra-day returns. The return distribution at low frequency (daily) is then extrapolated via either a characteristic function approach or Monte Carlo simulations. VaR and ES are estimated as the quantile and the tail mean of the distribution, respectively. The proposed approach is benchmarked against the RQ through several experiments. Extensive numerical simulations and an empirical study on 18 US stocks show the outperformance of our method, both in terms of the in-sample estimated risk measures and in the out-of-sample risk forecasting.
            </div>
        </details>
    </div>
</div>

<div class="paper-item">
    <h3>Deviations from Tradition: Stylized Facts in the Era of DeFi</h3>
    <div class="authors">D. M. Di Nosse, F. Gatta, F. Lillo, S. Jaimungal <br> <span style="font-size: 0.9em; color: #777;"><em>Quantitative Finance</em> (In Press)</span></div>
    <div class="abstract-container">
        <details class="fancy-abstract">
            <summary>View Abstract</summary>
            <div class="abstract-content">
                Decentralized Exchanges (DEXs) are now a significant component of the financial world where billions of dollars are traded daily. Differently from traditional markets, which are typically based on Limit Order Books, DEXs typically work as Automated Market Makers, and, since the implementation of Uniswap v3, feature concentrated liquidity. By investigating the twenty-four most active pools in Uniswap v3 during 2023 and 2024, we empirically study how this structural change in the organization of the markets modifies the well-studied stylized facts of prices, liquidity, and order flow observed in traditional markets. We find a series of new statistical regularities in the distributions and cross-autocorrelation functions of these variables that we are able to associate either with the market structure (e.g., the execution of orders in blocks) or with the intense activity of Maximal Extractable Value searchers, such as Just-in-Time liquidity providers and sandwich attackers.
            </div>
        </details>
    </div>
</div>

<hr>

## My Word Cloud

<div style="text-align: center; margin-top: 2rem;">
  <img src="{{ '/assets/img/wordcloud.jpg' | relative_url }}" alt="My Word Cloud" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
</div>
