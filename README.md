# TargetedMarketing
This repository stores the files of a Machine Learning project using 13 million instances from a randomized control trial collected in two weeks by Criteo's AI Lab.

## Introduction:
- One of the main applications of the Machine Learning models is to improve the Targeted Marketing. The Targeted Marketing is used to select the customers that most likely buy a product.
- There are different approaches for Targeted Marketing such as the Classical modeling (also known as Response model). This approach is focused in training a model with customers that were sent a promotion/offer. The model separates the customers that will buy from the ones that will not buy if targeted. This approach generates higher profit than random selection targeting.
- Nonetheless, the Classical modeling has a flaw. It does not separate customers that will buy even if not targeted from the ones that will only buy if targeted. In other words, the model wastes money by targeting customers that do not need it. The current solution to that issue is the Uplift modeling.
- The Uplift modeling can separate customers that will buy if not targeted from the ones that will buy only if targeted, as well as avoiding customers that will not buy even if targeted. Specifically, the model identifies the customers that are worth spending money on Targeted Marketing.
- This approach can also be related to the Churn problem, in which the goal is to avoid losing customers. It is related because it requires to send an offer to persuade the customer that the product still provide value. Therefore, it is important to send an offer to the customers that are more likely to stay if targeted.
- This notebook elaborates these two approaches for Targeted Marketing using a dataset with 13 million instances provided by Criteo (French advertising company).

## Objective
- To show the Classical and Uplift modeling in Targeted Marketing
