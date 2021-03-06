## Scenario IV

The R files above correspond to the simulation **Scenario IV** in the paper *Assessing Time-Varying Causal Effects in the Presenceof Cluster-Level Treatment Effect Heterogeneity*. A brief description of the R files needed is listed below.

File | Description
---- | ----
[part1.R](part1.R) | Test file part 1. 
[part2.R](part2.R) | Test file part 2.
[group.R](group.R) | Group structures.
[init.R](init.R) | Loads required packages and reads source files.
[sim-final.R](sim-final.R) | Simulation related functions.
[xgeepack.R](xgeepack.R) | Extensions for the geepack R package; extract, from a geepack model object, elements (e.g. working covariance, estimating function) needed for variance calculations.
[new-meat.R](new-meat.R) | Extensions for the geepack R package; extract, from a geepack model object, elements (e.g. working covariance, estimating function) needed for variance calculations.
[xzoo.R](xzoo.R) | Extensions for the zoo R package; apply lags, difference, rolling summaries to a sample of time series.
[test.RData](test.RData) | Simulation results for 100 clusters with 25 participants every cluster. 
[submit_workload.sh](submit_workload.sh) | Bash file (used for job array). 





