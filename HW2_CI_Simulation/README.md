# Confidence Interval Coverage Simulation

This project investigates how often confidence intervals (CIs) for the population mean actually contain the true mean. Through repeated sampling and simulation, we measure the coverage rate for different confidence levels and sample sizes.

---

## 🎯 Objectives

- Simulate repeated random samples from a normal distribution.
- Construct confidence intervals for each sample.
- Determine whether each CI contains the true mean.
- Estimate the empirical coverage rate across simulations.
- Compare results across varying:
  - Sample sizes  
  - Confidence levels

---

## 📊 Method Summary

For each simulation:

1. Generate a random sample from the distribution  
   **N(μ = 50, σ = 10)**.
2. Compute the sample mean **x̄**.
3. Construct the confidence interval:


4. Check whether the interval contains the true mean **μ = 50**.
5. Repeat **5000** times.

---

## 📈 Results

- Empirical coverage rate for the **95% confidence interval**:

**4752 / 5000 = 0.9504**

- As sample size increases:
- Standard error decreases  
- Confidence intervals become narrower  
- Coverage rates converge to theoretical values

- Higher confidence levels (e.g., 99%) produce wider intervals, resulting in higher coverage probability.

---

## 📉 Visualization

A coverage plot is generated showing:

- Coverage rate vs. sample size  
- Separate curves for 90%, 95%, and 99% confidence levels  
- A horizontal reference line at the nominal 95% level  

This provides a clear comparison of empirical coverage behavior.
