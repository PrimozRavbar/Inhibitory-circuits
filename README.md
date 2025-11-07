The code used for "Inhibitory circuits generate rhythms for leg movements during Drosophila grooming" paper authored by: 
Durafshan Sakeena Syed, Primoz Ravbar, Julie H Simpson

Code written by Primoz Ravbar (2025) for the paper.

The contents:
- model code
- data analysis code

** All the model functionality is in one file: ELife_5p2.ipynb 

This code allows users to run the model and visualize the data, including making movies.
New model instances can be evolved.

The current model file is: solution_elife5p0h_34w

An example movie of the model is: video_solution_elife5p0h_34w.avi 

** Behavior data analysis code: MS_data_analysis_eLife_rev_GitHub_1p2.ipynb

This code is used to analyze segmented behavioral data.
The UMAPs can be plotted and colored according to the behavioral features or cluster (class) membership.  

The segments (individual leg movements) are described by various features and classified in several types of behavior (such as head cleaning or front leg cleaning). 
 *** LMM fitting is performed in the “ --- LMM Main Script ---” cell. ***
The code can be used to plot comparisons between groups for feature-class pairs. 
Variabilities of feature-class pairs can also be compared in the second part of the code file. 


Paper link: https://www.biorxiv.org/content/10.1101/2024.06.05.597468v2.full
