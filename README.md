# BriskAlgorithm

In this project we have implemented the Brisk Algorithm in parallel using Mpi and OPENMP . 
Brisk Algorithm is a feature extraction algorithm which helps us to extract important and peculiar features from an image .
It is rotation and scale invariant, this makes it a very good algorithm for image matching applications.
We have used Mpi to distribute the data among two nodes and have used openmp to parallelize the operations needed 
to be performed on various octaves (.i.e on various layers) .Mpi creates various child processes and openmp creates threads 
to perform operations parallely.We have used OPENCV C++ library for programming . 
We have taken the source code for brisk algorithm from opencv c++ library and have parallelized the code.
