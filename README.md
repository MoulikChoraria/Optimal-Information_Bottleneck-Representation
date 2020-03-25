# Study to evaluate accuracy of information estimators & find optimal Information bottleneck representation from finite samples.

The information bottleneck method is a technique in information theory to explore the trade-off between compression and representational accuracy.  

In this study, two major paradigms of information estimation, nearest neighbor and kernel density estimators are compared. A heuristic is developed to solve the information bottleneck problem via coordinate descent when using k-NN estimators, after developing a differentiable approximation for the exponential time complexity problem.  


## Files:
- `Entropy_Eval.ipynb`: Jupyter Notebook: Script for comparing estimators in different settings.  
- `Coordinate_Ascent.ipynb`: Jupyter Notebook:  Proof of Concept of developed heuristic.
