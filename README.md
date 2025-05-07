# Practical Application 1: Coupon Acceptance Analysis

This project analyzes customer responses to driving coupons sourced from a UCI/MTurk survey.
You can view data exploration in the [analysis notebook](submission_Romin_Parekh.ipynb).

## Summary of Findings
- **Overall Patterns**:
  - Coffee House and less expensive restaurant coupons show the highest acceptance rates.
  - Evening offers (6PM) underperform compared to morning (10AM) and afternoon (2PM) coupons.

- **Coffee House Group**:
  - Acceptance rate: 49.92%.
  - Solo passengers are more likely to redeem coupons than those with companions.
  - 2-hour expiration coupons drive faster redemptions vs 1-day expiration.

## Recommendations
1. **Segmented Targeting**: Prioritize Coffee House and under-$20 restaurant coupons for promotions.
2. **Time-Based Campaigns**: Focus on morning and afternoon time slots for higher conversions.
3. **Passenger Context**: Offer engagement incentives for group passengers.
4. **Expiration Strategy**: Utilize shorter validity windows to encourage prompt actions.

## Next Steps
- Develop a logistic regression or tree-based model to quantify feature impacts.
- Incorporate geospatial and direction alignment metrics.
- A/B test expiration durations across key user segments.

