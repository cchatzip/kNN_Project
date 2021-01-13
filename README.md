# kNN_Project
calculation of the k nearest neighbors

To compile V0 use: gcc {name}.c -lopenblas -lm
To compile V1 use: mpicc {name}.c -lopenblas -lm

For large matrices i also used: export OMPI_MCA_btl_vader_single_copy_mechanism=none
