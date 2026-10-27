# Projects

## 1. [Crash Insurance and the G10 Carry Premium](https://github.com/Amanjeet-S/Crash-Insurance-G10-Carry-Premium)

This study tests the crash-risk explanation for currency carry returns by pricing protective options on a G10 carry portfolio. SABR volatility-smile calibration and hedge-cost decompositions connect insurance prices to realised returns, with inference allowing for serial dependence. The forward-discount spread rose after 2022 while the skew premium for protection remained broadly unchanged. Bounds on option-implied moments also show how conclusions about skewness depend on assumptions beyond the quoted strikes.

[Paper](https://github.com/Amanjeet-S/Crash-Insurance-G10-Carry-Premium/blob/main/paper/Crash_Insurance_and_the_G10_Carry_Premium.pdf) · [Reproduction](https://github.com/Amanjeet-S/Crash-Insurance-G10-Carry-Premium/blob/main/docs/reproducing_paper.md)

## 2. [Option Exercise-Policy Evaluation](https://github.com/Amanjeet-S/Option-Exercise-Policy-Evaluation)

I assess fitted Bermudan exercise policies by separating policy shortfall, martingale slack, numerical integration error and sampling uncertainty. The study compares one-dimensional pricing references with multiasset Monte Carlo benchmarks, including verified conditional integration and independent policy evaluation. Coverage experiments and matched computational comparisons test whether tighter numerical assessments support reliable monetary decisions.

[Paper](https://github.com/Amanjeet-S/Option-Exercise-Policy-Evaluation/blob/main/paper/Assessing_Bermudan_Exercise_Policies.pdf) · [Reproduction](https://github.com/Amanjeet-S/Option-Exercise-Policy-Evaluation/blob/main/docs/reproducing_paper.md)

## 3. [Deep Hedging: An Independent Replication](https://github.com/Amanjeet-S/Deep-Hedging-CVAR95-Replication)

This replication tests whether neural-network hedging reduces tail losses relative to delta hedging, and whether trading the difference between the two hedges meets a published statistical-arbitrage criterion. Networks minimise conditional value at risk (CVaR) under simulated GJR-GARCH volatility; independent test paths and calibration controls assess the resulting hedge. The empirical interval for improvement in 95 per cent CVaR includes zero, and the difference strategy fails the criterion in the retained sample.

[Research note](https://github.com/Amanjeet-S/Deep-Hedging-CVAR95-Replication/blob/main/docs/replication_report.pdf) · [Executed notebook](https://github.com/Amanjeet-S/Deep-Hedging-CVAR95-Replication/blob/main/reproduction.ipynb)

## 4. [Quantum Basket Pricing](https://github.com/Amanjeet-S/Quantum-Basket-Pricing)

The working paper investigates how payoff representation changes the cost of quantum pricing for capped basket derivatives. Gaussian conditioning and certified error bounds support comparisons under matched model, accuracy and confidence requirements, including preparation and arithmetic costs. Across four synthetic contracts, shared-threshold preparation reduces logical T-gate upper bounds by 2.34–10.00 per cent relative to the cheaper of two equally optimised implementations. Companion studies cover PDE pricing, parameter inference and constrained hedging. These results do not establish practical quantum advantage.

[Papers](https://github.com/Amanjeet-S/Quantum-Basket-Pricing/blob/main/paper/README.md)

## 5. [Monetary Tightening and Household Purchases](https://github.com/Amanjeet-S/Monetary-Policy)

Durable purchases can return to their previous rate while leaving a cumulative shortfall. This study tests whether the first-year decline in US durable purchases after monetary tightening is offset over the next two years. Narrative policy shocks and cumulative-response regressions estimate early and later responses jointly, with inference allowing for serial dependence. At the point estimates, later purchases deepen the initial shortfall; longer policy-history controls and leverage adjustment weaken precision.

[Paper](https://github.com/Amanjeet-S/Monetary-Policy/blob/main/paper/monetary_policy.pdf)

## 6. [Investment Memos](https://github.com/Amanjeet-S/Investment-Memos)

These investment cases connect potential mispricing to a specific business mechanism: the credibility of private-market valuations at StepStone and HarbourVest, contract-backed debt repayment at Nakilat, and contractual protection against fleet-value risk at Sixt. Financial-statement analysis and capital-structure modelling inform bear, base and bull valuations. Each memo states the assumptions behind its target price, dated catalysts and evidence that would overturn the thesis.

## 7. [Prices as Eigenvectors](https://github.com/Amanjeet-S/Prices-as-Eigenvectors)

This MATLAB project applies linear algebra and real analysis to Walrasian equilibrium in exchange economies. With Cobb-Douglas preferences, equilibrium market values are the eigenvector of a column-stochastic expenditure matrix, which yields exact rational prices; Newton's method in log prices extends the solution to CES preferences, and the implicit function theorem gives the price response to endowment transfers. Existence is proved for two goods with the intermediate value theorem, while a textbook economy with three equilibria and Scarf's cycling example show where uniqueness and price adjustment fail. Each result is proved or cited and checked by a unit test.

[Proofs](https://github.com/Amanjeet-S/Prices-as-Eigenvectors/blob/main/docs/proofs.md) · [Figures](https://github.com/Amanjeet-S/Prices-as-Eigenvectors/tree/main/results)
