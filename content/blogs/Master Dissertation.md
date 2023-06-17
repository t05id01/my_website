---
categories:
- ""
- ""
date: "2017-10-31T21:28:43-05:00"
description: ""
draft: false
image: 
keywords: ""
slug: Masters_Dissertation
title: Masters Dissertation
---

# An Analysis of Risk-Neutral density's Moments for USD/BRL options with applications to trading

Between 2017 and 2019 I completed a Masters in Financial Engineering by Funcadao Getulio Vargas in Sao Paulo, Brazil, and in order to complete the course and receive the Diploma, I presented my Dissertation thesis to a group of judge.

For this work I decided to focus on the study of how to translate Foreign Exchange (in this case, the Brazilian Real) options and their implied volatilities into probability density functions (PDFs) where one could assess the probabilities associated with different outcomes. I performed a study on the different Moments of these distribution functions, building a trading strategy to profit from the informational content of these Moments.

I spent over 9 months preparing this work and it was a very rewarding exercise which I'm proud of the result. I was able to deep-dive into the study of financial securities, trading strategies, and substantially developed my coding skills in the meantime (for this work, I used mostly Matlab). Below is a summary with the Abstract and main conclusions of the work.

*Abstract*

"The present work proposes an application of a non-parametric methodology to extract the risk-neutral probability density function (RND) to USD/BRL options. This methodology consists in complementing the RND extracted from the implied volatility smile with tails drawn from a GEV (generalized extreme value) distribution. These non-parametric risk-neutral densities are compared to parametric distributions that are frequently mentioned in the literature - specifically, the mixture of log-normal densities (MLN) and the generalized beta of second kind (GB2) - through a study of their moments. The present work proposes a straightforward methodology to apply the estimated moments for trading of USD/BRL futures, finding strategies that produce greater returns relative to a simple buy and hold strategy."

*Sample comparison of the extraction of risk-neutral densities (RNDs) of FX options under 3 different methodologies* ![RND Sample](https://github.com/t05id01/my_website/blob/main/content/blogs/rnd_comparison.jpg?raw=true)

*Sample cumulative performance of trading strategies that use signals extracted from different Moments (skewness and variance, respectively) to trade USD/BRL futues* ![RND Sample](https://github.com/t05id01/my_website/blob/main/content/blogs/rnd_performance.jpg?raw=true)

*Main Conclusions of the work*

-   We were able to build simple strategies that outperformed the buy-and-hold strategy during the period analysed (2014-2019). The parametric frameworks (in particular, the GB2) had, on average, a higher total return than the non-parametric one. This is likely related to the instability of the non-parametric moments

-   For the purpose of trading based on the model described in this work, the greater stability of parametric approaches more than compensated the drawbacks from assuming a particular functional form for the density function. In this sense, the RNDs estimated using the GB2 framework appeared to strike a balance between a fairly similar shape to their non-parametric equivalents, and a stability similar to the MLN


