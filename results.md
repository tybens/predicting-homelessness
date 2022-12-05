# Results

## Linear Regression:
Avg Train Score:  0.644981178718188
Avg Test Score:  0.5717882605924812
Standard Deviation CV Train Score: 0.013183128940558094
Standard Deviation CV Test Score: 0.07002381599795696

## Ridge Regression
### No Hyperparam Tuning
Avg Train Score:  0.6251584402343848
Avg Test Score:  0.5620623537393563
Standard Deviation CV Train Score: 0.013522049056034532
Standard Deviation CV Test Score: 0.0645711437373577
### Hyperparam Tuning
Avg Train Score:  0.6535736578358892
Avg Test Score:  0.5806035794475914
Standard Deviation CV Train Score: 0.01350611662446059
Standard Deviation CV Test Score: 0.06536988713394644

## Lasso Regression
### No Hyperparam Tuning
Avg Train Score:  0.5373898728580219
Avg Test Score:  0.5027220726376507
Standard Deviation CV Train Score: 0.011890702289973668
Standard Deviation CV Test Score: 0.052634761113487354
### Hyperparam Tuning
Avg Train Score:  0.6286373666235707
Avg Test Score:  0.5649401632614832
Standard Deviation CV Train Score: 0.013441909136011532
Standard Deviation CV Test Score: 0.06467763346551925

## TabNet
Avg Train Score: 0.9241606085710743
Avg Test Score: 0.8285530188444803
Standard Deviation CV Train Score: 0.047241027412387546
Standard Deviation CV Test Score: 0.032062470155568325


# Final Model Evaluations (on hold-out test set):
## LinearRegression
R-Squared Score on Train Set: 0.6401262900682146
R-Squared Score on Test Set: 0.541278673846841
## Ridge (hyperparam tuned)
R-Squared Score on Train Set: 0.6234568630355652
R-Squared Score on Test Set: 0.5377208873470635
## TabNet
R-Squared Score on Train Set: 0.910624771154967
R-Squared Score on Test Set: 0.765996861278735