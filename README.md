# ComBat: Site effect correction using ComBat Harmonization

1. Installation
library(devtools)
install_github("jfortin1/CombatHarmonization/R/neuroCombat")

2. Multi-Site Harmonization
library(neuroCombat)
data.harmonized <- neuroCombat(dat = dat, batch = batch)
