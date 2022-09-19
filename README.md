# Serial Reaction Time Task (SRTT) Online Experiment
______________
This repository contains code associated with the following manuscript:

Kaur, J., Balasubramaniam, R (2022). Sequence Learning in an Online Serial Reaction Time Task: The Effect of Task Instructions. (https://doi.org/10.1123/jmld.2021-0064).
______________
This the first project I completed as a PhD student. Due to COVID-19, data for this project was acquired entirely online and it allowed us to study the effect of learning using the standard Serial Reaction Time Task (SRTT) in an online environment.

The SRTT task was build using labs.js (https://lab.js.org/) and was deployed using Qualtrics online via the UC Merced SONA system. Subjects took part in the study and earned extra course credit after the completion of the task.

Project aims: testing the effect of task instructions in an SRTT paradigm by randomly assigning participants to the explicit or implicit learning conditions, while making use of both the auditory and visual stimuli;and to determine whether the SRTT paradigm can be employed online to study sequence learning.

There are 4 different RStudio Scripts files used for analysis, and they are as follows:
File 1: 1_implicitdataonly_accuracy.Rmd: is used for analyzing only the implicit learning data's accuracy for this project; 
File 2: 2_explicitdataonly_accuracy.Rmd: is used for analyzing only the explicit learning data's accuracy for this project; 
File 3: 3_implicitdataonly.Rmd: is used for analyzing the reaction time data associated with the implicit learning condition; 
File 4: 4_explicitdataonly.Rmd: is used for analyzing the reaction time data associated with the implicit learning condition; 
File 5: Acc.Data.Viz.Rmd: Data visualization code to plot out accuracy across the different learning conditions; 
File 6: Implicit+Explicit Data Visualization: Data Visualization code to plot out the accuracy across the different learning condtiions


Additionally, I've added my python scripts, as I initially used python to visualize and analyze my datasets.
