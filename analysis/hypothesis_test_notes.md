Hypothesis Test Notes
Primary Metric

Paid Conversion Rate

This metric was selected because the primary business objective of the experiment is to determine whether the new treatment increases the number of users who become paid customers.

Null Hypothesis (H₀)

There is no statistically significant difference in the paid conversion rate between the Control group and the Treatment group.

H₀: Paid Conversion Rate (Treatment) = Paid Conversion Rate (Control)

Alternative Hypothesis (H₁)

The Treatment group has a higher paid conversion rate than the Control group.

H₁: Paid Conversion Rate (Treatment) > Paid Conversion Rate (Control)

Type of Test

One-tailed hypothesis test

A one-tailed test is appropriate because the business objective is specifically to determine whether the Treatment improves conversion rather than simply being different.

Significance Level

α = 0.05 (5%)

Decision Rule:

If p-value < 0.05, reject the null hypothesis.
If p-value ≥ 0.05, fail to reject the null hypothesis.
Statistical Test

A Two-Proportion Z-Test (or an equivalent A/B test for binary outcomes) is used because Paid Conversion is a binary outcome (Converted / Not Converted).

Inputs:

Number of users in Control group
Number of users in Treatment group
Number of paid conversions in each group
Test Output

The statistical test compares the paid conversion rates of the two experiment groups.

The output should include:

Conversion rate (Control)
Conversion rate (Treatment)
Test statistic (Z-score)
P-value
Decision Logic

If the calculated p-value is less than 0.05:

Reject the null hypothesis.
Conclude that the Treatment produces a statistically significant improvement in paid conversion.

Otherwise:

Fail to reject the null hypothesis.
Conclude that there is insufficient statistical evidence that the Treatment improves conversion.
Business Interpretation

The hypothesis test helps determine whether any observed increase in paid conversion is likely due to the Treatment rather than random variation.

A statistically significant result provides evidence that the new experience positively impacts user conversion. However, the final business recommendation should not rely solely on conversion improvements. Guardrail metrics such as refund rate, support ticket rate, engagement score, days to convert, and revenue quality should also be evaluated before deciding whether to launch the Treatment.

Conclusion

The experiment outcome will be combined with guardrail metrics and segment-level analysis to decide whether to:

Launch the Treatment for all users,
Launch only for selected user segments,
Continue testing, or
Do not launch.

The final recommendation will be documented in recommendation_memo.md.
