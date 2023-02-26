# GOSPA

## Synopsis

This repository includes a MATLAB implementation of the generalized optimal sub-pattern assignment metric (GOSPA) to measure the distance between two finite sets of real vectors. Note that the two sets can have different cardinality. For details about GOSPA, check <https://arxiv.org/abs/1601.05585>. Also visit <https://youtu.be/M79GTTytvCM> for a 15-min presentation about the metric.

## Usage
An example 'exampleScript.m' is added to illustrate the usage of the GOSPA implementation. 

The current implementation of GOSPA (in GOSPA.m) is based on the **assign2D** function in the **TrackerComponentLibrary** from the below source. 
D. F. Crouse, "The tracker component library: free routines for rapid prototyping," in IEEE Aerospace and Electronic Systems Magazine, vol. 32, no. 5, pp. 18-27, May 2017
https://github.com/USNavalResearchLaboratory/TrackerComponentLibrary 
Thanks to Jan Krejčí for the suggestion in February 2023 to use the assign2D function in the TrackerComponentLibrary instead of the auction algorithm, to compute the optimal assignment.
