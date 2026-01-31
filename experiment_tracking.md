1 to 12 of 12 entries
Filter

index	Experiment ID	Model Type	Hyperparameters	Preprocessing Steps	Feature Selection Method	Train/Test Split	Precision	AUC Score	Accuracy
0	EXP-01	Decision Tree	Default (max_depth=None, min_samples_split=2)	None	All features	80/20	0.9861	0.9907	0.9851
1	EXP-02	Decision Tree	max_depth=5, min_samples_split=10	None	All features	80/20	0.9855	0.9993	0.9851
2	EXP-03	Decision Tree	Default (max_depth=None, min_samples_split=2)	None	SelectKBest (k=4): ['bill_length_mm', 'bill_depth_mm', 'flipper_length_mm', 'body_mass_g']	80/20	1.0	1.0	1.0
3	EXP-04	Decision Tree	max_depth=7, min_samples_split=5	StandardScaler	All features	70/30	0.98	0.9843	0.98
4	EXP-05	kNN	n_neighbors=5, weights=uniform	None	All features	80/20	0.8172	0.8781	0.8209
5	EXP-06	kNN	n_neighbors=3, weights=distance	None	All features	80/20	0.8321	0.8938	0.8358
6	EXP-07	kNN	n_neighbors=7, weights=uniform	StandardScaler	All features	80/20	0.9861	1.0	0.9851
7	EXP-08	kNN	n_neighbors=5, weights=distance	StandardScaler	Numerical features only	75/25	0.9884	1.0	0.9881
8	EXP-09	Gaussian Naive Bayes	Default (var_smoothing=1e-09)	None	All features	80/20	1.0	1.0	1.0
9	EXP-10	Gaussian Naive Bayes	var_smoothing=1e-05	None	All features	80/20	0.9855	0.9963	0.9851
10	EXP-11	Gaussian Naive Bayes	Default (var_smoothing=1e-09)	StandardScaler	All features	70/30	0.9153	0.9984	0.84
11	EXP-12	Gaussian Naive Bayes	var_smoothing=1e-07	StandardScaler	Numerical features only	80/20	0.9855	0.9972	0.9851
12      EXP-11  Gaussian Naive Bayes    Default (var_smoothing=1e-09)   StandardScaler  All features    70/30   0.9153  0.9984  0.84
13      EXP-12  Gaussian Naive Bayes    var_smoothing=1e-07     StandardScaler  Numerical features only 80/20   0.9855  0.9972  0.9851
