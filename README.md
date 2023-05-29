# Forward Protons short exercise for the 2023 CMSDAS

General information on CMSDAS 2023:
* [CMSDAS2023 main page](https://indico.cern.ch/event/1257234)
* [All short exercises](https://twiki.cern.ch/twiki/bin/view/CMS/WorkBookExercisesCMSDataAnalysisSchool#CmsDas2020CERN)
* [Exercise Twiki](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolCERN2023TaggedProtonsShortExercise)

**Video introduction** (from [CMSDAS2020](https://indico.cern.ch/e/cmsvdas2020)): [watch here!](https://videos.cern.ch/record/2730189)

## Recommended way to run the exercise (SWAN)
[![SWAN](https://swanserver.web.cern.ch/swanserver/images/badge_swan_white_150.png)](https://cern.ch/swanserver/cgi-bin/go/?projurl=https://github.com/CERN-CMS-DAS-2023/short-ex-pps.git)

To run the notebooks with regular CERN resources:
* Open a [SWAN session](https://swan.cern.ch) (the defaults are good, as of writing this pick software stack 102b and make sure to use Python3)
* In the SWAN session, click on the item on the right-hand side that says "Download Project from git" ![Download Project from git](download_project_trim.png)
* Copy-paste https://github.com/CERN-CMS-DAS-2023/short-ex-pps.git
* You're all set and can click on the three exercises, `Optical-Functions.ipynb`, `PixelEfficiencies.ipynb`, and `Dilepton-Protons.ipynb`

## Table of content

The exercise is organised in three Jupyter notebooks:

### 1. [Optical functions](https://nbviewer.jupyter.org/github/cmsdas/pps-short-exercise/blob/master/Optical-Functions.ipynb)  

In the first exercise, we will discuss proton transport and how protons propagate along the beamline under LHC magnetic field influence. Beam protons, taking place in diffractive interactions, can be scattered at small angles &theta; (usually measured in &mu;rad) and lose their momentum (typically denoted by &xi;). 

You can also consult with this [video](https://videos.cern.ch/record/2729663) recorded for DAS2020.

### 2. [Tracker Efficiencies](https://nbviewer.jupyter.org/github/cmsdas/pps-short-exercise/blob/master/PixelEfficiencies.ipynb)  

Tracker efficiencies are crucial to make proton data usable. Protons are available in two reconstruction flavors: singleRP and multiRP. We will now focus on the second category and see how we can extract adequate efficiency corrections ([video@CMSDAS2020](https://videos.cern.ch/record/2728988)).

Please open the notebook called 'PixelEfficiencies'. You can also consult [this video](https://videos.cern.ch/record/2729281).

### 3. [PPS protons in dilepton events](https://nbviewer.jupyter.org/github/cmsdas/pps-short-exercise/blob/master/Dilepton-Protons.ipynb)  

In the third exercise, we will implement what we learned from the first two exercises on the real data. The dataset we will use was recorded during the 2017 data taking-period. 

We will look at the central exclusive production of pair of muons. This measurement was the first obtained with PPS detectors (summarized in [JHEP 07 (2018) 153](https://link.springer.com/article/10.1007/JHEP07(2018)153))


