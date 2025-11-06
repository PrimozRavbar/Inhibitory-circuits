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

An example movie of the model is: Model_MS.avi  This movie is referenced as Video 1 in the paper.

** Behavior data analysis code: Segment_classification_GH.ipynb

This code is used to reduce the dimensionality of the segmented behavioral data and for clustering. 
The former is done by UMAP algorithm, and the latter is accomplished by agglomerative clustering over the low dimensional space.
Several alternative options are also included. 
The UMAPs can be plotted and colored according to the behavioral features or cluster (class) membership.  

Paper link: https://www.biorxiv.org/content/10.1101/2024.06.05.597468v2.full
