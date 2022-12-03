# Results

## Linear Regression:
Avg Train Score:  0.9398453537143053
Avg Test Score:  0.8426002976101575
Standard Deviation CV Train Score: 0.011969127117745986
Standard Deviation CV Test Score: 0.10974850910315155

## Ridge Regression
### No Hyperparam Tuning
Avg Train Score:  0.9476288828196869
Avg Test Score:  0.8715751601723956
Ridge Standard Deviation CV Train Score: 0.012152442981072036
Ridge Standard Deviation CV Test Score: 0.08427463037368774
### Hyperparam Tuning
Avg Train Score:  0.9509519158769635
Avg Test Score:  0.8747842656723648
Standard Deviation CV Train Score: 0.011257738687760902
Standard Deviation CV Test Score: 0.08697063681238831

## Lasso Regression
### No Hyperparam Tuning
Avg Train Score:  0.9471661883309691
Avg Test Score:  0.8737502970739165
Standard Deviation CV Train Score: 0.01219885157310196
Standard Deviation CV Test Score: 0.08135997576757513
### Hyperparam Tuning
Avg Train Score:  0.9473591938969518
Avg Test Score:  0.8741849805638461
Standard Deviation CV Train Score: 0.01201842174202289
Standard Deviation CV Test Score: 0.08019449002853882

## TabNet
Avg Train Score: 0.9465846991359029
Avg Test Score: 0.9607620380695389
Standard Deviation CV Train Score: 0.024659678866340965
Standard Deviation CV Test Score: 0.01716227597763228


# Final Model Evaluations (on hold-out test set):
## Ridge (no hyperparam)
R-Squared Score on Train Set: 0.9479996831291615
R-Squared Score on Test Set: 0.932044518555256
## TabNet
R-Squared Score on Train Set: 0.9497584106400593
R-Squared Score on Test Set: 0.9582769237437724