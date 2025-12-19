# CSE_407_project_notebooks
This repository contains the notebooks used for my CSE_407 course project


The green_computing main_file_used_on_report.ipynb notebook file contains all the neccessary results and visualiztions we used in our project report. It contains our custom CNN architecture and pruned results.

In the secondary_unsuccesful_with_accuracy_file.ipynb file quantization was successful and it was done firstly but the accuracy even in MNIST dataset was too low so we didn't fix the notebook file variable errors below and it was unsuccessful .  It contained our custom CNN baseline which we later fixed in the main report . Since it used smaller kernel size in custom CNN the GFLOPs were much lower than the one we used in our report.

Even though GFLOPs were higher in our main custom CNN architecture the size of the CNN was still very low compared to pretrained models which we used and it aligns with our report title since we wanted to make a custom CNN ultimately that would be lightweight and can be used in edge devices. So we decided to use the main notebook results for our project. the reasons were discussed more briefly in project report discussion section.  


In the experiment_on_structured_pruning.ipynb we tried more complicated methods such as structured pruning instead of unstructured pruning , quantization in different method and simply removing a percentage of parameters from pre-trained models we couldn't successfully execute all the methods , hence we decided to not use these results in our report. 
