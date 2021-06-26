# Parallel-
 parallel implementation with OpenMP
 parallel implementation with OpenMP tasks
 parallel implementation with MPI
 hybrid MPI+OpenMP parallel implementation

gcc/mpicc compilers 

OPENMP:
gcc -Wall -O3 -o openmp openmp.c -lm -fopenmp 
same with tasks 

MPI:
mpicc -Wall -O3 -o mpi mpi.c -lm 

MPI-OPENMP: 

mpicc -Wall -O3 -o mpiopenmp mpiopenmp.c -lm -fopenmp 




