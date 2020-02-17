Best Approach - Ensemble Model of XGBoost with CatBoost.

CatBoost was used with the same features as Day 1, and then parameter tuned. These results from Catboost were merged together with the results from XGboost (best model from day 1), in excel using the "OR" Logical Gate.

(1 - Default, 0 - NoDefault)
1 + 1 = 1
1 + 0 = 1
0 + 1 = 1
0 + 0 = 0


Selected features: the 18 PAY_*, DUE_*, PAID_* variables.