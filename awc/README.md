<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: awc

Published in: Not yet

Description: Test Adaptive Weights Clustering on several data sets.

Keywords: cluster-analysis, kullback-leibler, nonparametric, data visualization, data mining

Author: Kirill Efimov, Larisa Adamyan

Submitted [python]: Wed, September 19 2016 by Larisa Adamyan

Datafile: aggregation.arff, compound.arff, ds4c2sc8.arff, pathbased.arff, orange2.txt

Input: datafile name and lambda parameter, e.g. aggregation.arff 4.5. If nothing is given awc will run all data sets listed above.

Output: plot of 4 windows: 1. the weight matrix at the final step (white means 1, black is 0), 2. true weight matrix, 3. clustering based on the weight matrix, 4. true/wanted clustering.

Example: run python awc.py aggregation.arff 4.5 to see the clustering results on the aggregation datafile.  By running python awc.py without specifying arguments, awc will run on the all listed data files.

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/q_awc/master/awc/aggregation_result.jpg" alt="Image" />
</div>

