# Spectral-Embedding-Manifold-Learning
Scikit-learn implements Laplacian Eigenmaps, which finds a low dimensional representation of the data using a spectral decomposition of the graph Laplacian.

Spectral Embedding is an approach to calculating a non-linear embedding. Scikit-learn implements Laplacian Eigenmaps, which finds a low dimensional representation of the data using a spectral decomposition of the graph Laplacian. The graph generated can be considered as a discrete approximation of the low dimensional manifold in the high dimensional space. Minimization of a cost function based on the graph ensures that points close to each other on the manifold are mapped close to each other in the low dimensional space, preserving local distances.
Read the PDF with the Laplacian formulas and algorithm explained in detail. 

The best method to model manifolds is to treat the curved surface as being composed of several neighborhoods. If each data point manages to preserve the distance not with all the other points but only the ones close to it, the geometric relationships can be maintained in the data.
