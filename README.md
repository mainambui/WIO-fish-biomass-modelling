# WIO-fish-biomass-modelling
McClanahan TR, Maina JM, Jones K, Graham NAJ (2016) Modeling Reef Fish Biomass, Recovery Potential, and Management Priorities in the Western Indian Ocean PLOSE ONE

In this code:
I model fish biomass response using gamm;:mgcv package;
I run these in model selection framework within MuMIn;
I select the 95% confidence set of models and perform model average;
I then use the model veraged parameter estimates to predict fish biomass over new data (WIO planning units);
Section 2: time to recovery modelling
I fit ricker, asymtpte and logistic functions to fish biomass against age of protection using nls package;
I then apply these time to recovery models to the modelled biomass to spatially predict the time to recovery over WIO reefscape
