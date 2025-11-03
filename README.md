# RedNote Landing Lift A/B Test

## Project Overview

RedNote places great emphasis on its landing page design and aims to improve conversion rates through design enhancements. Based on historical data, the previous conversion rate was around **12%**, and the company hoped that the new design could achieve a **3% increase**, reaching **15%**. Before officially launching the new page, an A/B test was conducted on a small group of users to ensure that the desired improvement could be achieved.

## Methodology

### Key Metrics

* **P_A**: Observed conversion rate for the control group
* **P_B**: Observed conversion rate for the experimental group

### Sample Size Calculation

The minimum sample size per group was determined using standard formulas for A/B testing, resulting in **2,031 users per group**. Therefore, the total required sample size was **4,062 users**.

### Test Duration

Assuming the website’s average number of visits is **1,000 per day**, the minimum duration of the experiment was calculated to be **5 days** to ensure sufficient statistical power.

### Hypothesis Testing

* **Null hypothesis (H0):** There is no real difference between the two groups.
* **Alternative hypothesis (H1):** There is a true difference between the two groups.

A p-value was calculated to assess whether the observed change (0.5% decrease) was due to random chance or a meaningful effect.

## Results

* **P-value:** 0.63 (greater than the significance level), therefore the null hypothesis cannot be rejected.
* **Confidence interval (treatment group):** [0.104, 0.132]

  * Includes the baseline conversion rate of 12%
  * Does not include the target conversion rate of 15%

These results indicate that the new landing page design is unlikely to improve conversion rates and does not meet the expected target. The true conversion rate is likely similar to the baseline, demonstrating that the redesign is not a significant improvement.

## Conclusion

The A/B test shows that the new landing page design fails to achieve the desired increase in conversion rate. No statistically significant improvement was observed, suggesting that further design changes or alternative strategies may be required to reach the 15% target.
