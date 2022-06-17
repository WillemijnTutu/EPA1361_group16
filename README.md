# EPA1361 Group16

|Group Number |19|
|---|---|
|Daan Bos| 4477073 |
|Annemieke Brouwer| 4575687|
| Anne-Kee Doing |4453972 |
|Maaike Tran | 4496108 |
|Willemijn Tutuarima | 4651723|
|Laila Youssifou | 4312309 |

Email:
w.a.tutuarima@student.tudelft.nl

Version:
1.0

## Introduction

This github repository includes all the files used for the final assignment of group 16
for the course EPA1361. This includes the Room for the River model provided for the course.
The original repository for this model can be found [here](https://github.com/quaquel/epa1361_open).
Next to this, the EMA workbench is used throughout the analysis. This documentation for this
workbench can be found [here](https://github.com/quaquel/EMAworkbench).

## Files

### RfR model:
* [dike_model_function.py](dike_model_function.py): main function of the model
* [funs_dikes.py](funs_dikes.py): Helper functions regarding dike behaviour
* [funs_economy.py](funs_economy.py): Helper functions regarding economy behaviour
* [funs_generate_network.py](funs_generate_network.py): Helper functions to generate the network
* [funs_hydrostat.py](funs_hydrostat.py): Helper functions regarding hydro statistics behaviour
* [problem_formulation.py](problem_formulation.py): Helper file which specified different problem formulations
* [setup.py](setup.py): setup file for ema workbench
* [data](data): folder with all the data files used in the RfR model

### Analysis:

All of the analysis files use the RfR model and all its dependencies. The files in this folder are the following:
* [Global_sensitivity_analysis.ipynb](Global_sensitivity_analysis.ipynb): Jupyter notebook with the code of the global sensitivity analysis including methods of Sobol, Extra Trees Random Forest and Feature Scoring.
* [Scenario_Analysis.ipynb](Scenario_Analysis.ipynb): Jupyter notebook with the code of the performed scenario analysis including prim and dimensional stacking
* [MORDM.ipynb](MORDM.ipynb): Jupyter notebook with code of the performed MORDM run
* [AnalysisMORDM.ipynb](AnalysisMORDM.ipynb): Jupyter notebook with code used to perform visual and statistical analysis on the output of the MORDM run
* [ouput_data](output_data): Folder with all output data creates through the analysis
* [figures](figures): Folder with all the figures creates through the analysis

## Dependencies
The dependencies necessary to execute the code can be found in the [requirements](requirements) file in the repository.
Next to this all of the analysis is dependent on the EMAworkbench.
