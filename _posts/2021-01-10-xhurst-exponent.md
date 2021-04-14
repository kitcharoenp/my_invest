---
layout : post
title : "Hurst Exponent"
category: [terms]
---
**Mean-reverting** time series have long been a fruitful playground for quantitative traders.
mean reversion of financial time series such as artificially constructed spreads, which are used in pairs trading.

Ernie talks about several tools that can be used when testing if a time series is mean reverting. One is the **Augmented Dickey-Fuller test** for mean reversion. Ernie also goes into some detail about the **Johansen test**.

The idea behind the Hurst Exponent H is that it can supposedly help us determine whether a time series is a random walk (H ~ 0.5), trending (H > 0.5) or mean reverting (H < 0.5) for a specific period of time.

However, if you’ve ever used Hurst, you know that it can be a bit bewildering: not only does it often give unexpected results, but it also returns different results depending on the implementation used in its calculation. Further, there are a few different methods for calculating Hurst; we found that these generally agree for a randomly generated time series, but disagree when we use real data.

[1]: https://robotwealth.com/demystifying-the-hurst-exponent-part-1/ "Hurst Exponent for Algorithmic Trading"

[2]: https://robotwealth.com/demystifying-the-hurst-exponent-part-2/ "Hurst Exponent for Algorithmic Trading"

[id]: https://www.codespeedy.com/hurst-exponent-in-python/ "hurst-exponent-in-python"

https://www.quantstart.com/articles/Basics-of-Statistical-Mean-Reversion-Testing/

http://epchan.blogspot.com/2016/04/mean-reversion-momentum-and-volatility.html

https://www.financialwisdomforum.org/gummy-stuff/hurst.htm
