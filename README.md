# MultiThreading_102297010_


Multithreading enables a program to execute multiple tasks simultaneously, potentially improving performance and responsiveness, particularly in applications that involve I/O operations or parallelizable computations.

**Methodology**

This contains a Python script to benchmark the performance of matrix multiplication using different thread configurations. Here's how the benchmarking process works:

1. **Generating Matrices**: 
   - Random matrices of size 1000x1000 are generated to be multiplied.
   - A constant matrix of size 1000x1000 is generated to be multiplied with each random matrix.

2. **Multiplication with Varying Thread Configurations**:
   - The multiplication operation is performed with different thread configurations:
     - Single thread (T=1)
     - Multiple threads (T=2, T=3, T=4, T=5, T=6, T=7, T=8)
     - Combination of threads (e.g., (2, 3) indicates using 2 or 3 threads)
   - The time taken for each configuration is recorded.

3. **CPU Usage Measurement**:
   - CPU usage is measured before and after each multiplication operation using the `psutil` library.

4. **Result Analysis**:
   - The average time taken for matrix multiplication with each thread configuration is calculated.
   - CPU usage during the multiplication operations is recorded.
  
**Result Table-**


![image](https://github.com/akanksha2892/MultiThreading_102297010_/assets/122826707/d3681b5c-ebf2-421d-86c2-bc5730b9e3c2)



