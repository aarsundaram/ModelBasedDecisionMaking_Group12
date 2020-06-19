## EPA1361 - Group 12 - Final Assignment
This is a model repository of Group 12's EPA1361 (Model-Based Decision-Making) Final Assignment. It is developed for finding candidate flood protection measures to be implemented by Gorssel (Dike-Ring4) using ema-workbench.

Resources
* [Jan Kwakkel repository](https://github.com/quaquel/epa1361_open/tree/master/final%20assignment)
* [EMA Workbench documentation](https://emaworkbench.readthedocs.io/en/latest/)
 
There are seven notebooks used:
1. Sensitivity Analysis - understanding the deep uncertainty and its relation to the outcomes of interest
2. Open Exploration_BaseCase_ProblemFormulation5 - exploration to No-Policy situation
3. Scenario_Discovery - discovering the worst-case and the average case as reference scenario for MS-MORDM
4. Multi-Scenario MORDM - searching for candidate policies to cope with worst-cases which also achieve the outcomes of interest
5. Candidate Policy selection - selecting optimum policies for each scenario 
6. Open Exploration_CandidatePolicies - exploration the candidate policies under deep uncertainty
7. Evaluating the Levers of Gorssel - exploration of some of the Gorssel levers under deep uncertainty

Nine py files contained are important for the model run. All notebooks, except for Candidate Policy selection, require functions from the py-files to work. No modification in the py-files from the originally provided in [Jan Kwakkel repository](https://github.com/quaquel/epa1361_open/tree/master/final%20assignment).

Two folders of data are:
1. data: consist of constants, parameters, default values, etc building the model
2. intermediatedata: consist of csv files of candidate policies, optimized policies and experiment results from notebooks which are used by other notebooks.
