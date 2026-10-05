---
aliases:
  - OR
---
## Definition
Ratio of the [[Odds]] of event A taking place in the presence of B, and the odds of A in the absence of B.

## Formula
Using a disease example:

|                 | Disease (D) | Healthy (H) |
| --------------- | ----------- | ----------- |
| Exposed (E)     | ED          | EH          |
| Not Exposed (N) | ND          | NH          |
$$
OR = \frac{ED / EH}{ND / NH}
$$

## Interpretation
- OR = 1
	- No relationship between exposure and event occurring
- OR > 1
	- Exposure increases risk of event occurring
- OR < 1
	- Exposure decreases risk of event occurring

Magnitude is the strength of the relationship.

If [[p-value]] is NOT less than significance goal or if [[Confidence Interval]] contains 1.0, then RR is NOT statistically significant, regardless of RR magnitude.