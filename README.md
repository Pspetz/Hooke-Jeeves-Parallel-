# Parallel-

multistart_hooke_omp: parallel implementation with OpenMP

multistart_hooke_omp_tasks: parallel implementation with OpenMP tasks

multistart_hooke_mpi: parallel implementation with MPI

multistart_hooke_mpi_omp: hybrid MPI+OpenMP parallel implementation

gcc/mpicc compilers 

OPENMP:
gcc -Wall -O3 -o openmp openmp.c -lm -fopenmp 
same with tasks 

MPI:
mpicc -Wall -O3 -o mpi mpi.c -lm 

MPI-OPENMP: 

mpicc -Wall -O3 -o mpiopenmp mpiopenmp.c -lm -fopenmp 




