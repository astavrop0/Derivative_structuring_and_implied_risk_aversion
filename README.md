Derivative structuring and implied risk aversion
==============================

This project delves into the design of financial derivatives using a rigorous quantitative structuring framework. The methodology combines Bayesian information processing with rational optimization to align structured products more closely with investors' beliefs and risk preferences. Central to our approach is the payoff elasticity equation, which links payoff structures to risk aversion.

We begin by establishing a theoretical framework that includes the growth-optimizing investor model, maximal payoff of learning, and investor equivalence principles. This foundation allows us to translate investors' market beliefs into tradable payoffs and infer beliefs from existing payoff structures.

Our analysis employs both toy examples and real-world data applications. We demonstrate how quantitative structuring can better reflect shifts in market beliefs regarding expected value, volatility, and skewness compared to traditional ad hoc methods. For real-world data, we focus on the SPDR S&P 500 ETF Trust (SPY) to extract market-implied distributions and construct tailored structured products that align with specific investor profiles.

Additionally, we explore the extraction of risk aversion profiles from existing financial products, such as reverse convertibles. By applying our framework, we conduct an initial approach to identify the risk preferences implied by these products and compare them with the investors' stated beliefs.

Our findings indicate that quantitative structuring can more accurately tailor financial products to meet investors' specific needs. This approach not only enhances the alignment of structured products with investor views but also suggests that traditional products may often be suboptimal. The results underscore the importance of incorporating both market data and individual risk preferences in product design.

Furthermore, we suggest avenues for future research, including refining the choice of prior distributions, improving the practical implementation of the structuring algorithms, and exploring more sophisticated modeling approaches. Our study highlights the potential of quantitative structuring to advance the design of financial derivatives, offering more bespoke and effective investment solutions.



Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project
    │
    ├── data               <- SPY call option data used for the risk-neutral PDF via Breeden-Litzenberger
    │
    ├── notebooks          <- Jupyter notebooks with codes for the toy-examples and the real data applications
    │
    ├── reports            <- Generated analysis as LaTeX report and beamer presentation
    │
    └── requirements.txt   <- The requirements file for reproducing the analysis environment


Resources
------------

[[1]](https://doi.org/10.48550/arXiv.1304.7535) Soklakov A., “Elasticity theory of structuring”, Risk, December (2016), 81-86. arXiv:1304.7535.

[[2]](https://doi.org/10.48550/arXiv.1106.2882) Soklakov A., “Learning, investments and derivatives”, Risk, August (2010), arXiv:1106.2882v1 [q-fin.GN] 15 Jun 2011.

[[3]](https://doi.org/10.1111/j.1540-6261.2004.00637.x) Robert R. Bliss, Nikolaos Panigirtzoglou, “Option-Implied Risk Aversion Estimates”, November (2015), 

[[4]](https://econweb.rutgers.edu/mizrach/pubs/%5B42%5D-2010_Handbook.pdf) Mizrach, B. (2010). Estimating Implied Probabilities from Option Prices and the Underly- ing. In: Lee, CF., Lee, A.C., Lee, J. (eds) Handbook of Quantitative Finance and Risk Management. Springer, Boston, MA.


Contributors
------------

Andreas Stavropoulos ([@astavrop0](https://github.com/astavrop0)), Petros Chatzopoulos ([@w0oDy21](https://github.com/w0oDy21))

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>