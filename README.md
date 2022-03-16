# ABTesting

## Lesson 1
* What cannot be tested? 
  * new features (need time)
  * which mountain to climb
* Success/Failure trails - binominal dist
* Substantive/Practically significnat - use experience
  * alpha - false reject
  * beta - false accept (1-beta: power/sensitivity)
  * low N (small alpha, high beta), increase N (same alpha, lower beta)

## Lesson 2 Ethetics Principle

## Lesson 3 Choose Metrics

**Choose Metrics : sensitivity and robustness (to outlier / other unchanged)**
1. compare metrics: abs, rel, MFF
2. compute variance
  a. analytical may underestimate
  b. empirical: A/A test; bootstrap from a big A/A test

* the use of A/A test
  * sanity check - compare results to expectation
  * estimate variance
  * estimate CI
* filter and segment
  * check data quality
  * for sensitivity and robustness

## Lesson 4 Experiment Design

* Choose subject - unit of diversion
  * Prop: consistency; ethical (user consent); variability (need unit of analysis = unit of diversion)
* Choose population
  * Intra vs. Inter-user
  * larger target population may dilute the significant results
  * cohort - if need user stability
* Size
  * be consevative
  * SE ~ N^-1/2
* Duration
  * how long, when, which traffic (safe/ price/ cost)
  * learning effect need longer : use pre/post A/A to reduce other effect
 
