# Fraud-Cases-in-Banks

Classification:
- 0 : Not Fraud
- 1 : Fraud


Business Problems

- FP(False Posotif):
    - ML predicts that fraud will occur, even though actually no fraud occurred.
    - If ML predicts that this will happen when in fact fraud does not occur, it will result in service disruptions where a lot of customer funds will be withheld and services will not run properly. and further investigation is needed to prove whether fraud actually occurred
    - It is assumed that the cost of investigating fraud is 5 million rupiah

- FN(False Negatif):
    - ML predicts that fraud will not occur, even though fraud actually occurred.
    - If Ml predicts that fraud will not occur, even though fraud actually occurs. The company will experience large losses due to the fact that fraud occurs
    - It is assumed that the company lost 20 million due to fraud


The cost of losing money due to fraud is greater than the cost of investigating fraud.
In other words, FN costs are greater.
Therefore, the metric used is **Recall**.
