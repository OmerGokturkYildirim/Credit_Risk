Imbalanced-learn and scikit-learn libraries are used in this project to build and evaluate models using resampling.

Random Oversampling

Classification Report: Random Oversampling 

                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.74      0.58      0.02      0.66      0.44       101
   low_risk       1.00      0.58      0.74      0.73      0.66      0.42     17104

avg / total       0.99      0.58      0.74      0.73      0.66      0.42     17205




Classification Report: SMOTE Oversampling 							
							
	pre	rec	spe	f1	geo	iba	sup
high_risk	0.01	0.62	0.68	0.02	0.65	0.42	101
low_risk	1	0.68	0.62	0.81	0.65	0.43	17104
avgtotal	0.99	0.68	0.62	0.81	0.65	0.43	17205


SMOTE Oversampling

Classification Report: SMOTE Oversampling 

                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.62      0.68      0.02      0.65      0.42       101
   low_risk       1.00      0.68      0.62      0.81      0.65      0.43     17104

avg / total       0.99      0.68      0.62      0.81      0.65      0.43     17205
