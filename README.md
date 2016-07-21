# WIO-fish-biomass-modelling
McClanahan TR, Maina JM, Jones K, Graham NAJ (2016) Modeling Reef Fish Biomass, Recovery Potential, and Management Priorities in the Western Indian Ocean PLOSE ONE

In this code:
Part 1
I model fish biomass response using gamm::mgcv package;
I run these in a model selection framework using dredge::MuMIn package;
I then subset the 95% confidence set of models and perform model average;
Using the model averaged 95% coefficient set I then predict fish biomass spatially over new area, i.e. planning units;
Part 2: Generting time to recovery models
I fit ricker, asymtote and logistic functions to fish biomass against age of protection using the nls package;
I then apply these time to recovery models to the modelled biomass to spatially predict the time to recovery over the Western Indian Ocean reefscape.

