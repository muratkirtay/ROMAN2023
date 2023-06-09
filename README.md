## ICDL2023

A repository for reproducing the results presented in ICDL 2023 submission.

> **Abstract:** Multimodal learning is an active research area that is gaining importance in human-robot interaction.  Despite the obvious benefit of levering multiple sensors for perceiving the world, its neural computational cost has not been addressed in robotics, especially in Robot-Robot Interaction (RRI). This study addresses the role of computational cost in multimodal processing by considering robot-robot interaction in a sequential multimodal memory recall task. In this setting, the learner (Nao) robot receives auditory-only, visual-only, or audio-visual information from an instructor (Pepper) robot and the environment regarding previously learned memory items. The goal of the learner robot is to perform the interactive task with as low as possible neural computational cost. The learner robot has two cognitive modules: a multimodal auto-associative network that stands for the perceptual-cognitive processing of the robot and an internal reward mechanism that monitors the changes in neural energy incurred by the processing of the attended stimuli.  The reward computed is used to build an action policy for minimizing the neural energy consumption over the sequential memory recall task. The experimental results show that having access to both auditory and visual information is beneficial not only for better memory recall but also for minimizing the cost of neural computation.   


## Folder and file descriptions
+ **Figures-and-Assets:** this folder contains various assets to run the experiment and figures in the paper.  
+ **Data:** this folder contains data collected during the experiments in .pkl format. Note that the figures in the paper and in **Figures** folder can be generated by using the .pkl files. 
+ **Scipts:** python scripts to generate the tables and figures can be found in the previous publication [ROMAN2022](https://github.com/muratkirtay/RoMAN2021) and [ADAPTIVE2019](https://github.com/muratkirtay/ADAPTIVE2019) repos were used.  
+ **versions.txt:** a text file contains the version numbers of the python packages for running the scripts.

