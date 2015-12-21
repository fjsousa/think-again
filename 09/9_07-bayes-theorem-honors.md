# 9.7 Bayes Theorem Honors

Example: Probability of having cancer given that you tested positive:

- Base rate (or prevalence) of this condition = 0.003

- sensitivity of this test = 0.99 = percentage of cases with the condition that test positive

- specificity = 0.99 = percentage of cases without the condition that test negative

- Solution, or posterior probability = probability that you have the condition given that you tested positive

| | Do have the condition do not have the conditions | totals|
|----|----|-----|-----|
|positive test result| 0.99x300 = 297 |997 |1294|
|negative test result| 3 |0.99 x 99700 = 98703 |98706|
|totals | 1000000x0.003 = 300 |99700 |100000|

Solution = 297/1294 = 0.23

> The base rate is smaller than the false positives in this population...


| | Hypothesis is true = h| Hypothesis is false = ~h | Totals|
|----|----|-----|-----|
|Positive test result = e| Hits or True Positives | False Positives | Positives|
|Negative test result = ~e | False Negatives | True Negatives  | Negatives|
|Totals | Total With the condition |Total without the condition |Population|

- Base rate: Pr(h) = Total with cond / Pop.
- Sensitivity: Pr(e|h) = Hits / Total with cond.
- Specificity: Pr(~e|~h) = True negatives / Total without the cond.
- Solution: Pr(h|e) Hits / Total Positives

Pr(~h|~e) = True Negatives / Total Negatives

## Derivation of Bayes Theorem

- 1) Rule 2G (conjunction): P(e&h) = P(e) x P(h|e)
- 2) Divide both sides by Pr(e): P(h|e) = P(e&h) / P(e)
- 3) Replace e with (e&h)V(e&~h): P(h|e) = P(e&h) / P((e&h)V(e&~h))
- 4) Apply disjunction: Pr(h|e) = P(e&h) / [P(e&h) + P(e&~h)
- 5) Apply rule 2G: P(h|e) = [P(h) x P(e|h)] /[P(h) x P(e|h) + P(~h) x P(e|~h)]
