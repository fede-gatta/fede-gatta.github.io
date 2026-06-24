---
layout: page
title: Machine & Deep Learning
permalink: /papers/ml-dl/
---

<div class="paper-item">
  <h3>ENCODE-Ensemble neural combination for optimal dimensionality encoding in time-series forecasting</h3>
  <p class="authors">Fabio Giampaolo, Federico Gatta, Edoardo Prezioso, Salvatore Cuomo, MengChu Zhou, Giancarlo Fortino, Francesco Piccialli</p>
  <p class="journal"><em>Information Fusion</em> (2023)</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> Nowadays, predictive models based on a time series are widely used in many fields, from geology to healthcare and from traffic management to industrial production. One of the most important tasks in machine and deep learning is designing predictive algorithms that provide increasingly reliable and accurate forecasts from a time series. This work proposes a novel ensemble approach to producing predictions in a multivariate framework. Its main idea is to reduce data dimensionality through an encoding technique, with the aim to extract useful information via single predictive procedures and then to gather all the processed data through a combiner to give the final forecast. In our framework, the combiner is composed of a hybrid neural architecture: a Convolutional Neural Network to extract local patterns from the predictions and a Recurrent Neural Network to infer information about the temporal patterns of the time series. Furthermore, a fully connected network is adopted to merge these two components and to provide the prediction. Extensive experiments on different datasets, both public and private, related to different applications have been carried out. Comparisons of the errors with conventional methods and state-of-the-art strategies confirm both accuracy and robustness of the proposed ensemble. Finally, we also show a comparison in terms of computational time, both in the hyperparameter optimization and forecasting tasks.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://www.sciencedirect.com/science/article/pii/S1566253523002348" target="_blank">[Journal]</a>
  </p>
</div>

<div class="paper-item">
  <h3>Meshless methods for American option pricing through Physics-Informed Neural Networks</h3>
  <p class="authors">Federico Gatta, Vincenzo Schiano Di Cola, Fabio Giampaolo, Francesco Piccialli, Salvatore Cuomo</p>
  <p class="journal"><em>Engineering Analysis with Boundary Elements</em> (2023)</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> Nowadays, Deep Learning is drastically revolutionizing financial research as well as industry. Many methods have been discussed in the last few years, mainly related to option pricing. In fact, traditional approaches such as Monte Carlo simulation or finite difference methods are seriously harmed by multi-dimensional underlying and path dependency. Thus, dealing with particular contracts such as American multi-asset options is still rough. This paper addresses such a problem by pricing said put options with a novel meshless methodology, named Physics-Informed Neural Networks (PINNs), based on Artificial Intelligence. PINN paradigm has been recently introduced in Deep Learning literature. It exploits the theoretical background of the universal approximation theorem for neural networks to solve Partial Differential Equations numerically. This Deep Learning meshless method incorporates the equation and its initial and boundary conditions thanks to a specially designed loss function. We develop a suitable PINN for the proposed problem by introducing an algorithmic trick for improving the convergence of the free boundary problem. Furthermore, the worthiness of the proposal is assessed by several experiments concerned with single and multi-asset options. Finally, a parametric model is built to benefit further studies of option value behaviour related to particular market conditions.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://www.sciencedirect.com/science/article/pii/S0955799723000978" target="_blank">[Journal]</a>
    <a href="https://github.com/fgt996/Meshless-Methods-for-American-Option-Pricing-by-using-Physics-Informed-Neural-Networks" target="_blank">[GitHub]</a>
  </p>
</div>

<div class="paper-item">
  <h3>Statistical arbitrage in the stock markets by the means of multiple time horizons clustering</h3>
  <p class="authors">Federico Gatta, Carmela Iorio, Diletta Chiaro, Fabio Giampaolo, Salvatore Cuomo</p>
  <p class="journal"><em>Neural Computing and Applications</em> (2023)</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> Nowadays, statistical arbitrage is one of the most attractive fields of study for researchers, and its applications are widely used also in the financial industry. In this work, we propose a new approach for statistical arbitrage based on clustering stocks according to their exposition on common risk factors. A linear multifactor model is exploited as theoretical background. The risk factors of such a model are extracted via Principal Component Analysis by looking at different time granularity. Furthermore, they are standardized to be handled by a feature selection technique, namely the Adaptive Lasso, whose aim is to find the factors that strongly drive each stock’s return. The assets are then clustered by using the information provided by the feature selection, and their exposition on each factor is deleted to obtain the statistical arbitrage. Finally, the Sequential Least SQuares Programming is used to determine the optimal weights to construct the portfolio. The proposed methodology is tested on the Italian, German, American, Japanese, Brazilian, and Indian Stock Markets. Its performances, evaluated through a Cross-Validation approach, are compared with three benchmarks to assess the robustness of our strategy.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://link.springer.com/article/10.1007/s00521-023-08313-6" target="_blank">[Journal]</a>
    <a href="https://github.com/fgt996/Clustering4Investment" target="_blank">[GitHub]</a>
  </p>
</div>

<div class="paper-item">
  <h3>Neural networks generative models for time series</h3>
  <p class="authors">Federico Gatta, Fabio Giampaolo, Edoardo Prezioso, Gang Mei, Salvatore Cuomo, Francesco Piccialli</p>
  <p class="journal"><em>Journal of King Saud University - Computer and Information Sciences</em> (2022)</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> Nowadays, time series are a widely-exploited methodology to describe phenomena belonging to different fields. In fact, electrical consumption can be explained, from a data analysis perspective, with a time series, as for healthcare, financial index, air pollution or parking occupancy rate. Applying time series to different areas of interest has contributed to the exponential rise in interest by both practitioners and academics. On the other side, especially regarding static data, a new trend is acquiring even more relevance in the data analysis community, namely neural network generative approaches. Generative approaches aim to generate new, fake samples given a dataset of real data by implicitly learning the probability distribution underlining data. In this way, several tasks can be addressed, such as data augmentation, class imbalance, anomaly detection or privacy. However, even if this topic is relatively well-established in the literature related to static data regarding time series, the debate is still open. This paper contributes to this debate by comparing four neural network-based generative approaches for time series belonging to the state-of-the-art methodologies in literature. The comparison has been carried out on five public and private datasets and on different time granularities, with a total number of 13 experimental scenario. Our work aims to provide a wide overview of the performances of the compared methodologies when working in different conditions like seasonality, strong autoregressive components and long or short sequences.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://www.sciencedirect.com/science/article/pii/S1319157822002361" target="_blank">[Journal]</a>
  </p>
</div>

<div class="paper-item">
  <h3>Predictive maintenance for offshore oil wells by means of deep learning features extraction</h3>
  <p class="authors">Federico Gatta, Fabio Giampaolo, Diletta Chiaro, Francesco Piccialli</p>
  <p class="journal"><em>Expert Systems</em> (2022)</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> Nowadays, the great diffusion of the Internet of Things and the improvements in Artificial Intelligence techniques have given a rise in the development and application of data-driven approaches for Predictive Maintenance to reduce the costs linked to the maintenance of industrial machinery. Due to the wide real-life applications and the strong interest by even more industries, this field is highly attractive for academics and practitioners. So, constructing efficient frameworks to address the Predictive Maintenance problem is an open debate. In this work, we propose a Deep Learning approach for the feature extraction in the offshore oil wells monitoring context, exploiting the public 3 W dataset, which is well-known in the literature. The dataset is made up of about 2000 multivariate time series labelled according to the corresponding functioning of the well. So, there is a classification task with eight classes, each related to a particular machinery condition. Thanks to the peculiarities of the labels, the proposed framework is valid both for diagnostics and prognostics. In more detail, we compare two different approaches in feature extraction. The first is a statistical approach, widely used in the literature related to the considered dataset; the second is based on Convolutional 1D AutoEncoder. The extracted features are then used as input for several Machine Learning algorithms, namely the Random Forest, Nearest Neighbours, Gaussian Naive Bayes and Quadratic Discriminant Analysis. Different experiments on various time horizons prove the worthiness of the Convolutional AutoEncoder.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://onlinelibrary.wiley.com/doi/full/10.1111/exsy.13128" target="_blank">[Journal]</a>
    <a href="https://github.com/fgt996/Predictive-Maintenance-for-Offshore-Oil-Wells-by-Means-of-Deep-Learnin" target="_blank">[GitHub]</a>
  </p>
</div>

<div class="paper-item">
  <h3>An unsupervised learning framework for marketneutral portfolio</h3>
  <p class="authors">Salvatore Cuomo, Federico Gatta, Fabio Giampaolo, Carmela Iorio, Francesco Piccialli</p>
  <p class="journal"><em>Expert Systems with Applications</em> (2021)</p>
  
  <div class="abstract">
    <p><strong>Abstract:</strong> In this paper, we present a portfolio optimization strategy based on a novel approach in assets clustering on the financial background of the Arbitrage Pricing Theory, a well-known multi-factor model. In particular, our aim is to exploit data analysis tools, such as the techniques of features extraction and feature selection, to group assets that exhibit a significant exposition to the same risk factors. Then, we exploit the clustering to build a market-neutral portfolio and, more in general, an investment methodology that takes into account the peculiarities of the specific market. Finally, we apply our methodology in various case studies, discussing the results obtained and highlighting the strengths and the limits of the proposed strategy.</p>
  </div>
  
  <p class="paper-links">
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417421016109" target="_blank">[Journal]</a>
  </p>
</div>
