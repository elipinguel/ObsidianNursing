---
aliases:
  - RR
  - Risk Ratio
---
## Definition
Probability of an outcome in an exposed group compared to that of an unexposed group.

Measures association between exposure and outcome.

Must be able to calculate incidence in order to calculate.

>[!warning]
>There must be a way to calculate incidence. Otherwise, use [[Odds Ratio]]
## Formula

|                  | Events (E) | Non-Events (N) |
| ---------------- | ---------- | -------------- |
| Intervention (I) | IE         | IN             |
| Control (C)      | CE         | CN             |
$$
RR = \frac{ IE / IE + IN }{ CE / CE + CN }
$$

## Interpretation
- RR = 1
	- No relationship between exposure to intervention and event occurring
- RR > 1
	- Exposure to intervention increases risk of event occurring
- RR < 1
	- Exposure to intervention decreases risk of event occurring

Magnitude is the strength of the relationship.

If [[p-value]] is NOT less than significance goal or if [[Confidence Interval]] contains 1.0, then RR is NOT statistically significant, regardless of RR magnitude.