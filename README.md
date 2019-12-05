# continuous-K-SVD
Discrete and 2D continuous K-SVD implemented in C++, using Eigen3 and OpenMP. Project written in Qt.  

In the case of 2D continuous K-SVD, discrete atoms are replaced  with 'continuous atoms' represented as linear combinations of  products of cosines mapping from a 2D coordinate plane. This  allows sparse coding unstructured signals of variable length as values sampled at locations in a 2D plane, as well as  predicting signal values away from the sampled locations (c.f. "Cloud Dictionary: Coding and Modeling for Point Clouds",  https://arxiv.org/abs/1612.04956).
