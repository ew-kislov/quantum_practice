# Quantum practice

## Task 1

### Run on supercomputer

- `cd task1 && make omp_polus && ./main_omp`

## Task 2

### Run

- `make mpi_mac && mpirun -np <proc_num> ./main <n> <k> [test]`  

`./main <n> <k>` to generate input and output arrays, `./main <n> <k> test` to test with generated arrays.  

## Author

Evgeniy Kislov