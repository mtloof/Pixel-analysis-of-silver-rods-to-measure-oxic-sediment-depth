# Pixel Analysis to Measure Oxic Sediment Depth with Silver Rods

This analysis was created as part of a larger project to evaluate the biogeochemical effects of bottom trawling on benthic conditions in the Baltic Sea.

For context, silver rods can be inserted into sediment samples and below the oxic layer, sulfide will react with the silver rods and darken the silver rod.

Thus by inserting a silver rod into sediment and marking the surface level, one can measure the oxic depth from the surface mark to the darkening. However, due to the darkening being gradient and measurement of each rod relying on manual measurements with a ruler, uncertainties are clear.

This script was created with the aim of providing repeatable measurements from the same silver rods and act as a baseline for further methodological improvement with adjustable parameters and later calibration with manual measurements.

The two images included in the repo, show the silver rod measurements from sediment samples before and after stirring the sediment. This is to simulate the disruption of the benthic layer during bottom trawling.

For canny-edge detection the cv2 package is used.
