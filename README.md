#Supplementary material for "Evaluating a hierarchical approach to landscape level harvest scheduling" by Kyle Eyvindson, Jussi Rasinmäki, Annika Kangas in Canadian Journal of Forest Research, doi: 10.1139/cjfr-2017-0298

For a detailed description of the method, please refer to the published article.

The key files to run this process are:
1: Hierarchical_Programming.ipynb

This iPython notebook includes detailed comments describing the process. In the notebook, all parameters which can be modified are included in Section 1. The optimization models are created in Pyomo, and they directly relate to the models formulated in the published article.

2: data_heir_pseudo.dat

This is the input data for the models. A set of 1000 stands are provided, each stand has a number of schedules generated. All values are per hectare, and through randomly selecting a set of stands with varying areas, a much larger problem can be generated.
