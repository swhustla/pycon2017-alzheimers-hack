# PyCon Alzheimer's Challenge Hackathon: Bonus Tasks

## Tasks 1 & 2: Try to top the leaderboard by generating accurate forecasts
See https://github.com/noxtoby/TADPOLE/blob/master/evaluation/TADPOLE_SimpleForecastExampleLeaderboard.py

## Tasks 3: Perform some software engineering magic on the scripts in our github
See https://github.com/noxtoby/TADPOLE

    - (i) reading in the TADPOLE data sets and outputting a forecast in the right format. If you want to do this task look at this script https://github.com/noxtoby/TADPOLE/blob/master/evaluation/TADPOLE_SimpleForecastExampleLeaderboard.py

    - (ii) same as before but for the actual submission (not the leaderboard submission). We currently have a MATLAB script for this but not a Python equivalent. If you want to do this task look at this script https://github.com/noxtoby/TADPOLE/blob/master/evaluation/TADPOLE_SimpleForecastExample.m

    - (iii) evaluating forecasts given labelled test data. If you want to do this task look at this script https://github.com/noxtoby/TADPOLE/blob/master/evaluation/evalOneSubmission.py

    - (iv) creating the leaderboard datasets and a dummy D4 dataset. If you want to do this task look at these scripts https://github.com/noxtoby/TADPOLE/blob/master/evaluation/makeLeaderboardDataset.py and https://github.com/noxtoby/TADPOLE/blob/master/evaluation/makeDummyD4.py

## 4. Robustifying the python scripts that are wrapped with the TADPOLE data package currently stored on the ADNI site
These currently do the job of showing how the data sets were generated, but are somewhat broken insofar as they don’t run because the input data sets they use from ADNI have grown since they were first written.

Useful references
- https://github.com/noxtoby/TADPOLE/blob/master/TADPOLE_D1_D2.py
- https://github.com/noxtoby/TADPOLE/blob/master/TADPOLE_D2.py
- https://github.com/noxtoby/TADPOLE/blob/master/TADPOLE_D3.py

## 5. Augmenting those data-construction scripts so that they add other potentially useful information, such as genetic features or features of other imaging modalities e.g. DTI.

The following data may be quite valuable:
- BSI (Boundary Shift Integral) -  spreadsheet name " Fox Lab - BSI Measures [ADNI1,GO,2]"
- DMN connectivity - spreadsheet name "Mayo (Jack Lab) - Default Mode Network Connectivity [ADNIGO,2] "
- MRI infarcts - spreadsheet " MRI Infarcts [ADNI1,GO,2] "
- White Matter Hyperintensities - spreadsheet " UCD- White Matter Hyperintensity Volumes [ADNI2] "
- Arterial Spin Labelling images - spreadsheet "UCSF - ASL Perfusion CBF by FreeSurfer ROI [ADNIGO,2] "
- Tensor-based Morphometry - spreadsheet "USC - Tensor-based Morphometry Versions 2.0 and 2.1 [ADNI1,GO,2] "
