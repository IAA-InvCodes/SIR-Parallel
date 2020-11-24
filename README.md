# SIR-Parallel


SIR PARALLEL distribution
Authors: Stefan Thonhofer, Luis Bellot Rubio (IAA-CSIC)


The source code of SIR PARALLEL is in the directory /code. A test inversion 
of two SST/CRISP data cubes can be found in the directory /example. There 
you can also find all the input files and control files needed to run the 
code.

The code should be compiled with the Intel Fortran Compiler (ifort) and 
OpenMPI or MPICH. You must have the CFITSIO library installed on your system. 

To compile the code and create the executable, do 

make clean
make sir.x

You can run the code as in the script submit_job.sh provided in the 
/example directory.

For questions and comments, please contact

Luis Bellot Rubio
Instituto de Astrofísica de Andalucia-CSIC
lbellot at iaa.es

9 September 2020
